<script lang="ts">
  import '../app.css';
  import Seperator from './Seperator.svelte';
  import Backend from './tech/Backend.svelte';
  import DevOps from './tech/DevOps.svelte';
  import Frontend from './tech/Frontend.svelte';
  import Misc from './tech/Misc.svelte';
</script>

<svelte:head>
  <title>cz.cs</title>
</svelte:head>
<div class="min-h-screen bg-zinc-50 p-4 text-zinc-950 dark:bg-zinc-950 dark:text-zinc-50">
  <div class="flex justify-between">
    <div>
      <h1 class="font-display text-2xl font-bold">cz.cs</h1>
      <p>Full Stack Software Engineer</p>
    </div>
    <div class="flex items-center gap-4 self-center">
      <a
        class="opacity-50 transition-all hover:opacity-100"
        aria-label="My GitHub profile"
        href="https://github.com/cz-cs"
      >
        <img class="h-9 w-9 invert dark:invert-0" src="/img/github.webp" alt="" /></a
      >
      <a
        class="opacity-50 transition-all hover:opacity-100"
        aria-label="My Discord profile"
        href="https://discord.com/users/1148691793584590868"
      >
        <img class="h-9 w-9 invert dark:invert-0" src="/img/discord.webp" alt="" /></a
      >
    </div>
  </div>
  <Seperator />
  <div class="space-y-2">
    <h2 class="text-xl font-semibold">About me</h2>
    <div class="space-y-1">
      <p>
        I gained interest in computers when I was around five years old. I still have a picture of
        me playing around with the Windows XP settings menu!
      </p>
      <p>I started coding when I was 7, with an Arduino microcontroller.</p>
      <p>
        When my parents finally let me have a computer at 9 years old, I discovered C# and the .NET
        framework. From there, I started using the two to make desktop programs, more embedded
        software, CLIs, Discord bots, you get the gist.
      </p>
      <p>
        I did that until I was 13, when I gained interest in web technologies and how websites were
        made and maintained.
      </p>
      <p>
        Now, I make websites (mainly <a
          class="font-medium underline-offset-4 hover:underline"
          href="https://gears.sh">gears.sh</a
        > at the moment. hopefully released soon!!).
      </p>
    </div>
    <p class="text-sm font-medium opacity-50">
      TL;DR: I've been fascinated with computers basically my whole life.
    </p>
  </div>
  <Seperator />
  <div class="space-y-2">
    <h2 class="text-xl font-semibold">Technologies I'm familiar with</h2>
    <h3 class="text-lg font-medium">Frontend</h3>
    <Frontend />
    <h3 class="text-lg font-medium">Backend</h3>
    <Backend />
    <h3 class="text-lg font-medium">DevOps</h3>
    <DevOps />
    <h3 class="text-lg font-medium">Misc.</h3>
    <Misc />
    <img
      class="mt-6 h-12 w-12"
      src="/img/professional-visual.webp"
      alt="Adobe Professional Visual Design certificate"
    />
  </div>
  <Seperator />
  <div class="space-y-2">
    <h2 class="text-xl font-semibold">Stuff I've made</h2>
    <ul class="text-sm">
      <li>
        <a
          class="font-medium underline-offset-4 hover:underline"
          href="https://zenfake.com"
          target="_blank">zenfake.com</a
        >
      </li>
      <li>
        <a
          class="font-medium underline-offset-4 hover:underline"
          href="https://discord.gg/edgeware"
          target="_blank">Edgeware's Discord bot</a
        >
      </li>
      <li class="opacity-50">
        <a aria-disabled="true" class="font-medium" href="https://gears.sh/" target="_blank"
          >Gears (soon)</a
        >
      </li>
    </ul>
  </div>
  <div class="-mx-4 my-5 h-px bg-zinc-200 dark:bg-zinc-800"></div>
  <p class="text-center text-sm font-medium opacity-50">
    copyright cz.cs or whatever happy new year | icons by <a
      class="font-semibold underline-offset-4 hover:underline"
      href="https://skillicons.dev"
      target="_blank">Skill Icons</a
    >
  </p>
</div>
