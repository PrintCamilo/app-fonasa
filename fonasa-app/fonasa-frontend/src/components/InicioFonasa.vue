<template>
  <div>
    <h1>FONASA</h1>
    <p>Aplicación para automatización de consultas.</p>
    <div class="d-flex flex-column">
      <router-link to="/atender-paciente">Atender Paciente</router-link><br>
      <router-link to="/consultas-mas-pacientes">Consultas con más Pacientes</router-link><br>
      <router-link to="/liberar-consultas">Liberar Consultas</router-link><br>
      <router-link to="/fumadores-urgentes">Pacientes Fumadores Urgentes</router-link><br>
      <router-link to="/mayor-riesgo/:numHistoriaClinica">Pacientes de Mayor Riesgo</router-link><br>
      <router-link to="/mas-anciano">Paciente más anciano</router-link><br>
    </div>
  </div>
</template>

<script>
export default {
  name: "InicioFonasa",
};
</script>

<style scoped>



</style>
