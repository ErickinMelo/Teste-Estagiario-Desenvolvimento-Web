## Questões Teóricas

1. Qual a função do "head" no HTML?
R: A tag "head" é utilizada para fornecer informações sobre o documento sem si, que é utilizada pelo navegador. Nem todas as informações contidas no "head" serão vistas pelos usuários, como: 
a tag "meta", que são informações adicionais sobre a página, 
a tag "script" que é usada para incluir códigos javascript na página.
Porém, a informação como o título, é exibida para o usuário.

2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
R: Não, porque é necessário que a página seja responsiva, para que possa se adptar a tamanhos diferentes de tela.
Para deixar a página responsiva, pode-se uitlizar do CSS, para definir estilos diferentes para diversos tamanhos de tela.

3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?
R: Não, O código HTML e CSS é interpretado pelo navegador do usuário e transformado em uma representação visual em tempo real da página e não em forma de imagem.

4. Qual a função das tags H (h1, h2, h3, etc) no HTML?
R: A função das tags H é destacar um título ou subtítulo de um site. As tags H1 a H6 possuem diferentes níveis hierarquicos, geralmente em um site, o título principal é definido na tag h1 e os demais subtítulos são definidos nas tags h2, h3, h4 e assim por diante, conforme a importancia do texto.


5. O que é SEO e como funciona?
R: SEO é uma estratégia/técnica utilizada para otimizar um site e tem como objetivo melhorar o rankeamento do site em resultados de busca, como o Google por exemplo.
Para ter um bom SEO voce pode utilizar de palavras-chaves relevantes, a estrutura do seu site estar bem organizada, utilizando as tags de forma correta.

6. O uso de media query é obrigatório em todas as páginas?
R: Não necessariamente, se voce deseja que seu site possa ser acessado por diversos dispositivos voce deve usar o media query, para seu layout se adpatar a esses diversos tamanhos.
Mas nada impede de voce criar uma página e não utilizar o media query, porém seu site provavelmente ficará quebrado em algumas situações.

7. Qual a diferença entre CSS Inline e CSS em um arquivo?
R: Ambos funcionam, mas a diferença é que em um projeto grande, se voce utilizar o CSS inline, vai ficar muito "poluido" o projeto, por conta de ter muitas informações tudo junto, voce utilizando o CSS em um arquivo fica mais organizado e fácil de compreender.

8. Como criar animações no CSS? Dê um exemplo.
R: Voce pode utilizar a propiedade transition, transform ou animation.

Exemplo: 

<!-->HMTL<!-->
<button>Passe o mouse para ver a animação</button>

<!-->CSS<!-->
button {
  color: white;
  background: green;
  transition: background 2s;
}

button:hover,
button:focus {
  background: #000;
}

9. Qual a diferença entre class e ID no CSS?
R: A class é uilizada para definir um grupo de elementos, já o ID é um identificador único para um elemento

<div class="container" id=form-container><div></div>

.container {
  display: flex;
    justify-content: space-between;
    width: 990px;
}

#form-container {
  background-color: #878787;
}

10. Quais os diferentes tipos de seletores CSS?
R: É possivel selecionar pelo prórpio elemento, pela class ou pelo ID

<div></div>
<div class="container"></div>
<div id=carousel></div>


div {
  color: #fff;
}

.container {
  display: flex;
}

#carousel {
  background-color: #EEE;
}