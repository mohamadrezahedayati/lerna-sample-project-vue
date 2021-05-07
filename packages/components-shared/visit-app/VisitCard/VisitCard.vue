<template>
    <div class="container-visit-card">
        visit card component (npm)
        <br>
        <PrescriptionSumList />
    </div>
</template>

<script>
    import PrescriptionSumList from '@mohamad-org/prescription-sum-list/PrescriptionSumList'
    export default {
        components:{
            PrescriptionSumList
        }
    }
</script>

<style lang="css" scoped>
.container-visit-card{
    border: 1px rgb(0, 81, 255) solid;
    padding: 10px;
    margin-bottom: 10px;
    background-color: white;
}
</style>