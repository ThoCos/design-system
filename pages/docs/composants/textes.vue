<script setup>
definePageMeta({
  layout: "docs",
});

const consoleLog = `console.log('hello')`;
const code = `<TextesCode code="${consoleLog}" language="js" />`;
</script>

<template>
  <Container>
    <TitresH1>Textes</TitresH1>
    <!-- ======================================= -->

    <TitresH2>Gras</TitresH2>
    <TextesGras>Texte en gras</TextesGras>
    <TextesCode code="<TextesGras> Texte à mettre en gras </TextesGras>" />
    <!-- ======================================= -->

    <TitresH2>Italique</TitresH2>
    <TextesItalique>Texte en Italique</TextesItalique>
    <TextesCode
      code="<TextesItalique> Texte à mettre en italique </TextesItalique>"
    />
    <!-- ======================================= -->

    <TitresH2>Souligné</TitresH2>
    <TextesSouligne>Texte en gras</TextesSouligne>
    <TextesCode code="<TextesSouligne> Texte à souligner </TextesSouligne>" />
    <!-- ======================================= -->

    <TitresH2>Paragraphe</TitresH2>

    <TextesParagraphe>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
      voluptatum, quibusdam, voluptates quia quae voluptatem, quos quod quas
      voluptatibus quidem doloribus. Quisquam voluptatum, quibusdam, voluptates
      quia quae voluptatem, quos quod quas voluptatibus quidem doloribus.
    </TextesParagraphe>
    <TextesCode
      :code="`<TextesParagraphe>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam voluptatum, quibusdam, voluptates quia quae voluptatem, quos quod quas voluptatibus quidem doloribus. Quisquam voluptatum, quibusdam, voluptates quia quae voluptatem, quos quod quas voluptatibus quidem doloribus.
</TextesParagraphe>`"
    />

    <TitresH2>Code</TitresH2>

    <TextesParagraphe> Language par défaut : vue </TextesParagraphe>

    <TextesCode :code="consoleLog" language="js" />

    <TextesCode :code="code" />
  </Container>
</template>
