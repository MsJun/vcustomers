<template>
  <div class="alert alert-warning alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  {{massage}}
</div>
</template>

<script>
export default {
  name: 'about',
  props:["massage"],
  data () {
    return {
      
    }
  }
}
</script>

<style scoped>

</style>
