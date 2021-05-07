<template>
    <div class="container-patient-summary">
        <input type="text" v-model="textSummary" @input="showChange()">
        Patient Summary component (npm)
    </div>
</template>

<script>
    export default {
        data() {
            return {
                textSummary:''
            }
        },
        methods: {
            showChange(){
                this.$emit('getSearchValue',this.textSummary)
            }
        },
    }
</script>

<style lang="css" scoped>
.container-patient-summary{
    background-color: darkorange;
    padding: 10px;
}
</style>