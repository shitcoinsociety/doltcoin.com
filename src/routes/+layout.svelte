<script>
  import "$lib/global.css"

  /**
   * @typedef {Object} Props
   * @property {import('svelte').Snippet} [children]
   */

  /** @type {Props} */
  let { children } = $props();
</script>

<header>
  <div class="brand">
    <img src="/icon.svg" alt="D" class="h-8 inline-block" />
    DoltCoin
  </div>
  <menu>
    <li>
      <a class="github-button" href="https://github.com/shitcoinsociety/doltcoin" data-color-scheme="no-preference: light; light: light; dark: light;" data-size="large" data-show-count="true" aria-label="Star shitcoinsociety/doltcoin on GitHub">Star</a>
    </li>
  </menu>
</header>

<main>
  {@render children?.()}
</main>

<footer>
  Copyright © 2025 <a href="https://www.shitcoinsociety.com">Shitcoin Society</a>
</footer>