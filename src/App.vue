<template>
  <div class="snap-y snap-proximity mx-auto container bg-gray-100 h-screen overflow-y-scroll">
    <section
      v-for="i in 10"
      :key="`scroll_section_${i}`"
      class="relative flex flex-row h-full snap-start py-4 bg-gray-200 mt-4 p-4"
    >
      <div class="image-wrapper flex-1 h-min sticky top-0">
        <img src="https://place-hold.it/500" />
      </div>
      <div class="text-wrapper flex-1 overflow-y-scroll">
        <div v-for="j in 5" :key="`text_content_${j}`">
          <p>
            Jelly-o gummi bears wafer. Oat cake cupcake bonbon toffee. Jelly tiramisu gummi bears jelly beans dragée
            dragée cupcake fruitcake. Jelly beans pastry toffee halvah caramels. Jujubes chocolate cake croissant powder
            marshmallow lemon drops jujubes gingerbread gingerbread. Gummi bears macaroon ice cream jujubes gingerbread
            sesame snaps sweet tootsie roll. Toffee candy donut chupa chups sugar plum liquorice muffin tiramisu.
            Jujubes icing croissant sweet gummi bears jelly beans gummies liquorice. Sweet roll fruitcake candy gummies
            marshmallow. Sweet roll topping pastry oat cake chocolate cake. Oat cake jelly beans marshmallow jelly-o.
            Bear claw chocolate carrot cake chocolate cake marzipan pastry chocolate danish gummies. Sweet roll topping
            marshmallow.
          </p>

          <p>
            Wafer icing cotton candy oat cake. Toffee muffin jelly jelly beans toffee. Tart topping tiramisu tiramisu
            jelly. Danish chocolate chupa chups ice cream tootsie roll topping chocolate. Sesame snaps jelly topping
            tiramisu gummi bears. Cheesecake marzipan bonbon lemon drops. Wafer macaroon donut macaroon pudding pudding
            cupcake. Pie candy icing pastry fruitcake biscuit jelly beans chupa chups jelly. Powder cookie liquorice
            danish chocolate. Soufflé lemon drops jelly beans tart wafer. Bear claw tiramisu muffin jelly-o donut cake.
            Cupcake macaroon pudding halvah pudding tootsie roll cupcake. Cake cake jelly tart biscuit biscuit wafer
            icing. Macaroon cupcake cake cupcake tart brownie.
          </p>

          <p>
            Cupcake brownie halvah gingerbread gingerbread brownie danish muffin. Caramels gummi bears pie. Sugar plum
            sweet roll chocolate gingerbread jelly halvah muffin. Marzipan macaroon bonbon gummies cake gummies lemon
            drops. Soufflé bonbon cake. Sweet roll marzipan cake tootsie roll sweet. Sweet tart marzipan candy carrot
            cake topping. Pudding pudding gummies bonbon icing chupa chups. Icing jelly-o dragée. Cupcake soufflé
            cheesecake jelly beans. Sesame snaps gummi bears bonbon pie tiramisu. Cupcake carrot cake danish. Biscuit
            gummi bears croissant jujubes.
          </p>

          <p>
            Cheesecake cotton candy topping cheesecake icing. Ice cream biscuit marshmallow cake cake. Soufflé jelly-o
            apple pie tootsie roll. Pudding jelly-o sugar plum gummies powder. Gummi bears cookie candy lemon drops
            chocolate cake lollipop gummies donut. Chocolate bar cookie lemon drops donut. Macaroon marshmallow sweet
            roll chupa chups jelly-o candy canes jelly donut. Marshmallow carrot cake lollipop. Icing ice cream pie
            marshmallow gummi bears powder sugar plum sweet roll gummies. Wafer jujubes tart jelly. Gummies halvah
            powder ice cream cupcake toffee biscuit jelly-o sweet. Marzipan gingerbread gummi bears biscuit. Bear claw
            topping apple pie. Carrot cake chupa chups caramels carrot cake cheesecake.
          </p>

          <p>
            Apple pie pudding danish halvah. Soufflé toffee pastry. Gummies caramels sweet gingerbread. Toffee fruitcake
            halvah. Tart jelly sugar plum chocolate bar croissant cheesecake cake. Tart cookie dragée chocolate bar
            tiramisu cookie gummies gummi bears jelly-o. Carrot cake cookie pastry chupa chups jelly-o chocolate bar.
            Oat cake chocolate bar sweet roll chocolate bar chocolate cake bonbon sweet roll tootsie roll. Carrot cake
            halvah sugar plum gingerbread jelly beans brownie. Chocolate bar chupa chups carrot cake bonbon fruitcake
            tootsie roll cake halvah caramels. Muffin gummi bears candy cake jelly beans carrot cake toffee jelly beans.
            Bonbon halvah powder chocolate bar candy canes pastry pudding. Tiramisu sesame snaps jelly beans.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup></script>

<style></style>
