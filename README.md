# Códice · Proposta comercial para o varejo

Apresentação comercial em HTML (arquivo único) da **Códice**, displays inteligentes para
grandes resultados. Display as a Service para redes varejistas, dentro de um grupo com a
fábrica NeoBand e a 75 LAB.

**No ar:** https://projetos.75lab.com.br/neoband-retail-media/

## O racional

19 telas: primeiro quem é a empresa, depois a dor, a virada, o produto, a prova e a decisão.

| Bloco | Telas | Conteúdo |
|---|---|---|
| Abertura | 01 | A sua loja já é um veículo de mídia |
| Quem somos | 02 a 05 | Quem é a Códice, o grupo (NeoBand e 75 LAB), a operação e a plataforma |
| O que mudou | 06 a 07 | A verba desceu para o corredor e o custo de não agir |
| A solução | 08 a 11 | Display as a Service, quanto custa comprar sozinho, comprar ou assinar e o ciclo |
| O produto | 12 a 16 | Seis formatos, um slide por pacote (Essencial, Sense, Media) e a tecnologia |
| A prova | 17 a 18 | A conta em 6 meses e o efeito fiscal |
| Decisão | 19 | Simulador da rede com cronograma a partir de hoje |

A versão longa antiga continua em [`completo.html`](completo.html), na identidade NeoBand.

## Identidade Códice

- **Cores:** Midnight Navy `#061B49`, Electric Teal `#1DD4C8`, Intelligent Blue `#2F73FF`,
  Graphite `#4E4E50` e Off-white `#F5F7FA`, com o degradê navy, teal e azul.
- **Tipografia:** Exo 2 nos títulos e números, Inter no texto.
- **Elementos:** símbolo de três faces com barras de sensor, ondas, pontos de dados,
  conectores com anel, molduras de canto e grade modular.
- **Cursor:** moldura de quatro cantos com ponto de dado.

## Infográficos e interações

- Faixa de marcas atendidas pelo grupo rodando em duas linhas
- Operação em zigue-zague com seis fotos ligadas por uma linha com ponto em movimento
- Plataforma com sete telas do sistema que trocam sozinhas
- Iceberg do custo de comprar sozinho e barras do desembolso no primeiro mês
- Pacotes com pontos de destaque sobre a foto e medidor de camadas
- Órbita de tecnologia com troca automática lenta, pausa e clique para fixar
- Equação e cascata da conta em 6 meses
- Simulador: pacote, displays por loja, lojas, cota semanal, agenda vendida e período;
  receita, aluguel, lucro potencial, cronograma datado a partir do dia em que a página
  é aberta, lucro acumulado mês a mês e envio da simulação por e-mail ou WhatsApp

## Navegação

Setas, espaço, PageUp e PageDown, `Home`, `End`, `M` para o índice, `Esc` para fechar.
Swipe no celular. O link aceita âncora de tela: `#19` abre o simulador.

## Estrutura

```
index.html          apresentação de 19 telas (HTML, CSS e JS em arquivo único)
completo.html       versão longa antiga, identidade NeoBand
assets/foto-*       fotos da empresa e da operação
assets/sis-*        telas do sistema Códice em modo demonstração (dados fictícios)
assets/codice-*     logos, símbolo e suas partes, elementos gráficos da marca
assets/cfmt-*       renders dos seis formatos
```

## Fontes do conteúdo

Plano de negócio e modelo financeiro do projeto. Números de mercado do IAB Brasil /
Propmark (Digital Adspend 2026) e da ABRAS (Ranking 2026).
