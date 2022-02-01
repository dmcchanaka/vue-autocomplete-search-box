<template>
<div class="container">
<h3>Search Box </h3>

<div class="input-group mb-3">
  <input type="text" class="form-control" placeholder="Search Box" aria-describedby="basic-addon2">
  <div class="input-group-append">
    <span class="input-group-text btn btn-info" id="basic-addon2">Search</span>
  </div>
</div>
</div>
</template>
<script>
export default {
  name: 'search-bar',
  props: {
  },
  setup(){

    return {}
  }
}
</script>