# NeoBand Retail Media · Proposta comercial para o varejo

Apresentação comercial em HTML (arquivo único) da solução **Display as a Service** da
NeoBand com plataforma da 75 LAB, dirigida a redes varejistas.

**No ar:** https://projetos.75lab.com.br/neoband-retail-media/

## O racional

23 telas em cinco atos, no arco clássico de um pitch comercial:
contexto, dor, custo de não agir, virada, produto, prova, confiança, plano e decisão.

| Ato | Telas | Conteúdo |
|---|---|---|
| Abertura | 01 | A sua loja já é um veículo de mídia |
| 01 · O que mudou | 02 a 04 | Migração da verba, o espaço despreparado e o custo de não agir |
| 02 · A virada | 05 a 07 | O insight, Display as a Service e o ciclo de quatro passos |
| 03 · O produto | 08 a 12 | Anatomia, seis formatos, três planos, zonas da loja e camada de inteligência |
| 04 · A prova | 13 a 18 | 104 cotas, simulação, curva do semestre, comprar x assinar e o painel |
| 05 · Decisão | 19 a 23 | Por que a NeoBand, governança, piloto, escala e CTA final |

## Infográficos animados

- Fluxo de migração da verba (paths SVG que se desenham)
- Anéis concêntricos expandindo no número de impacto
- Diagrama de três círculos sobrepostos (mobiliário, manutenção, inteligência)
- Ciclo de quatro nós com linha tracejada que se desenha e fecha
- Chamadas de anatomia com linhas que crescem até os rótulos
- Planta da loja com seis zonas pulsando
- Órbita de tecnologia em duas camadas
- Grade de 104 cotas que se acende conforme a ocupação
- Arco de ocupação, barras comparativas e curva de área do semestre
- Cadeia de governança, timeline do piloto e barras de escala

## Interações

- Seletor dos três planos (Essencial, Sense, Media)
- Galeria clicável com os seis formatos de display
- Planta da loja com seis zonas comerciais e índice de valor da cota
- Órbita com dez módulos de tecnologia clicáveis
- Simulador de ocupação (25%, 50%, 75%, 100%) que recalcula receita, arco e grade
- Índice navegável (tecla `M`), 32 botões de CTA, exportação em PDF

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
index.html          apresentação completa (HTML, CSS e JS em arquivo único)
assets/             logos, renders ambientados e renders do sistema modular
```

## Fontes do conteúdo

Plano de negócio `75LAB_NeoBand_Plano_de_Negocio` e modelo financeiro
`75LAB_NeoBand_Modelo_Financeiro`. Números de mercado do IAB Brasil / Propmark
(Digital Adspend 2026) e ABRAS (Ranking 2026).
