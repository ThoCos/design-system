<template>
  <Container>
    <TitresH1 class="text-center"> DemocracyHub </TitresH1>

    <TextesParagraphe class="pb-5">
      Pellentesque vulputate volutpat nisl sed hendrerit. Fusce volutpat pretium
      est, vel lacinia erat. Vestibulum tempus hendrerit elit quis imperdiet. Ut
      non tortor ut lorem ultrices tincidunt sit amet sed urna. Pellentesque a
      lacinia urna. Integer accumsan, mi non tempus semper, diam orci
      condimentum magna, non faucibus dolor tellus non elit. Maecenas rhoncus
      arcu in vulputate facilisis. Sed ac finibus ligula. Morbi tempor orci eget
      luctus consequat. Aenean id mauris ex. Pellentesque hendrerit augue
      luctus, pulvinar leo facilisis, sollicitudin nisl. Praesent vitae sapien
      quis tortor egestas auctor placerat eget nisl. Proin pretium felis vitae
      ligula accumsan feugiat. Etiam aliquam aliquam dui a rhoncus. Pellentesque
      eleifend ipsum laoreet felis fermentum pretium.
    </TextesParagraphe>
    <TextesParagraphe
      >Aenean semper lectus id magna aliquet congue. Donec imperdiet vehicula
      porttitor. Phasellus maximus diam id eleifend blandit. Mauris a nulla
      nisl. Etiam blandit, libero quis rutrum dictum, magna elit sagittis
      lectus, nec dapibus ipsum orci vel ante. Praesent mattis justo quis tortor
      venenatis, non blandit purus consequat. Nam fermentum dui vitae tellus
      fringilla, ut imperdiet sem sodales. In hac habitasse platea dictumst.
      Suspendisse id ligula aliquet, efficitur libero eget, molestie diam.
      Vivamus magna ante, blandit egestas magna vel, volutpat suscipit mauris.
      Ut turpis purus, consectetur vestibulum consequat sit amet, dignissim sed
      leo. Aliquam accumsan nisl eu interdum convallis.</TextesParagraphe
    >

    <TitresH2 class="text-center"> Services </TitresH2>
    <div class="flex justify-center">
      <ListsGrid>
        <li>
          <CardsIconCard to="/docs/composants">
            <template #icon>
              <i
                class="ri-list-indefinite text-green-500 group-hover:text-green-700"
              ></i>
            </template>
            StrategicConnect
          </CardsIconCard>
        </li>

        <li>
          <CardsIconCard to="/docs/layouts">
            <template #icon>
              <i
                class="ri-layout-line text-blue-500 group-hover:text-blue-700"
              ></i>
            </template>
            InnovationForge
          </CardsIconCard>
        </li>

        <li>
          <CardsIconCard to="/docs/icones">
            <template #icon>
              <i
                class="ri-heart-line text-red-500 group-hover:text-red-700"
              ></i>
            </template>
            DataCatalyst
          </CardsIconCard>
        </li>

        <li>
          <CardsIconCard to="/docs/icones">
            <template #icon>
              <i class="ri-knife-line text-yellow-200"></i>
            </template>
            WorkingCamp
          </CardsIconCard>
        </li>
      </ListsGrid>
    </div>
  </Container>
</template>
