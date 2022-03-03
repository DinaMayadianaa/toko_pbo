<template>
<main>
  <navigasi/>
  <div class="jumbotron">
  <home />
  </div>
</main>
</template>

<script>
export default {
  mounted(){
    console.log(this.$supabase)
  }
}
</script>
