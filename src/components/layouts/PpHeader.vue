<script setup lang="ts">
import PpButtonLink from "../ui/PpButtonLink.vue";
</script>

<template>
  <header>
    <div class="page-header">
      <nav class="page-header__nav">
        <ul class="page-header__nav-col">
          <li class="page-header__nav-items">
            <PpButtonLink
              class="page-header__logo"
              :is-icon-only="false"
              button-text="Perfect-Pic"
              link="#"
            />
          </li>
          <li class="page-header__nav-items">
            <PpButtonLink
              :is-icon-only="false"
              button-text="About Us"
              link="#"
            />
          </li>
          <li class="page-header__nav-items">
            <PpButtonLink
              :is-icon-only="false"
              button-text="Contact"
              link="#"
            />
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
