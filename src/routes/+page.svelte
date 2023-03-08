<script>
  import Comp from '$routes/comp.svelte'
</script>
<p>
  (Before Comp)
  <Comp>
    <p>This shouldn't be visible.</p>
  </Comp>
  (After Comp)
</p>
