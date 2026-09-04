# O curso da Vereda

Guia rápido de apresentação da **Vereda**, a plataforma de gestão do
[Instituto Cerrados](https://vereda.cerrados.org).

**Publicado em:** https://yurisalmona.github.io/guia-vereda/

## O que é

Uma página só, autossuficiente, que apresenta a plataforma pela imagem da
própria vereda: a água aflora na nascente, corre pelo leito e chega à foz, e
cada trecho recebe do anterior. É essa continuidade que faz o orçamento saber
qual entrega ele paga, e a entrega saber qual objetivo ela serve.

Traz:

- o **diagrama do curso** inteiro, com os treze pontos e os afluentes;
- **cinco telas da plataforma**, renderizadas de verdade (não são capturas de
  tela: são os mesmos componentes, num quadro isolado);
- o **passo a passo** em nove etapas, do primeiro acesso à prestação de contas;
- **leitura em voz alta**, que usa a voz do aparelho e acompanha o texto.

## Os dados são de mentira

As telas mostram um projeto de demonstração — *Águas do Cerrado — Fase 2027* —
com valores redondos e três pessoas que não existem. Como esta página é
pública, nenhum número de projeto financiado e nenhum nome de equipe entra
nela. Quem gera essas telas é `scripts/vitrines-exemplo.tsx`, no repositório da
plataforma, e ele não toca em banco nenhum.

## Como atualizar

O `index.html` é gerado a partir das peças em `C:\projetos\vereda` (o guia, o
diagrama, o script e as vitrines). Para publicar uma versão nova, basta
substituir o arquivo e fazer commit: o GitHub Pages republica sozinho.
