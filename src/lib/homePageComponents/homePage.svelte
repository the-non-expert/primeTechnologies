<script>
  import Pattern from "../images/legoPattern.jpeg";
  import sample from "../images/homeImage2.jpeg";

  import azure from "../images/azureLogo.svg";
  import cisco from "../images/ciscoLogo.svg";
  import docker from "../images/dockerLogo.svg";
  import slack from "../images/slackLogo.svg";
  import dell from "../images/dellLogo.svg";
  import clients from "../images/testimonialImage.jpeg";
</script>

<div class="flex justify-center gap-24 mt-10 responsive">
  <div class="mb-4">
    <p class="wCustom font-lato">
      Making the right IT choices can be difficult. That's wherewe come in.
      Prime Technologies has the expertise and skill-set necessary to help you
      make IT choices that are practical, efficient & reliable when it matters
      the most.
    </p>

    <button class="mt-4 font-bold px-5 py-2 rounded bg-[#6F42C2] text-white"
      >SEE OUR PROJECTS</button
    >
  </div>

  <div class="w-96 h-48">
    <img src={Pattern} alt="homePattern" class="object-cover w-full h-full" />
  </div>
</div>

<div class="flex justify-center gap-24 mt-24 responsive">
  <div>
    <p class="text-3xl font-semibold">
      GET THE RESULTS YOU'VE <br /> BEEN LOOKING FOR
    </p>
  </div>
  <div>
    <p class="wCustom mt-10">
      Prime Technologies make IT infrastructure work smarter for your business
      and the people who rely on it.
    </p>
    <a href="/about"
      ><button class="mt-4 font-bold px-5 py-2 rounded bg-[#6F42C2] text-white"
        >MORE ABOUT US</button
      ></a
    >
  </div>
</div>

<!-- We can help with -->

<div class="mt-12">
  <p
    class="homeHeading font-semibold font-Montserrat w-fit xl:text-4xl lg:text-4xl md:text-3xl sm:text-2xl xs:text-xl mx-auto"
  >
    WE CAN <span class="text-[#6F42C1]">HELP</span> WITH
  </p>
  <div class="flex gap-10 justify-center mt-8">
    <p class="px-4 py-2 bg-slate-200 rounded-xl shadow-md">
      Internet Service Provider
    </p>
    <p class="px-4 py-2 bg-slate-200 rounded-xl shadow-md">
      Accounts Management
    </p>
    <p class="px-4 py-2 bg-slate-200 rounded-xl shadow-md">
      Application and Software
    </p>
    <p class="px-4 py-2 bg-slate-200 rounded-xl shadow-md">Cloud Migration</p>
  </div>
</div>

<!-- home image-->

<div class="mt-24 h-64">
  <img
    src={sample}
    alt="Passion"
    class="w-10/12 mx-auto h-full object-cover rounded-tl-2xl rounded-br-2xl"
  />
</div>

<!-- trusted companies -->

<div class="mt-20">
  <p
    class="homeHeading font-Montserrat w-fit xl:text-4xl lg:text-4xl md:text-3xl sm:text-2xl xs:text-xl mx-auto font-semibold"
  >
    TRUSTED BY <span class="text-[#6F42C1]">TOP</span> COMPANIES
  </p>

  <div class="flex gap-36 justify-center mt-8">
    <img src={azure} alt="azurelogo" class="w-36" />
    <img src={cisco} alt="azurelogo" class="w-24" />
    <img src={docker} alt="azurelogo" class="w-24" />
    <img src={slack} alt="azurelogo" class="w-24" />
    <img src={dell} alt="azurelogo" class="w-24" />
  </div>
</div>

<!-- testimonial section -->

<div class="mt-20 mb-20 flex justify-center gap-20">
  <img src={clients} alt="clients" class="w-4/12 h-full" />
  <div class="w-4/12">
    <p class="text-2xl font-semibold">
      WHAT OUR <span class="text-[#6F42C1]">CLIENTS</span><br /> HAVE TO SAY
    </p>
    <p class="mt-5">
      "Their team is incredibly responsive and proactive in identifying and
      resolving issues before they impact our operations. We've experienced a
      significant improvement in uptime, security, and overall IT performance.
      Most importantly, Prime Technologies has become a trusted partner,
      allowing us to focus on what we do best - running our business."
    </p>
    <a href="/testimonials"
      ><button class="mt-4 font-bold px-5 py-2 rounded bg-[#6F42C2] text-white"
        >View Testimonials</button
      ></a
    >
  </div>
</div>

<style>
  .wCustom {
    max-width: 25vw;
  }

  @media only screen and (max-width: 639px) {
    .flex {
      display: block; /* Change to block layout for smaller screens */
      justify-content: center; /* Maintain centering */
      gap: 0; /* Remove gap for smaller screens */
      margin: 0 auto; /* Center the entire component */
    }

    .wCustom {
      max-width: 100vw;
      text-align: center;
      padding: 20px;
    }

    .responsive {
      text-align: center;
    }

    .homeHeading {
      font-size: 1.5rem; /* Adjust font size for extra small screens */
    }
  }
</style>
