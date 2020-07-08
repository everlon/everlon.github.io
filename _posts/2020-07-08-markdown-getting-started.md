---
layout: post
title: "Afinal o que é Markdown?"
date: 2020-07-08 18:01:00 +0300
description: "Apresentando o Markdown que estou usando para escrever este blog."
img: dillinger.png
tags: [Markdown]
---

## Um guida rápido do que uso em Markdown.

Vou apresentar neste post como estou fazendo para escrever neste Blog. Uso o **Markdown**, uma forma mais interessante de escrever textos, principalmnente para nós programadores.

Resumindo: Markdown é uma forma de formatar um texto à partir de elementos de códigos fáceis. Criado por [John Gruber](https://daringfireball.net/projects/markdown/) em 2004, é utilizada em todo o mundo por programadores e escritores.

Diferente de escrever um texto em [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG), você escreverá seu texto adicionando a sintaxe para indicar quais partes quer formatar. Há quem diga que é muito mais produtivo (Eu), você só precisa decorar alguns caracteres para usar na hora de escrever.

Exemplificando, para indicar um cabeçalho, você adiciona o caracter de "tralha" ou "jogo-da-velha" antes dele (# Heading One). Ou, para deixar uma palavra em negrito, adicione dois asteriscos antes e depois dela (por exemplo, **negrito**). Pode demorar um pouco para se acostumar com a sintaxe do Markdown, mas com o tempo verá que será muito mais rápido.

Você pode usar um editor de texto simples para escrever em formato Markdown ou usar um dos muitos aplicaticos que já são baseados em Markdown.

### Por que usar o Markdown?

- Markdown pode ser usado para tudo: Criar sites(como este blog), documentos, notas, livros, apresentações, mensagens de email e documentação técnica.
- O Markdown é independente da plataforma. Você pode criar texto no formato Markdown em qualquer dispositivo executando qualquer sistema ou programa.
- Markdown é uma prova do futuro. Eu já tive que abrir textos em vários formatos do Microsoft World que mesmo no próprio World não abria por causa de versão. Sem falar de arquivos antigos que foi perdido por causa da versão do aplicativo que foi escrito. Com Markdown você fica livre de aplicativos.
- Markdown já esta em tudo que é lugar. Sites como o [Reddit](https://www.reddit.com/) e o [GitHub](https://github.com/) suportam o Markdown, e muitos aplicativos de desktop e baseados na Web o suportam.

### Como usá-lo?

Começar é o melhor meio de usar. Sério! Como é muito fácil de aprender e usar você pode abrir qualquer editor e sair escrevendo. Você pode usar um aplicativo online chamado [Dillinger](https://dillinger.io/) que lhe da a possibilidade de visualizar o que esta escrevendo usando Markdown em tempo real. Quer mais fácil que isso? Escreva do lado esquerdo e veja do lado direito. Deixe este site aberto enquanto lê este Post, assim já poderá testar a sintaxe. Depois você pode salvar com a extensão .md ou .markdown assim como outros formatos.

![Dillinger](dillinger.png)


### Onde usar?

Como disse, pode-se usar em muitos lugares como **Websites**, como Markdown foi projetado para web, muitas plataformas foram projetadas para ela, como esta do GitHub que estou usando. Se você quer uma maneira bem fácil de criar um site com arquivos Markdown, consulte [blot.im](https://blot.im/). É tão bobo que você usa sua conta do [Dropbox](https://www.dropbox.com/), criando uma pasta em seu computador e salvando seus arquivos em Markdown dentro dela eles já estão em seu site. Isso mesmo, simples assim.

Eu uso o [Jekyll](https://jekyllrb.com/) para criar este blog no [GitHub](https://github.com/).

Se você é um usuário do WordPress (uma pena mesmo), ficará feliz em saber que há suporte do Markdown para sites hospedados no [WordPress.com](https://en.support.wordpress.com/markdown/). Podem usar o [plugin Jetpack](https://jetpack.com/support/markdown/).

O Markdown não tem todos os recursos que um editor de texto como o Microsoft Word, mas o suficiente para criar documentos básicos até bem elaborados. Você pode usar alguns aplicativos de editção de texto para exportar seus documentos no formato Markdown para o formato de arquivo PDF ou HTML.

- Mac: [MacDown](https://macdown.uranusjr.com/) , [iA Writer](https://ia.net/writer) ou [Marked](https://marked2app.com/)
- iOS / Android: [iA Writer](https://ia.net/writer)
- Windows: [ghostwriter](https://wereturtle.github.io/ghostwriter/) ou [Markdown Monster](https://markdownmonster.west-wind.com/)
- Linux: [ReText](https://github.com/retext-project/retext) ou [ghostwriter](https://wereturtle.github.io/ghostwriter/)
- Web: [Dillinger](https://dillinger.io/) ou [StackEdit](https://stackedit.io/) (Estes dois muito semelhantes)

Markdown é a sintaxe ideal para fazer anotações. Busque pelos aplicativos abaixo:

- [Simplenote](https://simplenote.com/) e [Notable](https://notable.app/) são aplicativo gratuito de anotações disponível para todas as plataformas.
- [Boostnote](https://boostnote.io/) se autodenomina como um "aplicativo de anotações para programadores". Estou começando a usá-lo pelo fator multi-usuário.

Para escrever Livros e Documentação Técnicas é perfeito, experimente o [Leanpub](https://leanpub.com/), onde ele transforma seus arquivos no formato Markdown em livro eletrônico. Veja mais sobre esta parte também em [Kindle Direct Publishing](https://kdp.amazon.com/). Para documentação saiba mais com as aplicações:

- [Read the Docs](Read the Docs) você pode gerar um site de documentação a partir dos seus arquivos Markdown de código aberto.
- O [O VuePress](https://vuepress.vuejs.org/), [Docusaurus](https://docusaurus.io/) e o [MkDocs](https://www.mkdocs.org/) são geradores de sites estáticos rápido e simples, voltado para a documentação.

Agora os meus queridinhos são as apresentações com Markdown. Sim! Para você que faz palestras ou precisa apresentar suas idéias à equipe ou para o Boss, pode usar o Markdown para fazer aquela apresentação de forma muito mais rápida que o PowerPoint ou o Keynote. Veja mais sobre: O [Remark](https://remarkjs.com/) (seu lindo!), [Cleaver](https://jdan.github.io/cleaver/), [Deckset](https://www.decksetapp.com/) ou [Marked](https://marked2app.com/), estes dois últimos se usa Mac.

## Finalmente vamos ver como é a Sintáxe básica?

| Elemento | Sintaxe de Markdown |
| ----------- | ----------- |
| # Título de nível 1 | \# Heading level 1 |
| ## Título de nível 2 | \#\# Heading level 2 |
| ### Título de nível 3 | \#\#\# Heading level 3 |
| #### Título de nível 4 | \#\#\#\# Heading level 4 |
| ##### Título de nível 5 | \#\#\#\#\# Heading level 5 |
| ###### Título de nível 6 | \#\#\#\#\#\# Heading level 6 |
| Eu destaco em **texto em negrito**. | Eu destaco em \*\*texto em negrito\*\*. |
| Eu destaco em *texto em itálico*. | Eu destaco em \*Texto em itálico\*. |


### Títulos 

# H1
## H2
### H3

### Negrito

**Texto em negrito**

### Itálico

*Texto em itálico*

### Bloco de citação

> Pequeno bloco de citação.

### Lista ordenada

1. Primeiro item
2. Segunda item
3. Terceiro item

### Lista não ordenada

- Primeiro item
- Segundo item
- Terceiro item

### Códigos

`exemplo de código`

### Linha horizontal

---

### Link / Ligação

[title](https://www.example.com)

### Imagem

![alt text](image.jpg)







## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
