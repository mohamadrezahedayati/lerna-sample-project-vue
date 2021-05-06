<template>
    <div>
        visit list component 
      <div v-for="item in 5" :key="item">
        <VisitCard />
      </div>
    </div>
</template>

<script>
  import VisitCard from '@mohamad-org/visit-card/VisitCard'
    export default {
        components:{
          VisitCard
        }
    }
</script>

<style lang="scss" scoped>

</style>