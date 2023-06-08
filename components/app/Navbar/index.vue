<template>
  <header class="flex w-full justify-between px-6 py-4 border-b-2 border-b-gray-50">
    <NuxtLink to="/">
      <h1 class="font-bold text-black">
        PromptHub
      </h1>
    </NuxtLink>
    <div>
      <button @click="signup">
        <b>Sign up</b>
      </button>
    </div>
  </header>
</template>

<script setup lang="ts">

function signup () {
  window.alert('Signup')
}
</script>
