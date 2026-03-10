---
title: Página de Exemplo
date: 2017-01-05
description: >
  Uma breve descrição introdutória sobre esta página de conteúdo. Pode estar em
  **negrito** ou _itálico_ e pode ser dividida em vários parágrafos.
categories: [Exemplos]
tags: [teste, exemplo, docs]
---

{{% pageinfo color="warning td-max-width-on-larger-screens mx-0" %}}

Esta é uma página de exemplo. Substitui-a pelo teu próprio conteúdo.

{{% /pageinfo %}}

O texto pode estar em **negrito**, _itálico_ ou ~~riscado~~. As
[ligações](https://gohugo.io) devem aparecer a azul e sem sublinhado
(exceto quando se passa o rato por cima).

Deve existir espaço entre parágrafos. Este texto serve apenas como
conteúdo fictício para demonstrar estilos e formatação dentro da página.

> Não deve existir margem acima desta primeira frase.
>
> As citações (blockquote) devem aparecer num cinzento mais claro com
> uma barra à esquerda na cor secundária.
>
> Não deve existir margem abaixo desta última frase.

## Primeiro Cabeçalho 2

Este é um parágrafo normal após um cabeçalho. Este texto existe apenas
para demonstrar como o conteúdo aparece dentro da página.

Em ecrãs grandes, os parágrafos e cabeçalhos não devem ocupar toda
a largura do contentor, mas tabelas, blocos de código e elementos
semelhantes devem ocupar toda a largura.

## Segundo Cabeçalho 2

> Este é um bloco de citação após um cabeçalho. Serve para demonstrar
> como as citações são apresentadas no tema.

### Cabeçalho 3

```text
Este é um bloco de código após um cabeçalho.
```

Texto de exemplo para demonstrar conteúdo e formatação dentro da página.

#### Cabeçalho 4

- Esta é uma lista não ordenada após um cabeçalho.
- Esta é uma lista não ordenada após um cabeçalho.
- Esta é uma lista não ordenada após um cabeçalho.

##### Cabeçalho 5

1. Esta é uma lista ordenada após um cabeçalho.
2. Esta é uma lista ordenada após um cabeçalho.
3. Esta é uma lista ordenada após um cabeçalho.

###### Cabeçalho 6

| O que | Segue |
|-------|-------|
| Uma tabela | Um cabeçalho |
| Uma tabela | Um cabeçalho |
| Uma tabela | Um cabeçalho |

---

Existe uma linha horizontal acima e abaixo deste texto.

---

Aqui está uma lista não ordenada:

- Liverpool F.C.
- Chelsea F.C.
- Manchester United F.C.

E uma lista ordenada:

1. Michael Brecker
2. Seamus Blake
3. Branford Marsalis

E uma lista de tarefas não ordenada:

- [x] Criar um tema Hugo
- [x] Adicionar listas de tarefas
- [ ] Tirar férias

E uma lista de tarefas "mista":

- [ ] Fazer as malas
- ?
- [ ] Viajar!

E uma lista aninhada:

- Jackson 5
  - Michael
  - Tito
  - Jackie
  - Marlon
  - Jermaine
- TMNT
  - Leonardo
  - Michelangelo
  - Donatello
  - Raphael

Listas de definição podem ser usadas com a sintaxe Markdown. Os cabeçalhos das definições estão a negrito.

Nome : Godzilla

Nascimento : 1952

Local de nascimento : Japão

Cor : Verde

---

As tabelas devem ter cabeçalhos a negrito e linhas alternadas sombreadas.

| Artista | Álbum | Ano |
|---------|-------|-----|
| Michael Jackson | Thriller | 1982 |
| Prince | Purple Rain | 1984 |
| Beastie Boys | License to Ill | 1986 |

Se uma tabela for demasiado larga, deve permitir deslocamento horizontal.

| Artista | Álbum | Ano | Editora | Prémios | Músicas |
|---------|-------|-----|---------|--------|--------|
| Michael Jackson | Thriller | 1982 | Epic Records | Grammy para Álbum do Ano, American Music Award para Álbum Pop/Rock Favorito, American Music Award para Álbum Soul/R&B Favorito, Brit Award para Álbum Mais Vendido, Grammy para Melhor Engenharia de Álbum (não clássico) | Wanna Be Startin' Somethin', Baby Be Mine, The Girl Is Mine, Thriller, Beat It, Billie Jean, Human Nature, P.Y.T. (Pretty Young Thing), The Lady in My Life |
| Prince | Purple Rain | 1984 | Warner Brothers Records | Grammy para Melhor Banda Sonora para Media Visual, American Music Award para Álbum Pop/Rock Favorito, American Music Award para Álbum Soul/R&B Favorito, Brit Award para Melhor Banda Sonora/Gravação de Elenco, Grammy para Melhor Performance Rock de Duo ou Grupo com Vocal | Let's Go Crazy, Take Me With U, The Beautiful Ones, Computer Blue, Darling Nikki, When Doves Cry, I Would Die 4 U, Baby I'm a Star, Purple Rain |
| Beastie Boys | License to Ill | 1986 | Mercury Records | sem prémios mas esta célula da tabela é larga | Rhymin & Stealin, The New Style, She's Crafty, Posse in Effect, Slow Ride, Girls, (You Gotta) Fight for Your Right, No Sleep Till Brooklyn, Paul Revere, Hold It Now, Hit It, Brass Monkey, Slow and Low, Time to Get Ill |

---

Trechos de código como `var foo = "bar";` podem ser apresentados inline.

Também, `isto deve alinhar verticalmente` ~~`com isto`~~ ~~e isto~~.

O código também pode ser apresentado num bloco.

| Linguagem   | Código               |
| ---------- | ------------------ |
| Javascript | `var foo = "bar";` |
| Ruby       | `foo = "bar"{`     |

---

Imagens pequenas devem ser apresentadas no seu tamanho real.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg/240px-Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg)

