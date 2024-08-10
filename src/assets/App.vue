<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous"></link>



<template>
  
<div class="containerPai">


  <div class="cabecalho">
    <img alt="Logo" class="logo" src="./assets/etec.png" width="200" height="125" />
    <img class="ftperfil" src="./assets/perfil.png" alt="" >
    <ul>
      <li class="">Sair</li>
      <li class="" >Perfil</li>
    </ul>
  </div>
  

      <div class="poster">   
          <img src="" alt="imagem curso 1 Mysql">
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

<style>

.containerPai {
  background-color: rgb(227, 225, 225);
}

.cabecalho{
  background-color: rgb(180, 180, 180);
}

.poster{
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: rgb(207, 18, 18);
  color: aquamarine;
  width: 800px;
  height: 550px;
}

</style>
