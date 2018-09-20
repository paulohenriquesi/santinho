<template>
  <b-card 
    title="Bem vindo ao Santinho Digital"
    style="border: 1px solid #DDD">
    <p>Antes de prosseguir, é preciso concordar com os seguintes termos: </p>
    <ul>
      <li>Todos os santinhos gerados são armazenados na base dados para 
        possibilitar o compartilhamento</li>
      <li>Os santinhos salvos não guardam nenhuma identificação de quem os gerou
          e a única forma de recupera-los é com o link gerado ao final.</li>
      <li>Reservamo-nos o direito de obtermos estatísticas com base nos santinhos gerados</li>
    </ul>
    <p>Ao prosseguir, você concorda com os termos listados acima.</p>
    <router-link :to="{name: 'presidente'}">
      <b-button variant="primary">
        Continuar
      </b-button>
    </router-link>    
  </b-card>
</template>
