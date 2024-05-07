<script>
  // import icon from "$lib/images/addyFitnessIcon.png";
  // import logo from "$lib/images/addyFitnessLogo.png";
  // import caption from "$lib/images/addyFitnessCaption.png";
  import phone from "$lib/images/phoneIcon.svg";
  import email from "$lib/images/emailIcon.svg";

  import instagramIcon from "$lib/images/Instasvg.svg";
  import whatsappIcon from "$lib/images/whatsappSvg.svg";
  import linkedInIcon from "$lib/images/linkedin.svg";
  import youtubeIcon from "$lib/images/youtubeIcon.svg";

  let socialMediaDetails = [
    {
      id: 1,
      name: "Instagram",
      iconUrl: instagramIcon,
      redirectLink: "",
    },
    {
      id: 2,
      name: "Whatsapp",
      iconUrl: whatsappIcon,
      redirectLink: "",
    },
    {
      id: 3,
      name: "LinkedIn",
      iconUrl: linkedInIcon,
      redirectLink: "",
    },
    // {
    //   id: 4,
    //   name: "Youtube",
    //   iconUrl: youtubeIcon,
    //   redirectLink: "",
    // },
  ];
</script>

<div class="w-[98%] text-black py-6 rounded-t-3xl mx-auto">
  <div class="flex justify-evenly footerContainer">
    <div class="flex">
      <img src="" alt="PRIME TECHNOLOGIES" class="flex h-16" />
    </div>

    <div class="flex gap-10 footerOptions">
      <p class="font-semibold">About</p>
      <p class="font-semibold">Services</p>
      <p class="font-semibold">Contact Us</p>
      <p class="font-semibold">Feedback</p>
      <p class="font-semibold">Management</p>
    </div>

    <div class="flex gap-4">
      {#each socialMediaDetails as item (item.id)}
        <!-- svelte-ignore missing-declaration -->
        <a href={item.redirectLink}>
          <img src={item.iconUrl} alt="" class="w-6" />
        </a>
      {/each}
    </div>
  </div>

  <div class="flex justify-evenly items-center copyrightContainer">
    <div class="flex gap-4">
      <p class="">© 2024 Prime Technology Inc.</p>
      <p class="">Terms</p>
      <p>Privacy</p>
    </div>

    <div class="flex gap-5 text-black">
      <div class="flex items-center gap-2">
        <img src={phone} alt="phoneIcon" class="w-4" />
        <p class=" font-[lato]">+91 9338017665</p>
      </div>
      <div class="flex items-center gap-2">
        <img src={email} alt="phoneIcon" class="w-4" />
        <p class=" font-[lato]">sampleEmail@gmail.com</p>
      </div>
    </div>
  </div>
</div>

<style>
  @media only screen and (max-width: 639px) {
    .footerContainer {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .footerOptions {
      width: 80%;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      margin-bottom: 15px;
    }

    .copyrightContainer {
      flex-direction: column-reverse;
      margin-top: 50px;
    }
  }
  @media only screen and (max-width: 999px) {
    .footerContainer {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .footerOptions {
      /* gap: 55px; */
      margin-bottom: 15px;
    }

    .copyrightContainer {
      flex-direction: column-reverse;
      margin-top: 50px;
    }
  }
</style>
