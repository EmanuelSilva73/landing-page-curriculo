<template>
  <v-app class="portfolio-bg">
    <v-app-bar flat color="transparent" height="80">
      <v-container max-width="1040px">
          <div class="d-flex justify-end">
            <v-btn variant="text">Sobre</v-btn>
            <v-btn variant="text">Experiência</v-btn>
            <v-btn variant="text">Blog</v-btn>
            <v-btn variant="elevated" color="primary">Contato</v-btn>
          </div>
      </v-container>
    </v-app-bar>
    <v-main>
      <v-container max-width="1040">
        <v-row>
          <v-col cols="12" md="6">
            <h1 class="hero-title">
    Olá, sou <span class="text-primary">Emanuel Silva</span>
  </h1>

  <p class="hero-description mt-6">
    Analista e Desenvolvedor de Sistemas <br> Gerente de Projetos,
    apaixonado por tecnologia, inovação, inteligência artificial e transformação digital.
  </p>

  <div class="d-flex ga-2 mt-6">
    <!-- redes sociais -->
  </div>
            <v-btn icon>
              <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn icon>
              <v-icon>mdi-linkedin</v-icon>
            </v-btn>
            <v-btn icon>
              <v-icon>mdi-instagram</v-icon>
            </v-btn>
            <v-btn icon>
              <v-icon>mdi-whatsapp</v-icon>
            </v-btn>
          </v-col>
          <v-col cols="12" md="6" class="d-flex justify-center">
    <v-img
      src="/3.png"
      alt="Tela de código"
      width="100%"
      max-width="560"
    />
  </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<style>
.portfolio-bg {
  background: #020417;
}
.hero-title {
  font-size: 72px;
  line-height: 1;
  font-weight: 700;
  letter-spacing: -3px;
}

.hero-description {
  font-size: 20px;
  line-height: 1.6;
  max-width: 600px;
  opacity: 0.75;
}

@media (max-width: 600px) {
  .hero-title {
    font-size: 44px;
    letter-spacing: -1px;
  }
}
</style>


  