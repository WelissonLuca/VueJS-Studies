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

###### NPM

- NPM é o método de instalação recomendado para construção de aplicações em larga escala com o Vue.

```bash
# última versão estável
$ npm install vue
```

###### CLI

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

##### Estado & Reatividade

- Estado são os dados da aplicação.

- Reatividade e o ato das alterações que forem feitas no JS serem refletidas no HTML.

##### Métodos & Diretivas

- Método Vue é uma função associada à instância Vue.

- Diretivas são atributos HTML que são adicionados dentro de modelos. Todos começam com v-, para indicar que é um atributo especial do Vue.

###### Diretivas exemplos

- v-text Em vez de usar a interpolação, você pode usar a diretiva v-text. Ele executa o mesmo trabalho:

```html
<span v-text="name"></span>
```

- <strong>v-once</strong> Renderize o elemento e o componente apenas uma vez

```html
<span v-once>{{ name }}</span> 
```

- <strong>v-html</strong> Existem casos em que você deseja gerar HTML e fazer com que o navegador o interprete. Você pode usar a diretiva v-html:

```html
<span v-html="someHtml"></span>
```

- <strong>v-for</strong> é usado para renderizar uma lista de elementos com base nos dados de um Array.

```html
<ul id="example-1">
  <li v-for="item in items" :key="item.message">
    {{ item.message }}
  </li>
</ul>
```
