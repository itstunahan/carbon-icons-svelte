<script lang="ts">
  import Add16 from "carbon-icons-svelte/lib/Add16";
</script>

<Add16
  title="hello"
  on:click={(e) => {
    console.log(e);
  }} />

<!-- Try typing "<Dele..." -->
<!-- With the VSCode extension, it should autocomplete the "Delete16" import-->
