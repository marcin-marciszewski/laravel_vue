<template>
  <h1>Index</h1>
  <h2>
    {{ message }}
  </h2>
  <Link href="/hello">
    Show Page
  </Link>
</template>

<script setup>
import { Link } from '@inertiajs/vue3'
defineProps({
    message: {
        type: String,
        default: 'No message',
    },

})
</script>
