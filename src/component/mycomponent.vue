<template>
  <div id="mycomponent">
    <input v-model="first" placeholder="FIRST NAME">
    <input v-model="last" placeholder="LAST NAME">
    <p> Hello {{first}} {{last}}</p>

    <a> by {{ author }} </a>
  </div>
</template>

<script type="text/javascript">
  export default {
    data () {
      return {
        author: "Brian H",
        first: "",
        last: ""
      }
    }
  }
</script>

<style>
</style>
