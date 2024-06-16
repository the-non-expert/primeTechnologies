<script>
  import AlphabetList from "alphabet-list-svelte";

  let sampleItems = [
    { name: "Apple" },
    { name: "Apricot" },
    { name: "Avocado" },
    { name: "Banana" },
  ];
</script>

<AlphabetList {sampleItems} />
