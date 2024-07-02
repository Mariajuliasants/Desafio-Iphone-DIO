<h1 align="center"> Desafio Iphone DIO</h1>

<h3 align="left"> Modelagem e Diagramação UML do Componente iPhone</h3>
<p align="left">
	<b><i>
Este repositório contém a implementação de um desafio proposto pela Digital Innovation One (DIO).
Este projeto utiliza princípios de programação orientada a objetos e técnicas de modelagem UML para criar uma estrutura que permite que um dispositivo iPhone desempenhe três papéis distintos e cruciais: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.
    
  </i></b>
</p>

## Diagrama UML
<h3 align="center">
    <img src="https://github.com/Mariajuliasants/Desafio-Iphone-DIO/assets/141661649/a6fcb710-c24c-4e9c-92a6-48ffc773f766" >
  </a>
</h3>

## Explicação do Diagrama UML
O diagrama UML a ima ilustra a modelagem do componente iPhone. Este diagrama foi elaborado para demonstrar como as diferentes funcionalidades do iPhone podem ser estruturadas utilizando princípios de programação orientada a objetos.

### Interfaces

  ### `ReprodutorMusical`

`tocar()`
`pausar()`
`selecionarMusica(String musica)`


A interface `ReprodutorMusical` define métodos para tocar, pausar e selecionar músicas, representando a funcionalidade de reprodutor musical do iPhone, As classes que implementam essa interface são capazes de reproduzir músicas.

### `AparelhoTelefonico`
`ligar(String numero)`
`atender()`
`iniciarCorreioVoz()`

A interface `AparelhoTelefonico` define métodos para ligar, atender chamadas e iniciar o correio de voz, as classes que implementam essa interface podem funcionar como dispositivos telefônicos. representando a funcionalidade de telefone do iPhone.


### `NavegadorInternet`

`exibirPagina(String url)`
`+adicionarNovaAba()`
`atualizarPagina()`
A interface  `NavegadorInternet` define métodos para a navegação na web exibir páginas web, como adicionar novas abas e atualizar páginas, representando a funcionalidade de navegador de internet do iPhone.

### Classe principal
### `Iphone`

A classe central, `iPhone`, implementa todas as interfaces mencionadas acima, consolidando as funcionalidades de reprodutor musical, telefone e navegador de internet em um único componente.

<p align="center"> Desenvolvido por Maria Júlia Santos ✨ </p>
