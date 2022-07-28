<script>
  import RegularText from '../typography/RegularText.svelte'
  import HeaderText from '../typography/HeaderText.svelte'
</script>

<nav>
  <div class="home-link">
    <a href="https://www.hymowitz.org" target="_blank">EH</a>
  </div>
  <div class="header-text">
    <HeaderText>Paper_Blog</HeaderText>
    <RegularText>This is a sample blog, I'm learning svelte</RegularText>
  </div>
</nav>

<style>
  nav {
    border-bottom: 1px solid black;
    background-color: inherit;
  }
  .header-text {
    margin-left: 10%;
    display: grid;
    grid-template-columns: min-content 1fr;
    grid-gap: 20px;
    align-items: baseline;
  }

  .home-link {
    position: absolute;
    right: 5%;
    top: 20px;
  }
</style>
