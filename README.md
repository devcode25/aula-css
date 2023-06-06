# Boas vindas ao tema CSS!

### Vamos relembrar um pouco de HTML

HTML é uma abreviação de **Hyper Text Markup Language** (linguagem de marcação em hipertexto). Ou seja, não se trata de uma linguagem de programação, pois não tem lógica (algoritmos, processos etc). Ele cria a **estrutura** de uma página ou aplicação web, determinando a separação de layout e seu conteúdo.

Documentos .html possuem tags de estruturação básica:

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```

Internamente, as tags html possuem uma anatomia básica também:

```html
<nome-da-tag atributo="valor do atributo">
  conteúdo
</nome-da-tag>
```

Comentários em HTML:

```html
<!-- Isso é um comentário. Comentários em qualquer linguagem são pedaços de código que são ignorados na renderização (na leitura do computador), mas são úteis para entedimento humano -->
```


## Agora sim, partiu CSS!

CSS é abreviação de **Cascading Style Sheet** (folha de estilos em cascata). É a linguagem que define **estilos** para o HTML, portanto, não se trata de linguagem de programação. CSS tem "cascata" no nome, devido a sua forma de determinar a propriedade de um elemento - levando em consideração _hierarquia de seletores_ e de chamadas de estilo (inline, internal e external).

Para fazer o link de um arquivo .css em um documento .html, devemos inserir a tag <link> no <head> do documento, com o href do caminho do arquivo.

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body></body>
</html>
```

Dentro do arquivo .css, a anatomia é:

```css
seletor {
  propriedade: valor;
}
```

Exemplo:

```css
p {
  color: red;
}
```

Comentários em CSS:

```css
/* Sou um comentário CSS */
```

> **ATENÇÃO!**
> Não esqueçam de **indentar** o código! Isso ajuda na sua legibilidade, manutenção e colaboração com outros desenvolvedores.
> Para indentar, selecione a linha do código e aperte _tab_.

#### Classes e id

Classes e ids são atributos que podem ser inseridos em qualquer tag dentro da <body>. Eles são **atributos de nomeação**, sendo class muito usada para referência em CSS e id para Javascript (apesar de que há outras boas práticas no mercado atualmente).
Uma diferença entre os dois é que podem haver várias classes com o mesmo valor, ao passo que ids devem ser **únicos**.

#### Propriedades e tags

Verificar os arquivos de exercícios para vê-los em prática.

| HTML                                              | CSS                                                                                                       |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Tags de **estrutura**: !doctype, html, head, body | Propriedades de **background**: background-imagem, background-color                                       |
| Tags no **head**: meta (charset), title, link     | Propriedades de **texto**: text-align, font-family, font-size, text-decoration, font-size, text-transform |
| Tags de **divisão**: div                          | Propriedades de **layout**: width, margin, padding, display (inline-block)                                |
| Tags de **texto**: h1 ao h6, p                    | Propriedade de **cor**: color                                                                             |
| Tag de **link**: a                                | Propriedade de **decoração**: box-shadow, border                                                          |
| Tag de **imagem**: img                            |

-------
### Links úteis para estudo :)

- [Documentação HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML);
- [Documentação CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS);
- [Guia HTML para iniciantes](https://tableless.github.io/iniciantes/manual/html/);
- [Guia CSS para iniciantes](https://tableless.github.io/iniciantes/manual/css/);
- [Sobre HTML semântico](https://blog.geekhunter.com.br/voce-conhece-html-semantico/);
- [Tutorial sobre formulários HTML](https://www.homehost.com.br/blog/tutoriais/formulario-html/);
- [Sobre seletores CSS e pseudo-classes](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Getting_Started/Seletores);
- [Sobre a propriedade box-sizing](http://sergiolopes.org/css-box-sizing-border-box/);
- [Conceitos básicos de flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Conceitos_Basicos_do_Flexbox);
- [Calma senhora - ótimo site guia para estudos - desenvolvido por aluna da reprograma](https://calma-senhora.netlify.app/);

**Dicas extra**
- [Sobre Lorem Ipsum](https://pt.lipsum.com/);
- [Nomes de cores Html-CSS](https://htmlcolorcodes.com/color-names/);
- [Extensão conta-gotas, visualiza cores utilizadas pelo site no inspetor de código](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=pt);
- [Extensão para visualizar fontes usadas pelo site](https://chrome.google.com/webstore/detail/fonts-ninja/eljapbgkmlngdpckoiiibecpemleclhh);

**Dicas de links sobre Display flex**
 
- [tutorial MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
- [tutorial maujor](https://www.maujor.com/tutorial/propriedade-css-display.php)
- [tutorial w3schools](https://www.w3schools.com/cssref/pr_class_display.asp)
- [tutorial medium 1](https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-block-98480c987950)
- [tutorial medium 2](https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-inline-4ccb7b77371d#.jww2dont9)
- [tutorial css-tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)


**Sites úteis para buscar por imagens e layout**

- [Google Fonts](https://fonts.google.com/);
- [Flat UI Colors - paleta de cores](https://flatuicolors.com/);
- [Coolors - paleta de cores](https://coolors.co/);
- [FlatIcon - download de icones](https://www.flaticon.com/);
- [FontAwesome - download de icones dentre outros](https://fontawesome.com/icons?d=gallery);
- [Unsplash - site para download imagens](https://unsplash.com/);
- [Imagens de Fundo - site para download imagens](https://imagens-de-fundo.blogspot.com/);
- [FreePik - Site para download de imagens](https://br.freepik.com/);
- [Nappy - site com imagens de pessoas negras e marrons](https://www.nappy.co/);
- [Canva - banco de imagens - possível modificar e personalizá-las](https://www.canva.com/);
- [Pixabay - banco de imagens](https://pixabay.com/);
- [Negativespace - banco de imagens](https://negativespace.co/);
- [Pexels - banco de imagens](https://www.pexels.com/pt-br/);

**Vídeos pra quem gosta de vídeos - estudos**

- [Dica de tipografia - Largura do texto - 2min](https://www.youtube.com/watch?v=3C_9vIhmgm4);
- [Background simples mas pode ser que não](https://www.youtube.com/watch?v=kU8oIbe5hLs&list=PLirko8T4cEmx5eBb1-9j6T6Gl4aBtZ_5x&index=9);
- [Flexbox in 15 Minutes - em inglês](https://www.youtube.com/watch?v=fYq5PXgSsbE);
- [CSS Grid layout e Flexbox - um pouco mais avançado](https://www.youtube.com/watch?v=x-4z_u8LcGc);
- [Entenda o POSITION](https://www.youtube.com/watch?v=7svFaPgLCnc&t=61s);
- [Position in 9 Minutes - em inglês](https://www.youtube.com/watch?v=jx5jmI0UlXU);

**Jogos pra quem é de jogos - de CSS!! :)**

- [Flexbox Froggy - Jogo do Sapinho; pra aprender flexbox](https://flexboxfroggy.com/);
- [CSS Diner - Jantando com CSS; pra aprender sobre como usar seletores em CSS](https://flukeout.github.io/);
- [Flexbox Defense - Defendendo o CSS; outra forma de aprender flexbox](http://www.flexboxdefense.com/);

---
Bons estudos, galera!
