<template>
  <div class="alert alert-primary" role="alert">
    {{message}}
  </div>
</template>

<script>
export default {
      name : "App",
  data() {
    return {
      message: 'จาก Conponents VueJs นะครับ'
    }
  }
}
</script>