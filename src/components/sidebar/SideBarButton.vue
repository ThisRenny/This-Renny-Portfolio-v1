<template>
  <div class="btn-group-vertical" role="group" aria-label="...">
    <button type="button" class="btn btn-default">
      {{ name }}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    name: String,
  }
}
</script>

<style>
.btn-default {
  color: #ffffff;
}

.btn-default:hover {
  border-color: #ffffff;
  background: #ffffff;
}

</style>