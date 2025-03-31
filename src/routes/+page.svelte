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
  DoltCoin ($DOLT) is an upcoming blockchain and crypto-currency utilizing <a href="https://github.com/dolthub/dolt">Dolt</a> as its backing database. It has a focus on simplicity and
  ease of use, and is designed to be accessible by everyone, regardless of their
  technical background.
</p>

<p>
  [This article](https://dev.to/buhrmi/dolt-as-a-backing-database-for-blockchains-1ba4) explains the
  original motivation for DoltCoin, and using Dolt as a backing database.
</p>

<h2>
  How to get DoltCoin?
</h2>

<p>
  You can get DoltCoin by running a DoltCoin node, or by buying it on an exchange.
</p>

<h3>Supported Exchanges</h3>


<p>
  We're incredibly proud to announce that DoltCoin will launch on
  <a href="https://www.shitcoinswap.com">Shitcoin Swap</a>, a new open-source
  trading platform and community.
</p>

<p>
  More exchanges will be announced in the future.
</p>


<h2>
  Run your own node
</h2>

<p>
  DoltCoin is still under development.
  Please visit our <a href="https://github.com/shitcoinsociety/doltcoin">GitHub</a> page for the latest updates.
</p>



