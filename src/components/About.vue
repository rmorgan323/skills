<template>
  <div class="about">
    <h1>Hello, {{ user_name }}, this is an about page.</h1>
    <p>Some stuff that's great and belongs on an about page</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      user_name: this.$route.params.name
    }
  }
}
</script>