<!-- uncomment this h1 to see tha app working fine -->
<!-- <h1>Hi</h1> -->


<!-- comment all this out to see the app work just fine with an h1 -->
<script>
  import { Motion } from 'svelte-motion'
</script>

<Motion let:motion>
  <div use:motion/>
</Motion>

<style>
  div {
    width: 256px;
    height: 256px;
    background: red;
  }
</style>