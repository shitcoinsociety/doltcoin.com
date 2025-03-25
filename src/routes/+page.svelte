<script>
  import { onMount } from 'svelte';
  import { page } from '$app/stores';

  let hostname = $state('');

  onMount(() => {
    const url = new URL(window.location.href);
    hostname = url.hostname;
  });
</script>

<h1 class="brand">
  DoltCoin
</h1>

<h2>
  The blockchain for simple people.
</h2>

<p>
  DoltCoin is an upcoming blockchain and crypto-currency utilizing <a href="https://github.com/dolthub/dolt">Dolt</a> as its backing database. It has a focus on simplicity and
  ease of use, and is designed to be accessible by everyone, regardless of their
  technical background.
</p>

<h2>
  Get started
</h2>

<p>
  DoltCoin is still under development.
  Please visit our <a href="https://github.com/shitcoinsociety/doltcoin">GitHub</a> page for the latest updates.
</p>



