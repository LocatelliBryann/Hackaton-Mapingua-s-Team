<template>
  <v-app class="tudo">
    <v-flex>

        <div class="d-flex align-center">
          <img src="./chevron-back.png" alt="" srcset="" class="botao">
          <h3 >CADASTRO</h3>
          
        </div>
        <hr/>
      <div class="main">  
        <div class="texto">
            <h1>Qual conta deseja <br> criar?</h1>
        </div>
          <div class="checkboxs">
            <v-col
            cols="3"
            sm="4"
            md="4"
          >
            <v-checkbox
              label="Estudante"
              color="blue"
              hide-details
            ></v-checkbox>

            <v-checkbox
              label="Monitor"
              color="blue"
              hide-details
            ></v-checkbox>

            <v-checkbox
              label="Administrador"
              color="blue"
              hide-details
            ></v-checkbox>
          </v-col>
          </div>

        <div id="botao1">
             <v-btn elevation="5" color="#E1EFBF" rounded>Avançar</v-btn>
        </div>
      </div>

    </v-flex>
  </v-app>
</template>

<script>

</script>

<style>

h1 {
  margin-top: 100px;
}

.main {
  background: linear-gradient(to top, #F3FBF4, #e4ffaf);
  height: 150vh;
}
#botao1{ 
    margin-top: 550px;
    min-width: 100px;

}

.checkboxs {
  
  position: absolute
  
}

hr {
  border-color: black;
  
}

.texto {
  font-size: 20px;
}

img {
  width: 50px;
  height: 50px;
  margin-right: 400px;
  display:inline-block;
  vertical-align:top;
}
h3 {
  position: absolute;
  margin-left: 50px;
}

</style>