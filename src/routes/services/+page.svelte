<script>
  import Isp from "../../lib/images/ISP.svg";
  import Am from "../../lib/images/AccountManagement.svg";
</script>

<div class="text-center flex justify-center">
  <p
    class="homeHeading font-semibold font-Montserrat w-fit xl:text-7xl lg:text-6xl md:text-5xl sm:text-5xl xs:text-4xl xxs:text-3xl"
  >
    OUR <span class="text-[#6F42C1]">SERVICES</span>
  </p>
</div>

<div class="flex justify-center gap-24 mt-4 mb-4 responsive">
  <p class="wCustom font-Montserrat text-center">
    We deliver a wide array of essential services including software
    development, network infrastructure setup, cybersecurity measures, cloud
    computing solutions, data analytics, IT consulting for strategic planning,
    and comprehensive tech support. These services ensure efficient operations,
    robust security, and optimized technology utilization for businesses of all
    scales.
  </p>
</div>

<div class="flex gap-3 p-10 servicesResponse">
  <div class="w-[500px] border-2 border-black p-4 rounded-xl">
    <div class="">
      <h1 class="font-bold text-center">Account Management</h1>
      <!-- <img src={Am} alt="Am" class="w-16" /> -->
    </div>

    <div class="border-t border-black my-2" />

    <p class="text-xs mt-4">Sercives Included:</p>
    <div class="text-sm">
      <p>Comprehensive management of financial software.</p>
      <p>Expertise in various accounting software platforms.</p>
      <p>Seamless transition and update of company-year for fiscal records.</p>
      <p>
        Tailored services including installation, configuration, and
        troubleshooting.
      </p>
    </div>
    <div class="border-t border-black my-2" />

    <div class="flex">
      <p class="">Get your accounts sorted. Request a quotation today!</p>
      <button class="font-bold py-1 px-5 rounded bg-[#6F42C2] text-white"
        >Contact us</button
      >
    </div>
  </div>

  <div class="w-[500px] border-2 border-black p-4 rounded-xl">
    <div class="">
      <h1 class="font-bold text-center">Internet Service Provider</h1>
      <!-- <img src={Isp} alt="isp" class="w-24" /> -->
    </div>

    <div class="border-t border-black my-2" />

    <p class="text-xs mt-4">Services Included:</p>
    <div class="text-sm">
      <p>Network infrastructure seamless connectivity.</p>
      <p>Dedicated customer support for technical assistance.</p>
      <p>
        High-speed internet access tailored to residential and commercial needs.
      </p>
      <p>Packages offering options for various data speeds and usage.</p>
    </div>
    <div class="border-t border-black my-2" />

    <div class="flex">
      <p class="">
        Get the fastest Internet in Cuttack. Request a quotation today!
      </p>
      <button class="font-bold py-1 px-5 rounded bg-[#6F42C2] text-white"
        >Contact us</button
      >
    </div>
  </div>

  <div class="w-[500px] border-2 border-black p-4 rounded-xl">
    <h1 class="font-bold text-center">Application & Software</h1>

    <div class="border-t border-black my-2" />

    <p class="text-xs mt-4">Sercives Included:</p>
    <div class="text-sm">
      <p>Custom development tailored to specific requirements.</p>
      <p>Consultation for software utilization and optimization.</p>
      <p>
        Integration services to ensure seamless communication between different
        applications.
      </p>
      <p>
        Software maintenance and updates to keep systems running smoothly and
        securely.
      </p>
    </div>
    <div class="border-t border-black my-2" />

    <div class="flex">
      <p class="">
        If you can think it, we can make it. Request a quotation today!
      </p>
      <button class="font-bold py-1 px-5 rounded bg-[#6F42C2] text-white"
        >Contact us</button
      >
    </div>
  </div>
</div>

<style>
  .wCustom {
    max-width: 65vw;
  }

  @media only screen and (max-width: 639px) {
    .wCustom {
      max-width: 100vw;
      text-align: center;
      padding: 20px;
    }

    .servicesResponse {
      flex-direction: column;
    }
  }
</style>
