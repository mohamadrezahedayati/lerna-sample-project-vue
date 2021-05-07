<template>
    <div>
        <PatientSummary />
        <VisitList />
    </div>
</template>

<script>
    import PatientSummary from '@mohamad-org/patient-summary/PatientSummary'
    import VisitList from '@mohamad-org/visit-list/VisitList'
    export default {
        components:{
            PatientSummary,VisitList
        }
    }
</script>

<style lang="scss" scoped>

</style>