<script>
  import { ActionIcon } from '@svelteuidev/core';
  import { GithubLogo } from 'radix-icons-svelte';
  import { LinkedinLogo } from 'radix-icons-svelte';
</script>
<nav class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <span class="font-semibold text-xl tracking-tight"> <a href="/"> harrysharma1 </a></span>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="text-sm lg:flex-grow gap-x-5">
        <a href="/" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
          Home
        </a>
        <a href="/about" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
          About 
        </a>
        <a href="/contact" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white">
          Contact
        </a>
        <p class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white select-none">|</p>
        <a href="/experience" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white">
          Experience
        </a>
      </div>
      <div class="flex items-center justify-between flex-wrap space-x-5">
        <a href="https://github.com/harrysharma1"><ActionIcon variant="hover" ><GithubLogo size={60} color={"#333"}/></ActionIcon></a>
        <a href="https://www.linkedin.com/in/harry-sharma-567b21225/"><ActionIcon><LinkedinLogo size={60} color={"#0077b5"}/></ActionIcon></a>
      </div>
    </div>
</nav>