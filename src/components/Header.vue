<template>
  <div class="row">
    <nav class="navbar navbar-expand-lg navbar-light bg-success position-fixed fixed-top border border-primary">
      <ButtonCheck/>
      <div class="collapse navbar-collapse offset-4 gx-3" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0 text-center mt-3">
          <li class="nav-item me-3">
            <i class="bi bi-book-fill h4"></i>
            <RouterLink aria-current="page" class="nav-link active" to="/book">Books</RouterLink>
          </li>
          <li class="nav-item me-3">
            <i class="bi bi-newspaper h4"></i>
            <RouterLink aria-current="page" class="nav-link active" to="/news">Gallery</RouterLink>
          </li>
          <li class="nav-item dropdown me-3 ms-2">
            <i class="bi bi-backpack2-fill h4"></i>
            <RouterLink aria-current="page" class="nav-link active" to="/student">Students</RouterLink>
          </li>
          <li class="nav-item dropdown">
            <i class="bi bi-journal-bookmark-fill h4"></i>
            <RouterLink aria-current="page" class="nav-link active" to="/coures">Courses</RouterLink>
          </li>
          <li class="nav-item dropdown ms-3">
            <i class="bi bi-mortarboard-fill h4"></i>
            <RouterLink aria-current="page" class="nav-link active" to="/teachers">Teachers</RouterLink>
          </li>
        </ul>
        <div>
          <FormSearch/>
        </div>
      </div>
    </nav>
  </div>
</template>

<script setup lang="ts">
import ButtonCheck from "@/components/ButtonCheck.vue";
import FormSearch from "@/components/FormSearch.vue";
</script>