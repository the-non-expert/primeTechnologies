<script>
  let navOptions = [
    { id: 1, name: "Home", redirectUrl: "/" },
    { id: 2, name: "About Us", redirectUrl: "/about" },
    { id: 3, name: "What We Do", redirectUrl: "/services" },
    { id: 4, name: "Testimonials", redirectUrl: "/testimonials" },
    { id: 5, name: "Contact Us", redirectUrl: "/contact" },
  ];
</script>

<div class="flex justify-around mt-10">
  <img src="" alt="PRIME TECHNOLOGIES" class="flex h-36" />

  <header class="flex gap-12 justify-center">
    {#each navOptions as item (item.id)}
      <a href={item.redirectUrl}>
        <p class="text-lg font-Montserrat">{item.name}</p></a
      >
    {/each}
  </header>
</div>
