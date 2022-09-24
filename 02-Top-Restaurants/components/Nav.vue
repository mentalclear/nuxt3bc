<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="/">Restaurantly</a>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
            <li class="nav-item active">
                <a class="nav-link" href="/">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="/restaurants">Restaurants</a>
            </li>
        </ul>
    </div>
  </nav>
</template>

<script setup lang="ts">

</script>

<style scoped>
.ml-auto {
    margin-left: auto;
}

.navbar-brand {
    padding-left: 1rem;
}
.navbar-nav {
    padding-right: 1rem;
}
</style>