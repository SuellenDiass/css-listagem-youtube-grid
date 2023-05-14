 
 <p> <h1 align="center">Recriando a listagem do youtube</h1></p>
 
 
 <p align="center">
    <img width="700" src="https://github-production-user-asset-6210df.s3.amazonaws.com/102911341/238186464-30e2e7df-a644-42e3-9ce0-c0b8981f15c8.png">
</p>

<p align="center">Seja redirecionado à página do 
<a href="https://css-listagem-youtube-grid.suellensouza.repl.co/" target="_blank">projeto</a></p>

<p align="center">
    <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/> 
    <br>
</p>Responsividade em andamento e corrigir alguns conflitos entres as propriedades e suas classes.


<p> <h2 align="center">Recriando a listagem do youtube</h2></p>

## Descrição do projeto 

<p align="justify">

 Desafio: Construir a Página de Listagem de vídeos no YouTube com CSS colocando em prática todos os conceitos aprendidos, principalmente sobre Grid Layout.

 O  projeto utiliza um layout de grade (grid layout) para estruturar a página. Segue um resumo das principais propriedades e elementos do layout:


- [x] Grid Layout: A propriedade CSS display: grid; é aplicada ao elemento body, definindo-o como um contêiner de grade. Isso permite organizar o conteúdo em colunas e linhas.

- [x] Áreas de Grade: O layout é dividido em áreas de grade usando a propriedade grid-template-areas. O cabeçalho ocupa a área "header", o menu lateral ocupa a área "aside", e o conteúdo principal ocupa a área "main".

- [x] Tamanhos de Coluna e Linha: As propriedades grid-template-columns e grid-template-rows são usadas para definir o tamanho das colunas e linhas da grade. As colunas têm tamanho automático (auto) e as linhas têm tamanhos diferentes, com a segunda linha ocupando 100% da altura da viewport (100vh).

- [x] Posicionamento de Elementos: Os elementos dentro do cabeçalho (#header) estão organizados usando a propriedade display: grid;. Os elementos são posicionados usando a propriedade grid-area com valores correspondentes às áreas de grade definidas anteriormente.

- [x] Menu Lateral: O menu lateral é definido como um elemento aside com a classe menu_aside. Ele é fixado à esquerda da página usando a propriedade position: fixed;. Os itens do menu são listados usando uma lista não ordenada (ul) e cada item é estilizado como uma linha da grade.

- [x] Conteúdo Principal: O conteúdo principal é definido como um elemento main com a classe main_container. Ele contém uma lista de vídeos representados por elementos li com a classe videos__item. Os vídeos são organizados em uma grade flexível usando a propriedade display: flex; e a propriedade flex-wrap: wrap; para que os vídeos se ajustem automaticamente ao tamanho da tela.

- [x] Observações: falta analisar os conflitos das propriedades da classe .descricao-video com o uso da pseudo classe :nth-child() no aside e terminar de fazer a responsividade para telas menores.
Esqueci de criar o reset.css que é uma boa prática para garantir consistência entre os navegadores.


###

## Tecnologias utilizadas

<a href="#" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html" width="40" height="40"/> </a> 

<a href="#" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css" width="40" height="40"/> </a> 

<a href="#" target="_blank"> <img src="https://camo.githubusercontent.com/ee5225ba7c4338f1a1c10121ec32c396e1a4a2f5b0b58b6afd6d5c56ff5d6196/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f7673636f64652f7673636f64652d6f726967696e616c2d776f72646d61726b2e737667" alt="firebase" width="40" height="40"/> </a>

###


## Curso Formação Front-end Web Developer administrado pela Dio.me com a tutora Michele Ambrosio/Desenvolvedora Front-End

 [DIO](https://www.dio.me/).