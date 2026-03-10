---
date: 2026-02-10
title: Documentação fácil com Docsy
linkTitle: Anúncio do Docsy
description: >
  O tema Docsy para Hugo permite que os responsáveis e contribuidores de um
  projeto se concentrem no conteúdo, sem terem de reinventar toda a
  infraestrutura de um website do zero
author: '[Patrice Chalin](https://github.com/chalin)'
resources:
  - src: '**.{png,jpg}'
    params:
      byline: Foto de Peter Xie do Pexels
    # https://www.pexels.com/photo/serene-ocean-sunset-with-rocky-silhouettes-35157036/
cSpell:ignore: imgproc Pexels
---

**Este é um exemplo típico de um artigo de blog que inclui imagens.**

O *front matter* especifica a data do artigo do blog, o seu título, uma breve
descrição que será apresentada na página principal do blog e o seu autor.

## Incluir imagens

Aqui está uma imagem que inclui um crédito e uma legenda.

{{< imgproc sunset Crop "500x300" >}}

Imagem recortada para 500x300

{{< /imgproc >}}

O *front matter* desta publicação especifica propriedades que serão atribuídas
a todos os recursos de imagem:

```yaml
resources:
  - src: '**.{png,jpg}'
    params:
      byline: Foto de Peter Xie do Pexels
```

To include the image in a page, specify its details like this:

```go-html-template
{{</* imgproc sunset Crop "500x300" */>}}
Image cropped to 500x300
{{</* /imgproc */>}}
```

The image will be rendered at the size and byline specified in the front matter.
