<script setup>
defineProps({
  href: String,
});
</script>

<template>
  <a
    :href="href"
    target="_blank"
    rel="noreferrer"
    class="underline hover:text-teal-800 decoration-teal-800 dark:hover:text-teal-500 dark:decoration-teal-500"
  >
    <slot />
  </a>
</template>
