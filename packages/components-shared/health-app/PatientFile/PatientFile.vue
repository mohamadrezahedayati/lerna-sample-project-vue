<template>
    <div class="container-patient-file">
        patient file component (npm)
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

<style lang="css" scoped>
.container-patient-file{
    padding: 10px;
    background-color: rgb(127, 0, 139);
}
</style>