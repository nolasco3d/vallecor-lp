<script setup>

</script>

<template>
  <main class="">
    <section class="
        bg-[#4F008C] 
          
          md:bg-[url(src/assets/hero.png)] 
          md:bg-right-top md:bg-[length:720px_auto]
          bg-no-repeat">
      <div class="container mx-auto text-white  md:py-24 max-w-6xl">
        <img class="badge hidden md:block" src="src/assets/badge-white.svg"
          alt="Selo leinertex">

        <div class="columns-1 relative text-center md:text-left">
          <!-- LOGO MOBILE -->
          <img class="md:hidden h-7 absolute top-8 left-6"
            src="src/assets/logo-color.svg" alt="Logo vallecor mobile">

          <!-- LOGO DESKTOP -->
          <img class="mb-16 hidden md:block" src="src/assets/logo-white.svg"
            alt="Logo vallecor">

          <!-- HERO MOBILE -->
          <img class="md:hidden" src="src/assets/hero_mobile.png"
            alt="Hero Mobile">

          <h2 class="mb-8 md:mb-16 pt-32 text-3xl md:text-5xl md:pt-0  ">
            Economia e qualidade <br />
            <strong class="font-black">do jeito que você<br />
              sempre sonhou</strong>
          </h2>

          <button class="btn large blue mb-20">Conheça nossa linha</button>

          <h3 class="mb-10 md:mb-20 text-2xl md:text-4xl">
            A escolha certa para quem <br />
            quer uma <strong class="font-black">vida mais colorida</strong>.
          </h3>
        </div>

        <div class="grid grid-cols-2 gap-y-8 pb-8 md:pb-4 md:grid-cols-4">
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" src="src/assets/icon-coin.svg" alt="Icon">
            Economia na hora <br />de pintar
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" src="src/assets/icon-bucket-pencil.svg"
              alt="Icon">
            Fácil de <br />aplicar
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" src="src/assets/icon-roll.svg" alt="Icon">
            Boa Cobertura
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" src="src/assets/icon-bucket.svg"
              alt="Icon">
            Cores variadas <br />para ambientes <br />mais bonitos
          </div>
        </div>
      </div>

    </section>

    <section class="text-center pt-8 md:py-20">

      <h4 class="font-black text-2xl md:text-4xl text-[#434343] mb-11">
        Conheça nossas linhas de produtos
      </h4>

      <div class="flex overflow-x-scroll md:overflow-x-hidden 
        px-3 gap-4 md:gap-12 pt-[80px] pb-7 md:pt-0 md:pb-0
        md:container md:mx-auto md:max-w-6xl md:flex-col ">

        <div
          class="bg-[#8B2FAE] rounded-lg md:flex min-w-[320px] md:w-auto text-white px-5 md:px-10 py-5 flex-row-reverse justify-between">
          <img class="card-product__image mt-[-100px] md:mt-0"
            src="src/assets/Group 126.png" alt="Product" />

          <div
            class="xxx md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Fosco Ideal</h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img src="src/assets/bucket-size-icon-36l.svg" alt="">
                <img src="src/assets/bucket-size-icon-15l.svg" alt="">
              </div>

              <div class="hidden md:flex">
                <button class="btn yellow">Ver Cores</button>
                <button class="btn-download">
                  <span class="material-symbols-outlined">download</span>
                  <p class="m-0 pl-2 flex flex-col">
                    <strong class="font-black">DOWNLOAD</strong>
                    FICHA TÉCNICA
                  </p>
                </button>
              </div>
            </div>

            <div
              class="flex flex-col justify-around  font-black max-w-[180px] gap-y-5 md:gap-y-1 text-left self-center md:self-auto">
              <p>Economia e qualidade para sua casa</p>
              <p>Excelente rendimento e acabamento</p>
              <p>Parede mais bonita, disfarça leves imperfeições*</p>
            </div>

            <div class="flex md:hidden">
              <button class="btn yellow">Ver Cores</button>
              <button class="btn-download">
                <span class="material-symbols-outlined">download</span>
                <p class="m-0 pl-2 flex flex-col">
                  <strong class="font-black">DOWNLOAD</strong>
                  FICHA TÉCNICA
                </p>
              </button>
            </div>
          </div>
        </div>

        <div
          class="bg-[#37C0C9] rounded-lg md:flex min-w-[320px] md:w-auto text-white px-10 py-5 justify-between">
          <img class="card-product__image " src="src/assets/Group 130.png"
            alt="Product" />

          <div
            class="xxx text-center md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Massa Corrida
              </h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img src="src/assets/bucket-size-icon-36l.svg" alt="">
                <img src="src/assets/bucket-size-icon-15l.svg" alt="">
              </div>

              <div class="hidden md:flex">
                <button class="btn yellow">Ver Cores</button>
                <button class="btn-download">
                  <span class="material-symbols-outlined">download</span>
                  <p class="m-0 pl-2 flex flex-col">
                    <strong class="font-black">DOWNLOAD</strong>
                    FICHA TÉCNICA
                  </p>
                </button>
              </div>
            </div>

            <div class="flex flex-col justify-around font-black max-w-[180px]">
              <p>Fácil de Aplicar e Lixar</p>
              <p>Nivela e corrige imperfeições da parede</p>
            </div>
          </div>
        </div>

        <div
          class="bg-[#FF9E32] rounded-lg md:flex min-w-[320px] md:w-auto text-white px-10 py-5 flex-row-reverse justify-between">
          <img class="card-product__image " src="src/assets/Group 154.png"
            alt="Product" />

          <div
            class="xxx text-center md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Esmalte Sintético
              </h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img src="src/assets/bucket-size-icon-36l.svg" alt="">
                <img src="src/assets/bucket-size-icon-15l.svg" alt="">
              </div>

              <div class="hidden md:flex">
                <button class="btn yellow">Ver Cores</button>
                <button class="btn-download">
                  <span class="material-symbols-outlined">download</span>
                  <p class="m-0 pl-2 flex flex-col">
                    <strong class="font-black">DOWNLOAD</strong>
                    FICHA TÉCNICA
                  </p>
                </button>
              </div>
            </div>

            <div class="flex flex-col justify-around font-black max-w-[180px]">
              <p>Corrige e uniformiza a absorção</p>
              <p>Melhor aderência da tinta</p>
              <p>Mais rendimento da tinta</p>
            </div>
          </div>
        </div>

      </div>
    </section>

    <section class="flex text-white flex-wrap">
      <div class="bg-[#13467E] md:flex-1 w-full">
        <div class="flex justify-end">
          <img src="src/assets/sofa.png" alt="Imagem sofá" />
        </div>

        <div class="max-w-sm mx-auto my-10 px-6 md:p-0">
          <h6 class="text-3xl md:text-4xl mb-5">Vale a pena <br />
            <strong class="font-black">mudar de cor!</strong>
          </h6>
          <p>
            Explore todas as possibilidades dos nossos produtos para alegrar o
            seu ambiente! Aqui, mudar de cor vale a pena!
          </p>
        </div>
      </div>

      <div class="bg-[#37C0C9] md:flex-1 w-full">
        <div class="flex justify-end">
          <img src="src/assets/pintor.png" alt="Imagem sofá">
        </div>

        <div class="max-w-sm mx-auto my-10 px-6 md:p-0">
          <h6 class="text-3xl md:text-4xl mb-5">
            <strong class="font-black">Você é pintor?</strong><br />
            Então vai se apaixonar!
          </h6>
          <p>
            Além do melhor custo-benefício do mercado, as tintas Vallecor têm
            muita tecnologia e estrutura. Contamos com um parque industrial
            próprio e modernos laboratórios para o desenvolvimento dos produtos.
          </p>
          <button class="btn white mt-5">Conheça a nossa estrutura</button>
        </div>
      </div>
    </section>

    <section class="flex flex-center text-center">
      <div class="container mx-auto py-11 max-w-4xl px-5 md:px-0">
        <div class="font-black text-2xl md:text-4xl text-[#434343] mb-11">
          Dúvidas Frequentes
        </div>

        <div class="accordion border-b text-left">
          <div
            class="text-[#13467E] font-black text-xl flex items-start md:items-center justify-between py-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elitaecenas id ex
            porttitor?
            <span
              class="material-symbols-outlined text-[#B34FC5] rotate-180">expand_more</span>
          </div>

          <div class="pb-10">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
              id ex porttitor, bibendum diam id, consequat nulla. Proin risus,
              auctor at dictum vitae, tristique et turpis. Etiam orci massa,
              egestas id ultricies at, iaculis eget tellus. Morbi eget blandit
              dolor. Suspendisse lacinia vehicula purus eu dignissim. Vivamus
              ullamcorper, erat vel aliquet sagittis, erat magna sollicitudin
              urna, ac pretium diam tortor ut nunc. Sed pharetra vestibulum quam
              quis aliquet.</p>
          </div>
        </div>

        <div class="accordion border-b text-left">
          <div
            class="text-[#13467E] font-black text-xl flex justify-between py-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elitaecenas id ex
            porttitor?
            <span
              class="material-symbols-outlined text-[#B34FC5]">expand_more</span>
          </div>

          <div class="pb-10 hidden">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
              id ex porttitor, bibendum diam id, consequat nulla. Proin risus,
              auctor at dictum vitae, tristique et turpis. Etiam orci massa,
              egestas id ultricies at, iaculis eget tellus. Morbi eget blandit
              dolor. Suspendisse lacinia vehicula purus eu dignissim. Vivamus
              ullamcorper, erat vel aliquet sagittis, erat magna sollicitudin
              urna, ac pretium diam tortor ut nunc. Sed pharetra vestibulum quam
              quis aliquet.</p>
          </div>
        </div>

      </div>
    </section>

    <section class="bg-[#4F008C] py-16 text-white relative min-h-0 h-auto">
      <img class="hidden md:block absolute top-[-48px] right-0 "
        src="src/assets/right-decorator.svg" alt="Decorator">
      <div class="container mx-auto text-center max-w-3xl">

        <h4 class="text-2xl font-light mb-6">
          Quer saber mais sobre os nossos produtos, e ficar ligado nas
          novidades? <br />
          <span class="font-black">Cadastre-se!</span>
        </h4>

        <form action=""
          class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-4 mb-10 px-5">
          <div class="flex flex-col items-start">
            <label class="ml-2 font-black" for="name">Seu nome</label>
            <input
              class="border bg-transparent px-2 py-3 text-xs w-full focus:outline-none"
              type="text" name="name" placeholder="Digite seu nome">
          </div>
          <div class="flex flex-col items-start">
            <label class="ml-2 font-black" for="email">Seu email</label>
            <input
              class="border bg-transparent px-2 py-3 text-xs w-full focus:outline-none"
              type="email" name="email" placeholder="Digite seu nome">
          </div>
          <div class="flex flex-col items-start">
            <label class="ml-2 font-black" for="job">Você é:</label>
            <input
              class="border bg-transparent px-2 py-3 text-xs w-full focus:outline-none"
              type="text" name="job" placeholder="Selecione sua ocupação">
          </div>
          <div class="flex flex-col items-start">
            <label class="ml-2 font-black" for="phone">Seu telefone</label>
            <input
              class="border bg-transparent px-2 py-3 text-xs w-full focus:outline-none"
              type="tel" name="phone" placeholder="Somente números, com DDD">
          </div>

        </form>
        <button class="btn blue" type="submit">Cadastrar</button>
      </div>
    </section>
  </main>

  <footer class="relative flex justify-between px-6 md:justify-around py-12">
    <img class=" hidden md:block absolute top-0 translate-y-[-50%] left-0"
      src="src/assets/frame-form-before.svg" alt="Decorator">

    <img
      class=" w-[100px] md:w-auto absolute top-0 left-[50%] translate-x-[-50%]"
      src="src/assets/badge-purple.svg" alt="Decorator">

    <img class="h-[26px] md:h-auto md:mr-[170px]"
      src="src/assets/logo-color.svg" alt="Logo Vallecor">

    <div class="flex flex-col">
      <span
        class="text-gray-500 max-w-[100px] md:max-w-none leading-none">Central
        de
        Atendimento</span>
      <a class="font-black" href="tel:08007044244">0800 704 4244</a>
    </div>
  </footer>
</template>

<style scoped>
/* * {
  border: dotted 1px tomato;
} */
.material-symbols-outlined {
  font-variation-settings:
    'FILL' 0,
    'wght' 400,
    'GRAD' 200,
    'opsz' 48
}


section {
  /* height: 100vh; */
}

.badge {
  @apply absolute top-0 right-[50%] translate-x-[50%];
}

.btn {
  @apply rounded font-black text-sm bg-slate-200 py-[10px] px-[33px];
}

.btn.large {
  @apply py-[16px] px-[20px];
}

.btn.blue {
  @apply bg-[#37C0C9];
}

.btn.yellow {
  @apply bg-[#FFE600] text-[#8B2FAE];
}

.btn.white {
  @apply bg-white text-[#13467E];
}

.btn-download {
  @apply flex items-center text-sm px-4 py-1 leading-none text-[#FFE600];
}

.icon-wrapper {
  @apply flex flex-col items-center self-stretch text-center font-black;
}

.card-product {
  @apply rounded-lg flex text-white px-10 py-5;
}

/* 
.sect {
  display: flex;
flex-direction: column;
height: 100%;
justify-content: space-around;
} 
*/

.icon-wrapper .icon {
  @apply min-h-[90px] mb-3;
}
</style>
