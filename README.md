# artigo-chocolate
 Um site feito com HTML e CSS, com um artigo falando sobre chocolate em geral, história, benefícios, tipos, etc. Texto gerado por IA.

 Tive a ideia de fazê-lo depois de fazer um curso sobre inteligência artificial na [Trybe](https://be.trybe.com.br/curso-ia-na-pratica/), onde vimos um IA que gera webpages automaticamente. Eu usei essa ferramenta no desenvolvimento deste site, porém usei apenas o visual de base e os textos, todo o código foi feito por mim.

## Tabela de conteúdos

- [artigo-chocolate](#artigo-chocolate)
  - [Tabela de conteúdos](#tabela-de-conteúdos)
  - [Visão Geral](#visão-geral)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [Meu processo](#meu-processo)
    - [Construído com](#construído-com)
    - [O que eu aprendi](#o-que-eu-aprendi)
    - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
    - [Recursos úteis](#recursos-úteis)
  - [Autora](#autora)
  - [Agradecimentos](#agradecimentos)


## Visão Geral


### Screenshot

![](./src/imagens/apresentacao/captura-de-tela.gif)


### Links

- URL do site: [https://beatrizvsgoncalves.github.io/artigo-chocolate/](https://beatrizvsgoncalves.github.io/artigo-chocolate/)


## Meu processo


### Construído com

- HTML5 semântica
- Flexbox
- Inteligência Artificial


### O que eu aprendi

No desenvolvimento deste site eu pude colocar em prática muito do que aprendi de HTLM e CSS e me colocar à prova com posicionamentos mais complexos do que já havia feito. 

Aprendi uma forma de estilizar os números de uma lista ordenada.

```css
.lista-receitas li {
	max-width: 23rem;
	counter-increment: num-list;
}

.lista-receitas li::before {
	background-color: rgba(228, 198, 166, 0.518);
	color: var(--font-color);
	border: 1px solid rgb(200, 181, 160);
	border-radius: 0.2rem;
	content: counter(num-list);
	font-size: 1.4rem;
	font-weight: bold;
	margin-right: 0.5rem;
	margin-left: -3rem;
	padding: 0.3rem 0.7rem;
}
```

### Desenvolvimento contínuo

Gostei muito de fazer esse site, principalmente porque foi o primeiro que fiz de minha própria iniciativa, não fazendo parte de um curso ou desafio. O que mais gostei foi de trabalhar na responsividade, queria que fosse responsivo ao máximo que podia e acho que consegui cumprir isso. Descobri que essa é a parte que mais gosto no desenvolvimento de um site, é muito satisfatório ver seu site sendo capaz de se ajustar a qualquer tamanho de tela. Demorei um pouco (4 dias), mas aproveitei bastante e fui com calma. Estou muito satisfeita com ele. 


### Recursos úteis

- [KADUNEW](https://www.kadunew.com/blog/css/personalizando-listas-ordenadas-com-pseudo-elemento-before) - Esse artigo me ajudou na hora de estilizar os números da lista ordenada.

- O que mais me ajudou neste projeto foi o ChatGPT, peguei várias dicas com ele kk.


## Autora

- Github - [beatrizvsgoncalves](https://github.com/beatrizvsgoncalves)
- LinkedIn - [beatriz-vs-goncalves](https://www.linkedin.com/in/beatriz-vs-goncalves/)


## Agradecimentos

Meus agradecimentos a Trybe pela indicação de ótimas ferramentas IA no curso [IA na Prática](https://be.trybe.com.br/curso-ia-na-pratica/).
A IA [Gamma](https://gamma.app/) pelo exemplo de página.
E ao [Kadu](https://www.kadunew.com/blog/carlos-eduardo) o autor do artigo que ensina a estilizar listas ordenadas. 
