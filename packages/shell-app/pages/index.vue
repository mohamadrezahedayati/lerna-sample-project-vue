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
  margin: 6px auto;
  height: 88.6vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
