<script lang="ts">
  import { writable } from "svelte/store";
  export let a: number = 5;
  export let b: string = "foo";
  const foo = writable<string>("foo");
</script>

{a} : {b}
