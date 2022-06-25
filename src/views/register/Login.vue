<template>
  <div class="main">
    <div class="nav">
      <div class="voltar">
        <svg style="width: 24px; height: 24px" viewBox="0 0 24 24">
          <path
            fill="currentColor"
            d="M20,11V13H8L13.5,18.5L12.08,19.92L4.16,12L12.08,4.08L13.5,5.5L8,11H20Z"
          />
        </svg>
      </div>

      <div class="titulo">
        <h3>LOGIN</h3>
      </div>

      <div class="button-rtn"></div>
    </div>

    <div class="avatarElogin">
      <div class="img-logo">
        <v-avatar color="#D9D9D9" size="150"></v-avatar>
      </div>

      <div class="form">
        <v-form ref="form">
          <v-text-field label="E-mail" required></v-text-field>

          <v-text-field label="Senha" required></v-text-field>
        </v-form>
        <v-col>
          <div class="my-5">
            <v-btn color="#"> ENTRAR </v-btn>
          </div>
        </v-col>
      </div>
    </div>
  </div>
</template>

<style>
.main {
  display: flex;
  flex-direction: column;
}
.nav {
  position: absolute;
  width: 100%;
  height: 5%;
  border-bottom: 1px solid #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  top: 0;
}

.titulo {
  padding-right: 2rem;
}



.img-logo {
  margin-bottom: 25%;
}

.v-btn.v-btn--is-elevated.v-btn--has-bg.theme--light.v-size--default {
  background-color: #deefb8;
  color: #000000;
  font-weight: 400;
  height: 50px;
  width: 23rem;
  border-radius: 60px;
  box-shadow: none;
  border-style: groove;
}
</style>
