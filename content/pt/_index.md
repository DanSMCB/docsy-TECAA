---
title: Goldydocs
description: Avaliação da temperatura do mingau &mdash; na nuvem!
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Bem-vindo ao Goldydocs: Um exemplo e projeto inicial Docsy!"
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!--
  Quer uma capa sem imagem?
  Adicione o seguinte argumento ao shortcode blocks/cover:
    color="primary bg-gradient td-below-navbar"
-->

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

<!-- prettier-ignore -->
<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Saiba mais
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Obtenha o código
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

O Goldydocs fornece uma interface web única que mostra a temperatura do mingau, tamanho das cadeiras e maciez das camas! Você pode até descobrir quem tem comido **o seu** mingau.

(Infelizmente, o Goldydocs não é um projeto real, mas você pode usar este site como exemplo para criar seus próprios sites reais com [Docsy](https://docsy.dev))

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="Novas métricas de cadeiras!" icon="fa-lightbulb" %}}

A interface do Goldydocs agora mostra métricas de tamanho de cadeira por padrão.

Fique atento a futuras atualizações!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Contribuições bem-vindas!" icon="fab fa-github"
  url="https://github.com/google/docsy-example"
%}}

Temos um fluxo de trabalho de contribuições via [Pull Request](https://github.com/google/docsy-example/pulls) no **GitHub**. Novos usuários são sempre bem-vindos!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Siga-nos no X!" icon="fab fa-x-twitter"
  url="https://x.com/docsydocs"
%}}

Para anúncios de novas funcionalidades, novidades etc.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

Esta é a segunda seção

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

Esta é outra seção com alinhamento central

{{% /blocks/section %}}
