<script>
  import HomePage from "../lib/homePageComponents/homePage.svelte";
</script>

<div class="">
  <div class="text-center flex justify-center">
    <p
      class="homeHeading font-semibold font-Montserrat w-fit xl:text-7xl lg:text-6xl md:text-5xl sm:text-5xl xs:text-4xl xxs:text-3xl"
    >
      AN <span class="text-[#6F42C1]">IT SERVICES</span> EXPERIENCE <br /> LIKE NO
      OTHER
    </p>
  </div>

  <HomePage />
</div>

<style>
  @media (max-width: 639px) {
    .homeHeading {
      font-size: 2rem; /* Adjust font size for extra small screens */
    }
  }
</style>
