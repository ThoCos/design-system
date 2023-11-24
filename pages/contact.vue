<template>
  <container class="bg-gray-700 h-screen flex items-center justify-center">
    <div class="bg-gray-500 p-8 rounded-lg shadow-2xl max-w-md w-full">
      <h1 class="text-2xl text-gray-50 text-center font-semibold mb-6">
        Contactez nous!
      </h1>

      <form action="#" method="POST">
        <div class="mb-4">
          <label
            for="nom_prenom"
            class="block text-gray-50 text-sm font-bold mb-2"
            >Nom & Prénom</label
          >
          <input
            type="text"
            id="nom_prenom"
            name="nom_prenom"
            class="bg-gray-300 w-full p-2 border border-gray-300 rounded"
          />
        </div>

        <div class="mb-4">
          <label for="email" class="block text-gray-50 text-sm font-bold mb-2"
            >Adresse Email</label
          >
          <input
            type="email"
            id="email"
            name="email"
            class="bg-gray-300 w-full p-2 border border-gray-300 rounded"
          />
        </div>

        <div class="mb-4">
          <label for="message" class="block text-gray-50 text-sm font-bold mb-2"
            >Message</label
          >
          <textarea
            id="message"
            name="message"
            rows="4"
            class="bg-gray-300 w-full p-2 border border-gray-300 rounded"
          ></textarea>
        </div>

        <button type="submit" class="bg-blue-500 text-white p-2 rounded">
          Envoyer
        </button>
      </form>
    </div>
  </container>
  <div class="flex-wrap text-center justify-center pb-5">
    <h1 class="text-2xl text-gray-50 text-center font-semibold mb-6">
      Rejoignez-nous!
    </h1>
    <TextesParagraphe> Liberty Avenue, 6</TextesParagraphe>
    <TextesParagraphe> 6 685 Pyongyang</TextesParagraphe>
    <TextesParagraphe> The Coolest Korea</TextesParagraphe>
  </div>
  <div class="flex justify-center mb-10 rounded-lg">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d49585.719129328565!2d125.75342600696946!3d39.03566957039199!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sfr!2sbe!4v1700821549876!5m2!1sfr!2sbe"
      width="600"
      height="450"
      style="border: 0"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
  </div>
</template>
