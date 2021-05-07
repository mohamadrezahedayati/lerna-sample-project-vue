<template>
  <div class="container">
    <PatientFile />
  </div>
</template>

<script>
import PatientFile from '@mohamad-org/patient-file/PatientFile'
export default {
  components:{
    PatientFile
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
