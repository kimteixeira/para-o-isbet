# Para o ISBET: novas parcerias em aprendizagem e estágio

Estudo independente, feito por conta própria, que usa **somente dados públicos** para mostrar como dados e automação podem ajudar uma entidade de aprendizagem e estágio a encontrar novas parcerias.

**Ver o site:** abra o `index.html` publicado pelo GitHub Pages (link na seção *About* deste repositório).

## O que tem no site
- **História interativa:** duas fontes de novas parcerias, empresas privadas que anunciam vagas de jovem aprendiz e órgãos públicos que contratam estágio e aprendizagem por licitação.
- **Radar de novas parcerias:** empresas por estado e cidade, filtros, prioridade e lista para baixar; licitações abertas e contratos públicos que terminam nos próximos 12 meses.
- **Exemplo de painel interno:** protótipo com **dados fictícios**, só para mostrar o formato.

## Como foi feito
- Coleta automática em PowerShell de páginas públicas de vagas (Gupy, BNE, InfoJobs, Vagas.com) e do Portal Nacional de Contratações Públicas (PNCP), respeitando o `robots.txt` de cada site. Nenhum dado de candidato é coletado.
- Limpeza e classificação em Python: remoção de repetições e de anúncios de intermediários, cruzamento e prioridade.
- Página única em HTML, CSS e JavaScript, sem bibliotecas externas: funciona sem internet, exceto os links para os sites de origem.

## Avisos
- Estudo independente, preparado por conta própria. Não é material oficial do ISBET nem de nenhuma instituição, e não usa logo nem material oficial.
- Os números mudam a cada atualização; a data da coleta aparece em cada tela.
- "Não aparece como parceira" quer dizer só que o nome não está entre as parceiras divulgadas no site da instituição; não é afirmação sobre contratos.

Autor: Kim Santos Teixeira
