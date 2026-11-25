# TechConnect

Site de uma empresa fictícia de tecnologia, desenvolvido para a disciplina Mundo do Trabalho. A página apresenta quatro serviços, três exemplos de projetos e um formulário de contato demonstrativo.

[Abrir o site TechConnect](https://g-infantini.github.io/Mundo-do-trabalho/)

## Tecnologias

- HTML5 para a estrutura da página e a validação dos campos.
- CSS3 com Grid, Flexbox e consultas de mídia para adaptar a página ao celular.
- SVG para as ilustrações dos serviços e projetos.

## Como foi feito

O site foi desenvolvido com apoio do ChatGPT. Um dos pedidos feitos durante a atividade foi receber primeiro o CSS e depois o HTML, com o código descompactado. Na versão publicada, o navegador carrega o [estilo](css/estilo.css) a partir da [página inicial](index.html).

## Ajustes feitos na organização

A página da empresa passou para a raiz do repositório. Antes, quem abria esse endereço podia cair em uma versão antiga do portfólio pessoal. As ilustrações ficam em `imagens/` e o portfólio tem seu [próprio endereço](https://g-infantini.github.io/Portfolio/). O formulário confirma a validação na própria página, sem colocar os valores digitados no endereço.

## Aprendizados do projeto

- Usar âncoras para relacionar cada item do menu a uma seção da mesma página.
- Combinar `required`, `minlength` e `type="email"` para validar o formulário no navegador. O envio de mensagens não faz parte da demonstração.
- Manter os caminhos de CSS e imagens relativos ao `index.html` para que o site funcione também no GitHub Pages.

Para executar localmente, baixe o projeto e abra `index.html` no navegador.

Atividade do Curso Técnico em Informática para Internet · SENAI Varginha · 2026
