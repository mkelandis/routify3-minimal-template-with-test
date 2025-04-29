<script>

  import { params } from '@roxi/routify'
  $: id = $params.id

</script>

<p>
Your address id is <b>{id}</b>
</p>

<a href="/">Home</a>