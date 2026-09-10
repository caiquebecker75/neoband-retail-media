# NeoBand Retail Media · Proposta comercial para o varejo

Apresentação comercial em HTML (arquivo único) da solução **Display as a Service** da
NeoBand com plataforma da 75 LAB, dirigida a redes varejistas.

**No ar:** https://projetos.75lab.com.br/neoband-retail-media/

## O racional

12 telas no arco clássico de um pitch comercial: contexto, dor, custo de não agir,
virada, produto, preço, tecnologia, prova, benefício fiscal, confiança e decisão.

| Ato | Telas | Conteúdo |
|---|---|---|
| Abertura | 01 | A sua loja já é um veículo de mídia |
| 01 · O que mudou | 02 a 03 | A verba desceu para o corredor, as quatro travas e o custo de não agir |
| 02 · A solução | 04 a 05 | Display as a Service e o ciclo de quatro passos |
| 03 · O produto | 06 a 08 | Seis formatos, os três planos e a tecnologia embarcada |
| 04 · A prova | 09 a 10 | 104 cotas, simulação de receita e o efeito fiscal |
| 05 · Decisão | 11 a 12 | Por que a NeoBand, governança, piloto e CTA |

A versão longa de 23 telas continua no repositório em
[`completo.html`](completo.html), para reunião de aprofundamento:
https://projetos.75lab.com.br/neoband-retail-media/completo.html

## Infográficos animados

- Fluxo de migração da verba (paths SVG que se desenham)
- Anéis concêntricos expandindo no número de impacto
- Diagrama de três círculos sobrepostos (mobiliário, manutenção, inteligência)
- Ciclo de quatro nós com linha tracejada que se desenha e fecha
- Órbita de tecnologia em duas camadas, com dez módulos clicáveis
- Grade de 104 cotas que se acende conforme a ocupação
- Arco de ocupação e barras comparativas de receita
- Colunas empilhadas do efeito fiscal (custo efetivo e o que volta em imposto)
- Timeline do piloto com marcos pulsando

## Interações

- Seletor dos três planos (Essencial, Sense, Media)
- Galeria clicável com os seis formatos de display
- Órbita com dez módulos de tecnologia embarcada clicáveis
- Simulador de ocupação (25%, 50%, 75%, 100%) que recalcula receita, arco e grade
- Índice navegável (tecla `M`), 20 botões de CTA, exportação em PDF

## Transições

Seis tipos, escolhidos por natureza de tela: `push`, `rise`, `zoom`, `iris`,
`curtain` e `blinds` (cortina de oito blocos nas telas de virada), sempre com
a varredura de raios vermelhos por cima.

## Navegação

Setas, espaço, PageUp e PageDown, `Home`, `End`, `M` para o índice, `Esc` para fechar.
Swipe no celular. O link aceita âncora de tela: `#8` abre a tela 8.

## Identidade

Sistema visual levantado dos próprios materiais da NeoBand, já que a marca não
publica manual: preto como tela dominante, areia `#E7D0B1` como campo quente,
vermelho `#D20A11` como energia, âmbar `#F3A800` e roxo `#66256D` em círculos
chapados sobrepostos.

Devices da marca em uso: o sparkle de 4 pontas (cursor e marcador dos eyebrows),
a explosão de raios vermelhos, os anéis concêntricos e o enquadramento de foto em
cartão de canto arredondado. Tipografia Maven Pro, a fonte da marca, com Roboto no
texto corrido. Assinatura 75 LAB no topo de todas as telas.

## Estrutura

```
index.html          apresentação de 12 telas (HTML, CSS e JS em arquivo único)
completo.html       versão longa de 23 telas, mesma identidade
assets/             logos, renders ambientados e renders do sistema modular
```

## Fontes do conteúdo

Plano de negócio `75LAB_NeoBand_Plano_de_Negocio` e modelo financeiro
`75LAB_NeoBand_Modelo_Financeiro`. Números de mercado do IAB Brasil / Propmark
(Digital Adspend 2026) e ABRAS (Ranking 2026).
