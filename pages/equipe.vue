<template>
  <TitresH1 class="text-center m-5">L'équipe de choc!</TitresH1>
  <container class="bg-gray-700 h-screen flex items-center justify-center">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Première carte -->
      <div class="bg-gray-400 p-8 rounded shadow-md">
        <img
          src="https://media.ouest-france.fr/v1/pictures/MjAyMzA5MGNiY2ZiOGE5YjM1MzliMmFlNDVlZDkwNDQzYjU3Yjk?width=1260&height=708&focuspoint=50%2C25&cropresize=1&client_id=bpeditorial&sign=f88735fb51f64f674c18f0c6e2350d75a530bf3babcd7aa695a2ce491f10b3b5"
          alt="Photo"
          class="w-full h-45 object-cover mb-4 rounded"
        />
        <div>
          <h1 class="text-2xl font-semibold mb-2">Kimmy</h1>
          <p class="text-gray-700">Conseiller général en bien-être public.</p>
        </div>
      </div>

      <!-- Deuxième carte -->
      <div class="bg-gray-400 p-8 rounded shadow-md">
        <img
          src="https://image.cnbcfm.com/api/v1/image/107335620-17002271162023-11-09t124903z_190410705_rc2m94a7ippu_rtrmadp_0_russia-kazakhstan-putin.jpeg?v=1700729249&w=929&h=523&vtcrop=y"
          alt="Photo"
          class="w-full h-45 object-cover mb-4 rounded"
        />
        <div>
          <h1 class="text-2xl font-semibold mb-2">Vladou</h1>
          <p class="text-gray-700">Responsable de la sécurité publique.</p>
        </div>
      </div>

      <!-- Troisième carte -->
      <div class="bg-gray-400 p-8 rounded shadow-md">
        <img
          src="https://s.rfi.fr/media/display/2c2f70d6-1a71-11ee-a3b4-005056a90284/w:980/p:16x9/2023-07-03T180956Z_495390274_RC2YB1A19PLP_RTRMADP_3_NATO-NORDICS-SWEDEN-ERDOGAN.JPG"
          alt="Photo"
          class="w-full h-32 object-cover mb-4 rounded"
        />
        <div>
          <h1 class="text-2xl font-semibold mb-2">Erdo'</h1>
          <p class="text-gray-700">Auteur d' "être un bon voisin"</p>
        </div>
      </div>
    </div>
  </container>
</template>
