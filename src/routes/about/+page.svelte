<script>
  import aboutImage from "../../lib/images/AboutImage.svg";
</script>

<div class="text-center flex justify-center">
  <p
    class="homeHeading font-semibold font-Montserrat w-fit xl:text-7xl lg:text-6xl md:text-5xl sm:text-5xl xs:text-4xl xxs:text-3xl"
  >
    ABOUT <span class="text-[#6F42C1]">PRIME</span> TECHNOLOGY
  </p>
</div>
<div class="flex aboutContainer">
  <div class="w-1/2 p-16 flex flex-col align-center justify-center aboutText">
    <!-- <h1 class="font-bold text-2xl mb-2">About Prime Technology:</h1> -->
    <p>
      Prime Technology delivers expert solutions in accounts management, ISP
      services, and software development. With meticulous attention to detail,
      we optimize financial processes, ensure seamless connectivity, and develop
      bespoke software tailored to your needs. Trust Prime Technology for
      unparalleled expertise and professionalism in every aspect of IT service
      provision.
    </p>

    <h1 class="font-bold text-2xl mt-5 mb-2">Our Approach</h1>
    <p>
      At Prime Technology, we epitomize precision, innovation, and
      client-centricity. We prioritize understanding your unique needs to craft
      tailored solutions in accounts management, ISP services, and software
      development. Through collaborative partnerships and cutting-edge
      technology, we ensure unparalleled efficiency, reliability, and
      satisfaction in every project we undertake.
    </p>

    <h1 class="font-bold text-2xl mt-5 mb-2">Our Team</h1>
    <p>
      Our Team reflects a synergy of expertise and dedication. Comprising
      skilled professionals across accounts management, ISP services, and
      software development, our team is committed to delivering excellence.
      Through seamless collaboration and continual refinement, we ensure
      innovative solutions that exceed client expectations, driving success and
      growth.
    </p>
  </div>
  <div class="w-1/2 flex justify-center aboutImage">
    <img src={aboutImage} alt="aboutImage" class=" p-10" />
  </div>
</div>

<style>
  @media only screen and (max-width: 639px) {
    .aboutContainer {
      flex-direction: column;
    }

    .aboutText {
      width: 100%;
      text-align: center;
    }

    .aboutImage {
      width: 100%;
    }
  }

  @media only screen and (max-width: 999px) {
    .aboutContainer {
      flex-direction: column;
    }

    .aboutText {
      width: 100%;
      text-align: center;
    }

    .aboutImage {
      width: 100%;
    }
  }
</style>
