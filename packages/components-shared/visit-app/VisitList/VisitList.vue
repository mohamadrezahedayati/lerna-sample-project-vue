<template>
    <div>
        visit list component 
      <div v-for="item in 5" :key="item">
        <VisitCard />
      </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>