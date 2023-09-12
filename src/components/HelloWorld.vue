<template>
  <v-container>
    <h1>Hola mundo</h1>
    <v-btn color="primary">Bienvenido</v-btn>
    <div class="text-center">
    <v-btn
      prepend-icon="mdi-check-circle"
      append-icon="mdi-account-circle"
      color="blue-darken-4"
    >
      <template v-slot:prepend>
        <v-icon color="success"></v-icon>
      </template>

      Button

      <template v-slot:append>
        <v-icon color="warning"></v-icon>
      </template>
    </v-btn>
  </div>
  </v-container>
</template>

<script>

export default {
  name: 'HelloWorld',

}
</script>
