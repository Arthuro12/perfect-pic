<script setup lang="ts">
import PpButtonLink from "../ui/PpButtonLink.vue";
</script>

<template>
  <header>
    <div class="page-header">
      <nav class="page-header__nav">
        <ul class="page-header__nav-col">
          <li class="page-header__nav-items">
            <a class="page-header__logo" href="#">Perfect-Pic</a>
          </li>
          <li class="page-header__nav-items">
            <a href="#">About Us</a>
          </li>
          <li class="page-header__nav-items">
            <a href="#">Contact Us</a>
          </li>
        </ul>
        <ul class="page-header__nav-col">
          <li class="page-header__nav-items">
            <PpButtonLink :is-icon-only="false" button-text="Login" link="#" />
          </li>
          <li class="page-header__nav-items">
            <PpButtonLink :is-icon-only="false" button-text="Signup" link="#" />
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
