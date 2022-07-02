<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <Navbar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img :src="foto" contain max-height="500" class="mt-15"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="red--text text-darken-4 top">Olá, eu sou a Bruna!</h5>
          <h1 class="white--text">Desenvolvedora Front-end</h1>
          <p class="grey--text">
            Das primeiras linhas de código em HTML até o React e VueJS, <br/>
            aprendo todos os dias que ser uma boa dev não está em saber tudo, <br/>
            mas sim na determinação de não parar, estudar, pesquisar, praticar <br/>
            e,principalmente, amar o que eu faço seja criando, incrementando ou <br/>
            buscando erros e soluções.
          </p>
          <v-btn tile color="#A7121D" dark>sobre mim</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src
import Navbar from "../components/Navbar.vue";
import foto from "../assets/foto4.svg";

export default {
  name: "Home",
  data() {
    return {
      foto,
    };
  },
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.top {
  margin-top: 180px;
}

.topInverse {
  margin-top: -250px;
}

.topTolbar {
  margin-top:100px;
  text-align: center;
}

.first {
  width: 100%;
  height: 610px;
  background:  linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align:  center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.bgColor1 {
  background-color:  #1e1e1e;
}

.bgColor2 {
  background-color: #ce1d2a;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight {
  margin-right: 8px;
}

.mButton {
  margin-bottom: 8px;
}

.padding {
  padding: 8px 0px;
}

.col-12.padd {
  padding: 12px 0 !important;
}

.col-12.childcol {
  padding: 0 !important;
}

h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>
