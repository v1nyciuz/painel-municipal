# Painel Municipal — protótipo

Protótipo navegável de um painel de inteligência de gestão para prefeituras: pesquisa mensal com amostra estatística, notas por área, serviço e região, comparativo com as capitais, mapa da cidade e acompanhamento do impacto das ações.

> Todos os dados, nomes de cidade e regiões são fictícios.

## Ver online

**https://v1nyciuz.github.io/painel-municipal/**

Publicado com GitHub Pages a partir da branch `main`: cada envio para a `main` atualiza o site em um ou dois minutos.

## Telas

- **Visão geral:** índice geral, resumo do mês gerado por IA, maiores quedas e altas, notas por área e evolução em 12 meses.
- **Serviços:** lista ou agrupado por área, com busca, filtros de área e situação, e ficha de cada serviço.
- **Comparativo:** a cidade contra as capitais por área, e aprovação da gestão (restrita ao gabinete).
- **Mapa:** regiões da cidade coloridas por nota ou por variação no mês, com painel da região.
- **Ações e impacto:** registro de ações e medição de antes e depois.

## Estrutura

Uma única página estática (`index.html`), sem build e sem dependências além da fonte Inter do Google Fonts. Para rodar localmente, basta abrir o arquivo no navegador.

## Próximos passos

- Separar dados de exemplo em `data/*.json`.
- Migrar para um framework (React ou Vue) quando o protótipo virar produto.
- Mapa real com limites dos bairros (IBGE ou prefeitura) usando MapLibre ou Leaflet.
