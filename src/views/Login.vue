<template>
  <form class="form">
    <v-text-field
      v-model="name"
      :error-messages="nameErrors"
      :counter="10"
      label="Name"
      required
      @input="$v.name.$touch()"
      @blur="$v.name.$touch()"
    ></v-text-field>
    <v-text-field
      v-model="email"
      :error-messages="emailErrors"
      label="E-mail"
      required
      @input="$v.email.$touch()"
      @blur="$v.email.$touch()"
    ></v-text-field>
    <v-btn class="mr-4" @click="submit">
      Entrar
    </v-btn>
  </form>
</template>

<script>
// @ is an alias to /src
export default {
  name: "Login",
  components: {}
};
</script>

<style lang="scss" scoped>
.form {
  width: 70vw;
  height: 20vh;
  margin: 0 auto;
  transform: translateY(100%);
}
</style>
