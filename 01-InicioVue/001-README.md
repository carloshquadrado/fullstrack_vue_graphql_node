# Aula 001

```
## Criando o Ambiente com o VueJS
```
vue create .
    OBS: Fazer na pasta do Projeto
Current directory? Y
Pick a preset: default (babel, eslint)
```

## Limpando o arquivo padrão App.vue

###Tag <Script>
```
Remover a linha da importação do componente HelloWorld dentro da tag <script>
Remover as linhas da renderização do componente HelloWorld dentro da tag <script>

<script>
import HelloWorld from './components/HelloWorld.vue'

  components: {
    HelloWorld
  }
</script>


Ficando  da seguinte forma:
<script>
export default {
  name: 'app'
}
</script>
``

###Tag <Template>
``
Remover o bloco abaixo, retirando o logo e o título.

  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>

Ficando da seguinte forma:
<template>

</template>
``
###Tag <style>
``
Remover o bloco abaixo, retirando a estilização CSS.

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

Ficando da seguinte forma:
<style>

</style>
``