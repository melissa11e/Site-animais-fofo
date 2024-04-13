# Site-animais-fofo
Meu primeiro projeto HTML com um pouquinho de JavaScript.

Estou aprendendo html e essa página foi um passo muito importante para esclarecer alguns conceitos.
Basicamente, é uma página onde você pode escolher entre um cachorro e um gato, e embora seja uma concepção simples, são coisas que acabei de aprender e queria colocar em prática.
abaixo das imagens, possuem dois botões com tags <script> simples, onde ao clicar, você é redirecionado a outra página.


Anotação para o eu do futuro e colegas bucando conhecimento: os valores na tag de abertura do botão precisam ser
- <button onclick="variável p/definir a ação()"> Texto </button>
No caso do meu projeto, eu usei algumas facilidades do bootstrap, que me permitiu deixa-lo "decorado":
class="bnt bnt-primary mt-3"    - o bnt indica que é um botão.  - o bnt-primary decide a cor (poderia ser danger, secondary, success, info, warning.....) - O mt, se não me engano, define o tamanho da borda.
   ficando assim: <button onclick="variável()" class="bnt btn-primary my-3"> ....
  
  
- Recorde-mos agora a variável definida para a ação do onclick. Logo em seguida da tag button, abre-se uma tag <script> onde definiremos o comando que ao clicar, nos direcionará às outras páginas.
Fica mais ou menos assim:
<script>
  function variavel(){
    window.location.href="link da outra página ou endereço do arquivo html da outra página";
  }
</script>

O comando que faz a "mágica" é o que damos á variável, o window.location.href
lembrando que onclick=variável com o comando.
