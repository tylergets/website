<template>
  <div class="w-full h-full bg-black text-gray-300 flex items-center justify-center">
    <div class="flex flex-col space-y-2">
      <div class="text-3xl font-mono tracking-widest">
        Tyler Getsay
      </div>
      <div class="flex justify-center">
        <a href="mailto:ty@tyler.fail">
          Building software for humans
        </a>
      </div>
      <div class="space-x-4 flex justify-around pt-10">
        <div>
          <a href="https://twitter.com/tylergets" class="btn">
            <font-awesome-icon :icon="['fab', 'twitter']"  />
          </a>
        </div>
        <div>
          <a href="https://github.com/tylergets" class="btn">
            <font-awesome-icon :icon="['fab', 'github']"  />
          </a>
        </div>
        <div>
          <a href="https://linkedin.com/in/tylergets" class="btn">
            <font-awesome-icon :icon="['fab', 'linkedin']"  />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scoped>
  .btn {
    @apply text-2xl;
    &:hover {
      @apply text-white;
    }
  }
</style>
