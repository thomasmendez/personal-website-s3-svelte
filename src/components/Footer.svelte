<script>
  import Icon from '@iconify/svelte';
</script>

<style>
  .footer {
    border-top: 1px solid black;
  }
</style>

<footer class="footer p-4 flex justify-between">
  <div class="text-left pl-4">© {new Date().getFullYear()} Copyright</div>
  <div class="text-center md:flex md:flex-col md:items-center">
    <div class="mb-2">
      <a href="https://svelte.dev" target="_blank" class="text-orange-600 flex items-center">
        Created with Svelte
        <Icon icon="logos:svelte-icon" class="w-5 h-5 ml-1" />
      </a>
    </div>
    <div class="mb-2">
      <a href="https://vuejs.org" target="_blank" class="text-green-600 flex items-center">
        Check out the Vue version!
        <Icon icon="logos:vue" class="w-5 h-5 ml-1" />
      </a>
    </div>
    <div>
      <a href="https://reactjs.org" target="_blank" class="text-blue-400 flex items-center">
        Check out the React version!
        <Icon icon="logos:react" class="w-5 h-5 ml-1" />
      </a>
    </div>
  </div>
  <div class="text-right space-x-4 flex items-center pr-4">
    <a href="https://www.linkedin.com/" target="_blank">
        <Icon icon="mdi:linkedin" class="w-5 h-5 ml-1" />
    </a>
    <a href="https://github.com/" target="_blank" >
        <Icon icon="mdi:github" class="w-5 h-5 ml-1" />
    </a>
    <a href="mailto:your@email.com">
        <Icon icon="ic:baseline-email" class="w-5 h-5 ml-1" />
    </a>
  </div>
</footer>
  