<script>

  import { goto } from '@roxi/routify'

  function gotohelper() {
    $goto('/addresses/2', {}, {strict: false});
  }

  function gotoreplace() {
    $goto('/addresses/3', {}, {strict: false, replace: true});
  }
</script>

<h1>Welcome to Your New Routify 3 Project!</h1>

<p>
<a href="/addresses/1">Embedded href</a>
</p>

<p>
<button on:click={gotohelper}>goto helper</button>
</p>

<p>
<button on:click={gotoreplace}>goto replace</button>
</p>