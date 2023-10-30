<script lang="ts">
  import "../app.postcss";
  import "/src/prism.css"
  import Header from './header.svelte'
</script>

<div class="w-full p-4 md:p-6 lg:p-8 xl:p-12">
  <Header />
  <main class="flex flex-col w-full items-center">
    <slot />
  </main>
</div>

