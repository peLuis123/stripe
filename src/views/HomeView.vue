<template>
  <div>
    <div>
      <v-app-bar elevation="4" color="#00C853">
        <v-toolbar-title> Correo@Correo.com </v-toolbar-title>
        <v-spacer />
        <v-btn elevation="0" color="#00C853">Market-Place</v-btn>
        <v-btn elevation="0" color="#00C853">panel</v-btn>
      </v-app-bar>
    </div>
    <div class="d-flex justify-center text-center mt-6">
      <FormEmail />
    </div>
    <div >
      <FormCheckout/>

    </div>
    <div>
      paso 3
    </div>
  </div>
</template>

<script>
import FormEmail from '../components/FormEmail'
import FormCheckout from '../components/FormCheckout'

export default {
  name: 'HomeApp',

  components: {
    FormEmail,
    FormCheckout
  }
}
</script>