Imagens grandes devem sempre ajustar-se ao contentor de conteúdo.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg/1024px-Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg)

_A fotografia acima do rebento de abeto Picea abies com botões de folhagem: Bjørn Erik Pedersen, CC-BY-SA._

## Componentes

### Alertas em sintaxe Markdown

> [!NB] Isto é um alerta.

> [!SECONDARY] Título do alerta
>
> Este é um alerta com título.

> [!TIP]
>
> Este é um alerta de sucesso.

> [!WARNING]
>
> Isto é um aviso!

> [!DANGER] Perigo!
>
> Este é um alerta de perigo com título!

### Shortcode de alerta

{{% alert %}} Isto é um alerta. {{% /alert %}}

{{% alert title="Título do alerta" color="secondary" %}} Isto é um alerta com um título. {{% /alert %}}

{{% alert color="success" %}} Este é um alerta de sucesso. {{% /alert %}}

{{% alert color="warning" %}} Isto é um aviso! {{% /alert %}}

{{% alert title="Perigo!" color="danger" %}} Este é um alerta de perigo com um título! {{% /alert %}}

## Outro Cabeçalho

Adiciona algumas secções aqui para veres como fica o índice (ToC). Este texto é fictício para demonstrar formatação: Bacon ipsum dolor sit amet t-bone doner shank drumstick, pork belly porchetta chuck sausage brisket ham hock rump pig. Chuck kielbasa leberkas, pork bresaola ham hock filet mignon cow shoulder short ribs biltong.

### Este Documento

Texto de exemplo em latim fictício: Inguina genus: Anaphen post: lingua violente voce suae meus aetate diversi. Orbis unam nec flammaeque status deam Silenum erat et a ferrea. Excitus rigidum ait: vestro et Herculis convicia: nitidae deseruit coniuge Proteaque adiciam _eripitur_? Sitim noceat signa _probat quidem_. Sua longis _fugatis_ quidem genae.

### Contagem de Pixels

Mais texto de exemplo para demonstrar layout: Tilde photo booth wayfarers cliche lomo intelligentsia man braid kombucha vaporware farm-to-table mixtape portland. PBR&B pickled cornhole ugh try-hard ethical subway tile. Fixie paleo intelligentsia pabst. Ennui waistcoat vinyl gochujang. Poutine salvia authentic affogato, chambray lumbersexual shabby chic.

### Informação de Contacto

Texto fictício para contacto: Plaid hell of cred microdosing, succulents tilde pour-over. Offal shabby chic 3 wolf moon blue bottle raw denim normcore poutine pork belly.

### Ligações Externas

Mais texto de demonstração: Stumptown PBR&B keytar plaid street art, forage XOXO pitchfork selvage affogato green juice listicle pickled everyday carry hashtag. Organic sustainable letterpress sartorial scenester intelligentsia swag bushwick. Put a bird on it stumptown neutra locavore. IPhone typewriter messenger bag narwhal. Ennui cold-pressed seitan flannel keytar, single-origin coffee adaptogen occupy yuccie williamsburg chillwave shoreditch forage waistcoat.

```text
Este é o último elemento da página e não deve existir margem abaixo.
```
