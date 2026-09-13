# Códice · Proposta comercial para o varejo

Apresentação comercial em HTML (arquivo único) da **Códice**, displays inteligentes para
grandes resultados. Display as a Service para redes varejistas, com fabricação NeoBand e
plataforma e design da 75 LAB.

**No ar:** https://projetos.75lab.com.br/neoband-retail-media/

## O racional

12 telas no arco de um pitch comercial: contexto, dor, custo de não agir, virada, produto,
preço, tecnologia, prova, benefício fiscal, confiança e decisão.

| Ato | Telas | Conteúdo |
|---|---|---|
| Abertura | 01 | A sua loja já é um veículo de mídia |
| 01 · O que mudou | 02 a 03 | A verba desceu para o corredor, as quatro travas e o custo de não agir |
| 02 · A solução | 04 a 05 | Display as a Service e o ciclo de quatro passos |
| 03 · O produto | 06 a 08 | Seis formatos, os três planos e a tecnologia embarcada |
| 04 · A prova | 09 a 10 | 104 cotas, simulação de receita e o efeito fiscal |
| 05 · Decisão | 11 a 12 | Por que a Códice, governança, piloto e CTA |

A versão longa de 23 telas continua em [`completo.html`](completo.html), ainda na
identidade anterior (NeoBand).

## Identidade Códice

- **Cores:** Midnight Navy `#061B49` (principal), Electric Teal `#1DD4C8` (destaques),
  Intelligent Blue `#2F73FF` (dados), Graphite `#4E4E50` (apoio), Off-white `#F5F7FA`
  (base clara) e o degradê navy, teal e azul.
- **Tipografia:** Exo 2 nos títulos e números, Inter no texto.
- **Elementos:** símbolo de três faces com barras de sensor, ondas de sensor, pontos de
  dados, conectores com anel, molduras de canto e grade modular.
- **Cursor:** moldura de quatro cantos com ponto de dado, que se abre sobre o que é clicável.
- Telas alternam entre Midnight Navy e Off-white. Sem brilho, sem fundo quase preto.

## Infográficos animados

- Fluxo de verba com partículas correndo pelas linhas
- Símbolo da Códice montado face a face, com conectores até mobiliário, manutenção,
  inteligência e receita
- Ciclo de quatro passos com um ponto de dado percorrendo o circuito
- Órbita pontilhada em rotação, com conector que se desenha até o módulo escolhido
- Grade de 104 cotas, arco de ocupação e barras de receita
- Colunas empilhadas do efeito fiscal (custo efetivo e o que volta em imposto)
- Timeline do piloto com marcos pulsando

## Interações

- Galeria dos seis formatos, com moldura que se refaz a cada troca
- Seletor dos três planos
- Órbita com dez módulos de tecnologia clicáveis
- Simulador de ocupação (25%, 50%, 75%, 100%)
- Índice navegável (tecla `M`), botões de CTA, exportação em PDF

## Navegação

Setas, espaço, PageUp e PageDown, `Home`, `End`, `M` para o índice, `Esc` para fechar.
Swipe no celular. O link aceita âncora de tela: `#9` abre a tela 9.

## Estrutura

```
index.html          apresentação de 12 telas (HTML, CSS e JS em arquivo único)
completo.html       versão longa de 23 telas, identidade anterior
assets/codice-*     logos, símbolo e suas partes, elementos gráficos da marca
assets/cfmt-*       renders dos formatos, com as áreas de comunicação na paleta Códice
assets/app-*        renders de aplicação da marca
```

## Fontes do conteúdo

Plano de negócio e modelo financeiro do projeto. Números de mercado do IAB Brasil /
Propmark (Digital Adspend 2026) e da ABRAS (Ranking 2026).
