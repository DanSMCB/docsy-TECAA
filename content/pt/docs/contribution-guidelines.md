---
title: Diretrizes de Contribuição
description: Como contribuir para a documentação
weight: 10
---

{{% pageinfo color="info td-max-width-on-larger-screens mx-0" %}}

Estas diretrizes básicas de exemplo assumem que o teu site Docsy está a ser publicado usando
o Netlify e que os teus ficheiros estão armazenados no GitHub. Podes usar estas diretrizes "tal
como estão" ou adaptá-las com as tuas próprias instruções: por exemplo, outras opções de
implantação, informação sobre a estrutura de ficheiros do projeto de documentação, diretrizes
específicas de revisão, diretrizes de versionamento ou qualquer outra informação que os teus
utilizadores possam considerar útil ao atualizar o site.
[Kubeflow](https://github.com/kubeflow/website/blob/master/README.md) tem um excelente exemplo.

Não te esqueças de ligar ao teu próprio repositório de documentação em vez do nosso site de
exemplo! Além disso, garante que os utilizadores conseguem encontrar estas diretrizes a partir
do README do teu repositório: adiciona-as lá e faz link para elas nesta página, adiciona-as aqui
e faz link a partir do README, ou inclui em ambos os locais.

{{% /pageinfo %}}

Usamos o [Hugo](https://gohugo.io/) para formatar e gerar o nosso website, o
tema [Docsy](https://github.com/google/docsy) para estilização e estrutura do site,
e [Netlify](https://www.netlify.com/) para gerir a publicação do site.
O Hugo é um gerador de sites estáticos open-source que nos fornece templates,
organização de conteúdo numa estrutura de diretórios padrão e um motor de geração
de website. Escreves as páginas em Markdown (ou HTML se quiseres), e o Hugo
compila tudo num site.

Todas as submissões, incluindo as feitas por membros do projeto, requerem revisão.
Usamos pull requests no GitHub para este propósito. Consulta
[Ajuda do GitHub](https://help.github.com/articles/about-pull-requests/) para mais
informação sobre como usar pull requests.

## Início rápido com Netlify

Aqui está um guia rápido para atualizar a documentação. Assume que estás familiarizado
com o workflow do GitHub e que estás confortável a usar a pré-visualização automática das
atualizações da documentação:

1. Faz um fork do [repositório Goldydocs](https://github.com/google/docsy-example) no GitHub.
2. Faz as tuas alterações e envia um pull request (PR).
3. Se ainda não estiveres pronto para revisão, adiciona "WIP" ao nome do PR para indicar
   que está em progresso. (**Não** adiciones a propriedade do Hugo "draft = true" no front matter
   da página, porque isso impede a publicação automática da pré-visualização descrita no ponto seguinte.)
4. Espera que o workflow automático do PR execute algumas verificações. Quando estiver pronto,
   deverás ver um comentário como: **deploy/netlify — Deploy preview ready!**
5. Clica em **Details** à direita de "Deploy preview ready" para ver uma pré-visualização das
   tuas alterações.
6. Continua a atualizar a tua documentação e a enviar alterações até ficares satisfeito com o conteúdo.
7. Quando estiveres pronto para revisão, adiciona um comentário ao PR e remove quaisquer marcadores "WIP".

## Atualizar uma única página

Se encontraste algo que queres alterar enquanto usas a documentação,
o Docsy tem um atalho para ti:

1. Clica em **Edit this page** no canto superior direito da página.
2. Se ainda não tiveres um fork atualizado do repositório do projeto, serás
   solicitado a criar um — clica em **Fork this repository and propose changes** ou
   **Update your Fork** para obter uma versão atualizada do projeto para editar. A
   página apropriada no teu fork será exibida em modo de edição.
3. Segue o restante do processo do [Início rápido com Netlify](#início-rápido-com-netlify)
   acima para fazer, pré-visualizar e propor as tuas alterações.

## Pré-visualizar alterações localmente

Se quiseres executar o teu próprio servidor Hugo local para pré-visualizar as alterações
enquanto trabalhas:

1. Segue as instruções em [Começar](/docs/getting-started) para instalar o Hugo e quaisquer
   outras ferramentas necessárias. Precisarás pelo menos da **versão 0.146.0 do Hugo**
   (recomendamos usar a versão mais recente disponível), e deve ser a versão **extended**, que suporta SCSS.
2. Faz fork do [repositório Goldydocs](https://github.com/google/docsy-example) para o teu projeto,
   depois cria uma cópia local usando `git clone`.

   ```sh
   git clone --branch v0.12.0 --depth 1 https://github.com/google/docsy-example.git
   ```

1. Executa `hugo server` no diretório raiz do site. Por defeito, o site ficará
   disponível em http://localhost:1313/. Agora que estás a servir o site localmente,
   o Hugo irá observar alterações no conteúdo e atualizar automaticamente o site.
2. Continua com o workflow habitual do GitHub para editar ficheiros, fazer commit,
   enviar as alterações para o teu fork e criar um pull request.

## Criar um issue

Se encontraste um problema na documentação, mas não tens certeza de como o corrigir
por ti mesmo, cria um issue no
[repositório Goldydocs](https://github.com/google/docsy-example/issues). Também podes
criar um issue sobre uma página específica clicando no botão **Create Issue** no
canto superior direito da página.

## Recursos úteis

- [Guia do utilizador Docsy](https://www.docsy.dev/docs/): Tudo sobre Docsy, incluindo
  como gerir a navegação, a aparência e suporte multi-idioma.
- [Documentação Hugo](https://gohugo.io/documentation/): Referência completa para Hugo.
- [GitHub Hello World!](https://guides.github.com/activities/hello-world/): Uma introdução
  básica aos conceitos e workflow do GitHub.
