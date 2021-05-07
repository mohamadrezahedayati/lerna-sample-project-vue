<template>
    <div class="container-visit-list">
        visit list component (npm)
      <div v-for="item in 5" :key="item">
        <VisitCard />
      </div>
      {{searchValue}}
    </div>
</template>

<script>
  import VisitCard from '@mohamad-org/visit-card/VisitCard'
    export default {
      props: {
        searchValue: {
          type: String,
          default: ''
        },
      },
        components:{
          VisitCard
        }
    }
</script>

<style lang="css" scoped>
.container-visit-list{
  margin-top: 10px;
  background-color: darkorange;
  padding: 10px;
}
</style>