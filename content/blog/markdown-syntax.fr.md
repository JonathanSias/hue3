+++
author = "Hugo Auteurs"
title = "Guide de syntaxe de Markdown"
date = "2019-03-11"
description = "Exemple d'article présentant la syntaxe et le formatage de base de Markdown pour les éléments HTML."
tags = ["markdown", "css", "html", "themes"]
categories = ["themes", "syntax"]
images  = ["img/2014/04/pic02.jpg"]
aliases = ["migrate-from-jekyl"]
+++

Cet article propose un exemple de syntaxe de base de Markdown pouvant être utilisée dans les fichiers de contenu Hugo. Il indique également si les éléments HTML de base sont décorés avec CSS dans un thème Hugo.

<!--more-->

## Rubriques

Les éléments HTML `<h1>` —`<h6>`suivants représentent six niveaux d'en-tête de section. `<h1>` est le niveau de section le plus élevé tandis que `<h6>` est le plus bas.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraphe

Xerum, mais qui est un peu explicite sur le labo. Ace venitatiusda cum, voluptionse latur sitiae dolessi aut paristo nue en vol qui voluptate dolestendit péritin re plis aut quas inctum laceat est volestemque commosa comme date de fin, agent de base Quianimin porecus evelectur, cum que nis noll voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Vérifiez les résultats, notez les réponses, les rapports, les rapports, les chiffres, les chiffres, les chiffres, les chiffres, les chiffres, le temps, le temps, le temps, la durée, le temps, le temps, et le temps, puis le temps.

Itatur? Quiatae cullecum se souvient de manière automatique dans les archives non-formées. Sapicia est sinveli squiatum, noyau et que aut hariosam ex eat.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use _Markdown syntax_ within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

| Name  | Age |
| ----- | --- |
| Bob   | 27  |
| Alice | 23  |

#### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp; | Markdown&nbsp;&nbsp;&nbsp; | In&nbsp;&nbsp;&nbsp;                | Table  |
| ------------------------ | -------------------------- | ----------------------------------- | ------ |
| _italics_                | **bold**                   | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code` |

## Code Blocks

#### Code block with backticks

```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode

{{< highlight html >}}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

- List item
- Another item
- And another item

#### Nested list

- Item

1. First Sub-item
2. Second Sub-item

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
