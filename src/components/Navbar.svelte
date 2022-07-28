<script>
  import RegularText from '../typography/RegularText.svelte'
  import HeaderText from '../typography/HeaderText.svelte'
</script>

<nav>
  <div>
    <HeaderText>Paper_Blog</HeaderText>
    <RegularText>This is a sample blog, I'm learning svelte</RegularText>
  </div>
</nav>

<style>
  nav {
    border-bottom: 1px solid grey;
  }
  div {
    margin-left: 5%;
    display: grid;
    grid-template-columns: min-content 1fr;
    grid-gap: 20px;
    align-items: baseline;
  }
</style>
