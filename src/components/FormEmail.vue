<template>
  <v-card width="500" >
    <v-card-text>
      <v-text-field v-model="email" dense label="Ingresar Correo" outlined>
      </v-text-field>
      <v-btn color="primary">Confirmar Correo</v-btn>
    </v-card-text>
  </v-card>
</template>
<script>
export default {
  data () {
    return {
      email: ''
    }
  },
  methods: {
    name () {}
  }
}
</script>
