<script setup>
import badgeWhite from "./assets/badge-white.svg"
import logoColor from "./assets/logo-color.svg"
import logoWhite from "./assets/logo-white.svg"
import hero from "./assets/hero.png"
import heroMobile from "./assets/hero_mobile.png"
import iconCoin from "./assets/icon-coin.svg"
import iconBucketPencil from "./assets/icon-bucket-pencil.svg"
import iconRoll from "./assets/icon-roll.svg"
import iconBucket from "./assets/icon-bucket.svg"
import recipe36 from "./assets/bucket-size-icon-36l.svg"
import recipe15 from "./assets/bucket-size-icon-15l.svg"
import bucket1 from "./assets/Group_126.png"
import bucket2 from "./assets/Group_130.png"
import bucket3 from "./assets/Group_154.png"
import sofa from "./assets/sofa.png"
import pintor from "./assets/pintor.png"
import rightDec from "./assets/right-decorator.svg"
import beforeForm from "./assets/frame-form-before.svg"
import badgePurple from "./assets/badge-purple.svg"

</script>

<template>
  <main>
    <section :class="
      `bg-[#4F008C] 
    md:bg-[url(${hero})] 
    md:bg-right-top md:bg-[length:720px_auto]
    bg-no-repeat`">
      <div class="container mx-auto text-white  md:py-24 max-w-6xl">
        <img class="badge hidden md:block" :src="badgeWhite"
          alt="Selo leinertex">

        <div class="columns-1 relative text-center md:text-left">
          <!-- LOGO MOBILE -->
          <img class="md:hidden h-7 absolute top-8 left-6" :src="logoColor"
            alt="Logo vallecor mobile">

          <!-- LOGO DESKTOP -->
          <img class="mb-16 hidden md:block" :src="logoWhite"
            alt="Logo vallecor">

          <!-- HERO MOBILE -->
          <img class="md:hidden" :src="heroMobile" alt="Hero Mobile">

          <h2 class="mb-8 md:mb-16 pt-32 text-3xl md:text-5xl md:pt-0  ">
            Economia e qualidade <br />
            <strong class="font-black">do jeito que você<br />
              sempre sonhou</strong>
          </h2>

          <button class="btn btn-large blue mb-20">Conheça nossa linha</button>

          <h3 class="mb-10 md:mb-20 text-2xl md:text-4xl">
            A escolha certa para quem <br />
            quer uma <strong class="font-black">vida mais colorida</strong>.
          </h3>
        </div>

        <div class="grid grid-cols-2 gap-y-8 pb-8 md:pb-4 md:grid-cols-4">
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" :src="iconCoin" alt="Icon">
            Economia na hora <br />de pintar
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" :src="iconBucketPencil" alt="Icon">
            Fácil de <br />aplicar
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" :src="iconRoll" alt="Icon">
            Boa Cobertura
          </div>
          <div class="text-center font-black flex flex-col self-baseline">
            <img class="icon mx-auto" :src="iconBucket" alt="Icon">
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

        <!-- CARD 1 -->
        <div
          class="bg-[#8B2FAE] rounded-lg md:flex min-w-[320px] md:w-auto text-white px-5 md:px-10 py-5 flex-row-reverse justify-between">
          <img class="card-product__image mt-[-100px] md:mt-0" :src="bucket1"
            alt="Product" />

          <div
            class="xxx md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Fosco Ideal</h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img :src="recipe36" alt="">
                <img :src="recipe15" alt="">
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

        <!-- CARD 2 -->
        <div class="bg-[#37C0C9] 
          rounded-lg text-white px-5 py-5 flex flex-col
          min-w-[320px] md:w-auto md:px-10 md:flex md:flex-row ">
          <img class="mt-[-100px] md:mt-0" :src="bucket2" alt="Product" />

          <div
            class="xxx md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-self-end md:justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Massa Corrida
              </h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img :src="recipe36" alt="">
                <img :src="recipe15" alt="">
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
              class="flex flex-col justify-around  font-black max-w-[180px] gap-y-5 md:gap-y-1 text-left self-center md:self-auto grow">
              <p>Fácil de Aplicar e Lixar</p>
              <p>Nivela e corrige imperfeições da parede</p>
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

        <!-- CARD 3 -->
        <div class="bg-[#FF9E32] 
          rounded-lg text-white px-5 py-5 flex flex-col
          min-w-[320px] md:w-auto md:px-10 md:flex md:flex-row-reverse 
          items-center">
          <img class="mt-[-100px] md:mt-0" :src="bucket3" alt="Product" />

          <div
            class="xxx md:text-left flex flex-col md:flex-row flex-1 gap-5 justify-self-end md:justify-around">
            <div class="flex flex-col justify-around">
              <h5 class="text-4xl md:text-5xl font-black mb-1">Esmalte Sintético
              </h5>

              <p class="text-sm mb-5">Disponibilidade:</p>

              <div
                class="flex items-baseline justify-center md:justify-start gap-8">
                <img :src="recipe36" alt="">
                <img :src="recipe15" alt="">
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
              class="flex flex-col justify-around  font-black max-w-[180px] gap-y-5 md:gap-y-1 text-left self-center md:self-auto grow">
              <p>Corrige e uniformiza a absorção</p>
              <p>Melhor aderência da tinta</p>
              <p>Mais rendimento da tinta</p>
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

      </div>
    </section>

    <section class="flex text-white flex-wrap">
      <div class="bg-[#13467E] md:flex-1 w-full">
        <div class="flex justify-end">
          <img :src="sofa" alt="Imagem sofá" />
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
          <img :src="pintor" alt="Imagem sofá">
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
      <img class="hidden md:block absolute top-[-48px] right-0 " :src="rightDec"
        alt="Decorator">
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
      :src="beforeForm" alt="Decorator">

    <img
      class=" w-[100px] md:w-auto absolute top-0 left-[50%] translate-x-[-50%]"
      :src="badgePurple" alt="Decorator">

    <img class="h-[26px] md:h-auto md:mr-[170px]" :src="logoColor"
      alt="Logo Vallecor">

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

.badge {
  @apply absolute top-0 right-[50%] translate-x-[50%];
}

.btn {
  @apply rounded font-black text-sm bg-slate-200 py-[10px] px-[33px];

  &.purple {
    @apply bg-purple-500;
  }

  &.blue {
    @apply bg-[#37C0C9];
  }

  &.yellow {
    @apply bg-[#FFE600] text-[#8B2FAE];
  }

  &.white {
    @apply bg-white text-[#13467E];
  }

  &-download {
    @apply flex items-center text-sm px-4 py-1 leading-none text-[#FFE600];
  }

  &-large {
    @apply py-[16px] px-[20px];
  }

  .icon-wrapper {
    @apply flex flex-col items-center self-stretch text-center font-black;
  }
}



/* .btn .btn .card-product {
  @apply rounded-lg flex text-white px-10 py-5;
}

.icon-wrapper .icon {
  @apply min-h-[90px] mb-3;
} */
</style>
