<template>
  <main>
      <div class="main-title">
         <h2>Questo é il fantastico main</h2>
      </div>
      <div class="main-text">
         <div class="first-text">
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam ad nisi ex eveniet, necessitatibus temporibus sunt cum illum! Est, delectus. Assumenda debitis provident nam ea blanditiis vel voluptates ducimus tempora officiis quaerat id voluptate ex laborum ad praesentium cupiditate voluptatibus est, veniam eius. Non autem ad exercitationem pariatur quasi eaque beatae doloribus, qui illo consequuntur vitae laudantium tempora laboriosam! Aut, porro voluptatibus esse tempora earum provident dicta? Sequi vitae est veritatis tenetur consequuntur! Ratione facilis beatae earum pariatur magni maiores! Minus maxime exercitationem dolorum iste sequi, magnam inventore aut provident quisquam modi nihil nemo natus nesciunt, quam delectus atque, voluptatibus eaque reprehenderit blanditiis tenetur quibusdam deserunt voluptate? Ab alias corporis sint ad repellendus voluptates, nihil quidem recusandae similique. Iusto architecto accusantium magnam deserunt eius est culpa, minus eligendi neque quis blanditiis possimus nesciunt fugit quasi quam ullam. Adipisci illo blanditiis explicabo consequuntur voluptatibus veniam molestiae, recusandae repudiandae iure obcaecati voluptas. magnam inventore aut provident quisquam modi nihil nemo natus nesciunt, quam delectus atque, voluptatibus eaque reprehenderit blanditiis tenetur quibusdam deserunt voluptate? Ab alias corporis sint ad repellendus voluptates, nihil quidem recusandae similique. Iusto architecto accusantium magnam deserunt eius est culpa, minus eligendi neque quis blanditiis possimus nesciunt fugit quasi quam ullam. Adipisci illo blanditiis explicabo consequuntur voluptatibus veniam molestiae, recusandae repudiandae iure obcaecati voluptas.
            </p>
         </div>
         <div class="second-text">
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam ad nisi ex eveniet, necessitatibus temporibus sunt cum illum! Est, delectus. Assumenda debitis provident nam ea blanditiis vel voluptates ducimus tempora officiis quaerat id voluptate ex laborum ad praesentium cupiditate voluptatibus est, veniam eius. Non autem ad exercitationem pariatur quasi eaque beatae doloribus, qui illo consequuntur vitae laudantium tempora laboriosam! Aut, porro voluptatibus esse tempora earum provident dicta? Sequi vitae est veritatis tenetur consequuntur! Ratione facilis beatae earum pariatur magni maiores! Minus maxime exercitationem dolorum iste sequi, magnam inventore aut provident quisquam modi nihil nemo natus nesciunt, quam delectus atque, voluptatibus eaque reprehenderit blanditiis tenetur. Aut, porro voluptatibus esse tempora earum provident dicta? Sequi vitae est veritatis tenetur consequuntur! <br> Ratione facilis beatae earum pariatur magni maiores! Minus maxime exercitationem dolorum iste sequi, magnam inventore aut provident quisquam modi nihil nemo natus nesciunt, quam delectus atque, voluptatibus eaque reprehenderit blanditiis tenetur.
            </p>
         </div>
      </div>
      
  </main>
</template>

<script>
export default {
   // gli si assegna il nome prima di importarlo
   name: "Main"
}
</script>

<style scoped>

   main{
      height: calc(100vh - 80px - 80px);
      width: 100vw;
      background: cornsilk;
   }

   .main-title{
      text-align: center;
      padding: 20px 0;
      font-size: 30px;
   }

   .main-text{
      display: flex;
   }

   .first-text{
      width: 40%;
      padding: 20px;
   }

   .second-text{
      width: 60%;
      padding: 20px;
   }
</style>