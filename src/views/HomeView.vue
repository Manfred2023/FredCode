<script setup lang="ts">
</script>

<template>
  <!-- Ours Header -->
  <div class="bg-primary  ">
    <div class="max-w-[1280px] mx-auto items-center">
      <!-- Header with logo and WhatsApp link -->
      <div class="flex items-center justify-between text-onSecondary p-5">
        <div class="text-2xl font-bold"><h2>FredCode</h2></div>
        <div class="hidden md:flex items-center justify-between gap-6">
          <h2>Home</h2>
          <h2>Service</h2>
          <h2>Partner</h2>
          <h2>About Us</h2>
        </div>
        <div class="text-green-600 bg-onSecondary p-2 rounded font-bold flex gap-2 cursor-pointer">
          <img src="../assets/icon/whatsapp.svg" alt="Logo" class="w-6 h-6" />
          <a
            href="https://wa.me/237672846994?text=Salut%20FredCode%2C%20j'ai%20besoin%20de%20vos%20prestations"
            target="_blank"
          >
            WhatsApp
          </a>
        </div>
      </div>
      <!-- little presentation for  -->
      <section
        class="grid grid-cols-1 md:grid-cols-2 w-full h-full  items-center text-onSecondary px-5 md:px-10 md:pt-25 pt-5 pb-10"
      >
      <div class="flex items-center justify-center pb-5">
        <div
          class="bg-onSecondary text-onPrimary flex h-60 md:h-100 w-60  rounded-full items-center justify-center overflow-hidden"
        >
          <img
            src="../assets/image/fred_profile.JPG"
            class="h-full w-full object-cover"
            alt="Profile"
          />
        </div>
      </div>
        <div class="flex-col items-center justify-center">
          <p class="text-4xl font-bold px-2 text-center pb-5 md:text-left">
            Hi, Am Manfred MOUKATE, CEO of FredCode Sarl
          </p>
          <p class="text-2xl font-light px-4 pb-4 text-center md:text-left">
            Passionate about technology, I lead FredCode to deliver smart, high-quality software
            that empowers companies to grow and innovate.
          </p>
          <div class="flex justify-center">
            <div
              class="bg-yellowCustom hover:bg-onSecondary  text-onPrimary hover:text-greenCustom   justify-center w-2/3 md:w-1/2 py-3 px-3 rounded font-bold flex cursor-pointer items-center"
            >
              <a class="text-center text-xl">Download Resume</a>
            </div>
          </div>
        </div>
      </section>


    </div>
  </div>
  <!-- Our services -->
  <div class="bg-onSecondary ">
    <div class="max-w-[1280px] mx-auto items-center p-10">
        <div class="flex justify-center">
          <p class="font-bold text-2xl ">Our service</p>
        </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-5 justify-between pt-5 ">
         <div class="border-l-4 border-primary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-primary text-lg">
            💼 Développement de logiciels sur mesure
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Solutions performantes et évolutives adaptées à vos processus métiers.
            <br><span class="font-medium">👉 PME, startups, projets internes.</span>
          </p>

        </div>
         <div class="border-l-4 border-greenCustom rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-greenCustom text-lg">
            📱 Mobile App Development (Applications mobiles)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Développement d’applications Android & iOS natives ou cross-platform (Flutter).
            <br><span class="font-medium">👉 e-commerce, livraison, fintech, gestion, apps personnalisées.</span>
          </p>

        </div>
         <div class="border-l-4 border-onPrimary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-onPrimary text-lg">
            🌐 Web App & SaaS Solutions (Applications web & plateformes SaaS)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Conception de plateformes en ligne performantes : dashboards, CRM, ERP, outils internes
            <br><span class="font-medium">👉 productivité, gestion, automatisation.</span>
          </p>

        </div>
         <div class="border-l-4 border-greenCustom rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-greenCustom text-lg">
            ☁️ Hosting & Deployment (Hébergement & DevOps)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Assistance continue, corrections, mise à jour, amélioration de performance.
            <br><span class="font-medium">👉 fiabilité + rapidité d’intervention.</span>
          </p>

        </div>
         <div class="border-l-4 border-onPrimary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-onPrimary text-lg">
            🔒 API Development & Integration (API & intégrations)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Création d’API sécurisées et intégration avec des services tiers (paiements, SMS, IA, Cloud…)
            <br><span class="font-medium">👉 Mobile Money, gateways bancaires, services externes.</span>
          </p>

        </div>
         <div class="border-l-4 border-primary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition">
          <h2 class="font-semibold text-primary text-lg">
            ☁️ Hosting & Deployment (Hébergement & DevOps)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Assistance continue, corrections, mise à jour, amélioration de performance.
            <br><span class="font-medium">👉 fiabilité + rapidité d’intervention.</span>
          </p>

        </div>


      </div>
    </div>
  </div>
  <!-- Our project -->
  <div class="bg-gray-300 ">
    <div class="max-w-[1280px] mx-auto items-center p-10">
      <div class="flex justify-center">
        <p class="font-bold text-2xl ">Our Project</p>
      </div>

    </div>
  </div>

</template>
