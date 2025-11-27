<script setup lang="ts">
</script>

<template>
  <!-- Ours Header -->
  <div class="bg-primary">
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
        <div
          class="text-green-600 hover:text-onPrimary hover:bg-yellowCustom bg-onSecondary p-2 rounded font-bold flex gap-2 cursor-pointer"
        >
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
        class="grid grid-cols-1 md:grid-cols-2 w-full h-full items-center text-onSecondary px-5 md:px-10 md:pt-25 pt-5 pb-10"
      >
        <div class="flex items-center justify-center pb-5">
          <div
            class="bg-onSecondary text-onPrimary flex h-60 md:h-100 w-60 rounded-full items-center justify-center overflow-hidden"
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
              class="bg-yellowCustom hover:bg-onSecondary text-onPrimary hover:text-greenCustom justify-center w-2/3 md:w-1/2 py-3 px-3 rounded font-bold flex cursor-pointer items-center"
            >
              <a class="text-center text-xl">Download Resume</a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
  <!-- Our services -->
  <div class="bg-onSecondary">
    <div class="max-w-[1280px] mx-auto items-center p-10">
      <div class="flex justify-center">
        <p class="font-bold text-2xl">Our services</p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-5 justify-between pt-5">
        <div
          class="border-l-4 border-primary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-primary text-lg">
            💼 Développement de logiciels sur mesure
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Solutions performantes et évolutives adaptées à vos processus métiers.
            <br /><span class="font-medium">👉 PME, startups, projets internes.</span>
          </p>
        </div>
        <div
          class="border-l-4 border-greenCustom rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-greenCustom text-lg">
            📱 Mobile App Development (Applications mobiles)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Développement d’applications Android & iOS natives ou cross-platform (Flutter).
            <br /><span class="font-medium"
              >👉 e-commerce, livraison, fintech, gestion, apps personnalisées.</span
            >
          </p>
        </div>
        <div
          class="border-l-4 border-onPrimary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-onPrimary text-lg">
            🌐 Web App & SaaS Solutions (Applications web & plateformes SaaS)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Conception de plateformes en ligne performantes : dashboards, CRM, ERP, outils internes
            <br /><span class="font-medium">👉 productivité, gestion, automatisation.</span>
          </p>
        </div>
        <div
          class="border-l-4 border-greenCustom rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-greenCustom text-lg">
            ☁️ Hosting & Deployment (Hébergement & DevOps)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Assistance continue, corrections, mise à jour, amélioration de performance.
            <br /><span class="font-medium">👉 fiabilité + rapidité d’intervention.</span>
          </p>
        </div>
        <div
          class="border-l-4 border-onPrimary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-onPrimary text-lg">
            🔒 API Development & Integration (API & intégrations)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Création d’API sécurisées et intégration avec des services tiers (paiements, SMS, IA,
            Cloud…)
            <br /><span class="font-medium"
              >👉 Mobile Money, gateways bancaires, services externes.</span
            >
          </p>
        </div>
        <div
          class="border-l-4 border-primary rounded-md bg-gray-50 p-4 hover:bg-gray-100 transition"
        >
          <h2 class="font-semibold text-primary text-lg">
            ☁️ Hosting & Deployment (Hébergement & DevOps)
          </h2>
          <p class="text-gray-700 text-sm mt-2">
            Assistance continue, corrections, mise à jour, amélioration de performance.
            <br /><span class="font-medium">👉 fiabilité + rapidité d’intervention.</span>
          </p>
        </div>
      </div>
    </div>
  </div>
  <!-- Our project -->
  <div class="bg-gray-300">
    <div class="max-w-[1280px] mx-auto items-center p-10">
      <div class="flex justify-center">
        <p class="font-bold text-2xl">Our Projects</p>
      </div>
    </div>
  </div>
  <!-- footer -->
  <div class="bg-onPrimary">
    <div class="max-w-[1280px] mx-auto items-center p-10">
      <div class="grid grid-cols-1 md:grid-cols-3">
        <div class="flex flex-col">
          <h1 class="text-2xl font-bold text-onSecondary">FredCode</h1>
          <p class="text-sm mt-2 text-onSecondary">
            Éditeur de logiciels spécialisé en développement mobile, web, API, IA et solutions
            d'entreprise.
          </p>
          <div class="pt-5 w-full md:w-2/3 justify-center">
            <div
              class="text-green-600 hover:text-onPrimary hover:bg-yellowCustom bg-onSecondary p-2 rounded font-bold flex gap-2 cursor-pointer"
            >
              <img src="../assets/icon/whatsapp.svg" alt="Logo" class="w-6 h-6" />
              <a
                href="https://wa.me/237672846994?text=Salut%20FredCode%2C%20j'ai%20besoin%20de%20vos%20prestations"
                target="_blank"
              >
                WhatsApp
              </a>
            </div>
          </div>
          <div class="pt-5 flex gap-5">
            <a href="https://github.com/Manfred2023" target="_blank">
              <img src="../assets/icon/github.svg" alt="Logo" class="w-6 h-6 cursor-pointer" />
            </a>
            <a href="https://www.linkedin.com/in/manfred-moukate-709192396" target="_blank">
              <img src="../assets/icon/linkedin.svg" alt="Logo" class="w-6 h-6 cursor-pointer" />
            </a>
            <a href="https://web.facebook.com/profile.php?id=61569676726582" target="_blank">
              <img src="../assets/icon/facebook.svg" alt="Logo" class="w-6 h-6 cursor-pointer" />
            </a>
          </div>
        </div>
        <div class="flex flex-col pt-5 md:pt-0">
          <h1 class="text-2xl font-bold text-onSecondary">Contact</h1>
          <div class="flex gap-2 cursor-pointer pt-2">
            <img src="../assets/icon/phone.svg" alt="Logo" class="w-6 h-6" />
            <p class="text-onSecondary">+237 699-888-709 / 672-846-994</p>
          </div>
          <div class="flex gap-2 cursor-pointer pt-2">
            <img src="../assets/icon/email.svg" alt="Logo" class="w-6 h-6" />
            <p class="text-onSecondary">contact@fredcode.net</p>
          </div>
          <div class="flex gap-2 cursor-pointer pt-2">
            <img src="../assets/icon/location.svg" alt="Logo" class="w-6 h-6" />
            <p class="text-onSecondary">Douala, Cameroon</p>
          </div>
          <div class="flex gap-2 cursor-pointer pt-2">
            <img src="../assets/icon/website.svg" alt="Logo" class="w-6 h-6" />
            <p class="text-onSecondary">fredcode.net</p>
          </div>
        </div>
        <div class="flex flex-col pt-5 md:pt-0">
          <h1 class="text-2xl font-bold text-onSecondary">Demander un devis</h1>
          <div class="pt-2 gap-2 grid">
           <div class="grid grid-cols-1 md:grid-cols-2 gap-3 cursor-pointer pt-2">
             <input class="border border-onSecondary p-2 rounded text-onSecondary" placeholder="First name">
             <input class="border border-onSecondary p-2 rounded text-onSecondary" placeholder="Last name">
           </div>
           <div class="grid grid-cols-1">
            <input class="border border-onSecondary p-2 rounded text-onSecondary" placeholder="Email address" type="email">
           </div>
            <div class="grid ">
              <textarea
                class="border border-onSecondary p-2 rounded text-onSecondary"
                placeholder="Describe your idea"
                rows="4"
              ></textarea>

            </div>
          </div>
          <div class="pt-5 w-full  justify-center">
            <div
              class="text-green-600 hover:text-onPrimary hover:bg-yellowCustom bg-onSecondary p-2 rounded font-bold flex justify-center gap-2 cursor-pointer"
            >
              <a
                href="https://wa.me/237672846994?text=Salut%20FredCode%2C%20j'ai%20besoin%20de%20vos%20prestations"
                target="_blank"
              >
                Soumettre
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- copyWrite -->
  <div class="bg-yellowCustom">
    <div  class="max-w-[1280px] mx-auto items-center p-2">
      <div class="flex flex-col md:flex-row items-center justify-center md:justify-between">
        <p>2025 FredCode. Tous droits réservés.</p>
        <p>
          Développé et hébergé par.<span class="font-bold cursor-pointer">
                  FredCode Sarl</span
        >
        </p>
      </div>
    </div>
  </div>
</template>
