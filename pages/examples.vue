<template>
  <div class="flex-grow flex overflow-hidden">
    <div class="px-8 py-8 bg-gray-200 w-64 overflow-y-auto">
      <div class="font-bold mb-4">Examples</div>
      <div v-for="i in 100">
        <nuxt-link to="/examples/page-1" class="block mb-4">Examples Page 1</nuxt-link>
        <nuxt-link to="/examples/page-2" class="block mb-4">Examples Page 2</nuxt-link>
      </div>
    </div>
    <div>
      <nuxt-child/>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'default'
}
</script>
