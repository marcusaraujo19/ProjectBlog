<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>
<template>
<div class="containerPai">


  <div class="cabecalho">
    <img alt="Logo etec" src="./assets/etec.png" width="200" height="125"  />
    <img src="./assets/perfil.png" alt="imagem do perfil"  width="20px" height="20px">
    <ul>
      <li class="">Sair</li>
      <li class="" >Perfil</li>
    </ul>
  </div>
  

      <div class="poster">
         <img src="./assets/post1.jpg" alt=""> </img>
          
            <h3>Curso 1</h3>

            <p>Bem-vindo ao curso de JavaScript! Neste curso, você vai explorar a linguagem que dá vida às páginas da web e permite criar interatividade e dinamismo. JavaScript é
                uma linguagem essencial para desenvolvedores front-end e também é amplamente usada no back-end com Começaremos com os fundamentos, abordando variáveis, tipos de dados 
                e operadores. Em seguida, vamos mergulhar em funções, objetos e arrays, essenciais para a construção de aplicativos complexos. 
                Você aprenderá a manipular o DOM para criar experiências de usuário interativas e a fazer requisições HTTP para se comunicar com servidores.
                Também cobriremos conceitos avançados, como promessas, async/await e eventos, que ajudarão a construir aplicações robustas e responsivas. Prepare-se para uma jornada prática
                com exercícios e projetos que solidificarão seu conhecimento. Vamos começar a desbravar o mundo do JavaScript e transformar suas ideias em realidade!</p>
        </div>


<div class="poster">
         <img src="./assets/post2.jpg" alt=""> </img>
          
            <h3>Curso 1</h3>

            <p>Bem-vindo ao curso de JavaScript! Neste curso, você vai explorar a linguagem que dá vida às páginas da web e permite criar interatividade e dinamismo. JavaScript é
                uma linguagem essencial para desenvolvedores front-end e também é amplamente usada no back-end com Começaremos com os fundamentos, abordando variáveis, tipos de dados 
                e operadores. Em seguida, vamos mergulhar em funções, objetos e arrays, essenciais para a construção de aplicativos complexos. 
                Você aprenderá a manipular o DOM para criar experiências de usuário interativas e a fazer requisições HTTP para se comunicar com servidores.
                Também cobriremos conceitos avançados, como promessas, async/await e eventos, que ajudarão a construir aplicações robustas e responsivas. Prepare-se para uma jornada prática
                com exercícios e projetos que solidificarão seu conhecimento. Vamos começar a desbravar o mundo do JavaScript e transformar suas ideias em realidade!</p>
  </div>

<div class="poster">
         <img src="./assets/post3.jpg" alt=""> </img>
          
            <h3>Curso 1</h3>

            <p>Bem-vindo ao curso de JavaScript! Neste curso, você vai explorar a linguagem que dá vida às páginas da web e permite criar interatividade e dinamismo. JavaScript é
                uma linguagem essencial para desenvolvedores front-end e também é amplamente usada no back-end com Começaremos com os fundamentos, abordando variáveis, tipos de dados 
                e operadores. Em seguida, vamos mergulhar em funções, objetos e arrays, essenciais para a construção de aplicativos complexos. 
                Você aprenderá a manipular o DOM para criar experiências de usuário interativas e a fazer requisições HTTP para se comunicar com servidores.
                Também cobriremos conceitos avançados, como promessas, async/await e eventos, que ajudarão a construir aplicações robustas e responsivas. Prepare-se para uma jornada prática
                com exercícios e projetos que solidificarão seu conhecimento. Vamos começar a desbravar o mundo do JavaScript e transformar suas ideias em realidade!</p>
  </div>
</div>
</template>

<style scoped>
.containerPai {
  background-color: rgb(227, 225, 225);
}

.cabecalho{
  background-color: rgb(180, 180, 180);
  display: flex;

}



.poster{
  
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: rgb(184, 184, 184);
  color: black;
  width: 90%;
  height: 90%;
  margin: auto;
  gap: 20px;
  margin-bottom: 20px;
  margin-top: 20px;
  font-family: Arial, Helvetica, sans-serif;
  padding: 20px; 
}


</style>
