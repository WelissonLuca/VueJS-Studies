#### Repositório criado para documentar meus estudos relacionados a VUE JS

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--_HH1pOzV--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/z74oqos1984w5g5ah0i9.jpeg" alt="VUE JS">

<br>



##### O que é VUE JS ?
<p align="center">

- Vue JS é um framework Javascript open source, lançado em Fevereiro de 2014 por Evan You, Desenvolvedor que atuava em um dos projetos do Google Creative Labs, em 2014.


- Foi nesse projeto que descobriu a necessidade de criar uma ferramenta mais completa e ágil para lidar com grandes UIs.

- Vue JS é muito utilizado para criar aplicações single page (página única) e também para desenvolver vários tipos de interfaces, que possuem necessidades de maior interação e experiência mais valorosa para o usuário.

- É importante frisar que Vue JS se enquadra em framework Javascript progressivo, isto é, Vue JS pode ser conectado em um pedaço de uma aplicação server-side que precisa otimizar a UI.
</p>

### Instalação e uso

###### CDN
- Para propósitos de prototipação ou aprendizado, você pode usar a versão mais recente com:

```javascript
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

- Para produção, recomendados vincular a um número de versão específico para evitar quebra de funções das versões mais novas:

```javascript
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.12"></script>
```
- Se você está usando Modulos ES nativos, existe uma build compatível com isso:

```javascript
<script type="module">
  import Vue from 'https://cdn.jsdelivr.net/npm/vue@2.6.12/dist/vue.esm.browser.js'
</script>
```

######  NPM

- NPM é o método de instalação recomendado para construção de aplicações em larga escala com o Vue.
```bash
# última versão estável
$ npm install vue
```
######  CLI

- Vue.js oferece um CLI oficial para rapidamente construir ambiciosas Single Page Applications. Ele possui um conjunto de configurações de build prontas para um processo de trabalho de front-end moderno.

```bash
npm install -g @vue/cli
# Ou
yarn global add @vue/cli
Create a project:

vue create my-project
# Ou
vue ui
```