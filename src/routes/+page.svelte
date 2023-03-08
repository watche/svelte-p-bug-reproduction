<script>
  import Comp from '$routes/comp.svelte'
</script>
<p>
  (Before Comp)
  <Comp>
    <svelte:fragment slot="hidden"><p>This should be visible</p></svelte:fragment>
    <svelte:fragment slot="alsoHidden"><p>This should be visible</p></svelte:fragment>
    <div>
      <section>
        <span>
          This should not!
        </span>
      </section>
    </div>
  </Comp>
  (After Comp)
</p>
