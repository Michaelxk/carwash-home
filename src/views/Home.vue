<template>
  <div class="home">
    <Login />
  </div>
</template>
<script>
import Login from "@/views/Login";

// @ is an alias to /src
export default {
  name: "Home",
  components: { Login }
};
</script>
