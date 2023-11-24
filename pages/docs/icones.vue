<script setup>
definePageMeta({
  layout: "docs",
});
</script>

<template>
  <Container>
    <TitresH1> Icones </TitresH1>

    <TextesParagraphe>
      Vous pouvez utilisez les icones de Remix Icon dans vos projets.

      <LinksExternal to="https://remixicon.com/"
        >https://remixicon.com/</LinksExternal
      >
    </TextesParagraphe>

    <TitresH2>Exemples</TitresH2>

    <i class="ri-heart-line text-6xl text-red-500"></i>
    <i class="ri-chat-3-line text-6xl text-blue-400"></i>
    <i class="ri-vip-diamond-line text-6xl text-purple-600"></i>
    <i class="ri-sun-line text-6xl text-yellow-500"></i>

    <TextesCode
      :code="`<i class=&quot;ri-heart-line text-6xl text-red-500&quot;></i>`"
    />
  </Container>
</template>
