# Códice · Proposta comercial para o varejo

Apresentação comercial em HTML (arquivo único) da **Códice**, displays inteligentes para
grandes resultados. Display as a Service para redes varejistas, dentro de um grupo com a
fábrica NeoBand e a 75 LAB.

**No ar:** https://projetos.75lab.com.br/neoband-retail-media/

## O racional

12 telas, uma ideia por tela. Versões anteriores (13 e 19 telas) ficaram no histórico do Git.

| Bloco | Telas | Conteúdo |
|---|---|---|
| Abertura | 01 | A sua loja já é um veículo de mídia |
| O que mudou | 02 | A verba desceu para o corredor e o custo de não agir |
| Quem somos | 03 a 05 | O grupo (NeoBand e 75 LAB, marcas atendidas), o que é a Códice e a plataforma |
| Por que assinar | 06 | Comprar sozinho × assinar por R$ 499 por display por mês |
| O produto | 07 a 11 | Seis formatos e os três pacotes em 3D, e a tecnologia embarcada |
| Decisão | 12 | Simulador da rede (1, 6 ou 12 meses) com cronograma a partir de hoje |

Métrica da proposta: **R$ 499 por display por mês**. **1 cota = 1 semana de 1 display.**

## Identidade Códice

- **Cores:** Midnight Navy `#061B49`, Electric Teal `#1DD4C8`, Intelligent Blue `#2F73FF`,
  Graphite `#4E4E50` e Off-white `#F5F7FA`.
- **Tipografia:** Exo 2 nos títulos e números, Inter no texto.
- **Transição:** a cada troca de tela uma cortina com o símbolo e o logotipo da Códice.
- **Cursor:** moldura de quatro cantos com ponto de dado.

## Interações

- **Displays em 3D** (formatos e pacotes): arrastar para girar, com QR code que abre o mesmo
  display em realidade aumentada, em tamanho real, em `projetos.75lab.com.br/ar/codice-displays/`.
  Os modelos são os mesmos do repositório `caiquebecker75/ar` (pasta `codice-displays`).
- **Plataforma:** telas do sistema em modo demonstração que trocam sozinhas; clique para ver em
  tela cheia (setas trocam a tela, Esc fecha).
- **Tecnologia:** órbita com troca automática lenta, pausa e clique para fixar.
- **Simulador:** pacote, displays por loja, lojas, preço da cota, agenda vendida e período;
  receita, aluguel, lucro, cronograma datado a partir do dia em que a página é aberta e envio
  da simulação por e-mail ou WhatsApp.

## Navegação

Setas, espaço, PageUp e PageDown, `Home`, `End`, `M` para o índice, `Esc` para fechar.
Swipe no celular. O link aceita âncora de tela: `#12` abre o simulador.

## Estrutura

```
index.html          apresentação de 12 telas (HTML, CSS e JS em arquivo único)
completo.html       versão longa antiga, identidade NeoBand
assets/3d/          displays em .glb e posters (gerados no repositório de AR)
assets/vendor/      model-viewer 4.3.1 e gerador de QR code
assets/sis-*        telas do sistema Códice em modo demonstração (dados fictícios)
assets/codice-*     logos, símbolo e suas partes, elementos gráficos da marca
```

## Fontes do conteúdo

Plano de negócio e modelo financeiro do projeto. Números de mercado do IAB Brasil /
Propmark (Digital Adspend 2026).
