<template>
  <div class="d-flex" id="wrapper">
    <div id="page-content-wrapper" class="w-100">
      <div class="container-fluid my-4">
        <router-view />
      </div>
      <AppFooter />
    </div>
  </div>
</template>
<script>

</script>
<style>
#wrapper {
  display: flex;
}
#sidebar-wrapper {
  width: 250px;
}
#page-content-wrapper {
  flex: 1;
}
</style>