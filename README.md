# FoodGIS

FoodGIS é um site web de mapeamento voltado para estudantes universitários que desejam encontrar opções de alimentação próximas ao campus. A plataforma combina dados de OpenStreetMap com uma interface interativa em mapa para mostrar restaurantes, lanchonetes, cafeterias e bares em um raio de até 800 metros do ponto de interesse.

## O que o site faz

O projeto permite:

- identificar o campus mais próximo do usuário por GPS ou selecionar manualmente entre diferentes universidades;
- centralizar o mapa no campus escolhido e exibir o local em destaque;
- consultar estabelecimentos alimentícios na região por categoria, como restaurantes, fast food, cafés e bares;
- ordenar os resultados pela proximidade em relação ao campus;
- mostrar os pontos em um mapa interativo com marcadores e pop-ups;
- apresentar uma lista em formato de carrossel com cards dos locais mais próximos;
- carregar camadas personalizadas em formatos como KML, GeoJSON e Shapefile para análise complementar;
- ativar ou remover camadas adicionadas e manter a visualização organizada.

## Funcionalidades principais

### 1. Campus e localização

- O sistema tenta localizar o usuário automaticamente usando o GPS do navegador.
- Se o GPS não estiver disponível, o site usa um campus padrão.
- O usuário também pode escolher manualmente entre campus disponíveis.

### 2. Filtro de locais

- Os dados são buscados em tempo real usando a API Overpass do OpenStreetMap.
- O filtro permite visualizar apenas certos tipos de estabelecimento, como:
  - restaurantes;
  - fast food;
  - cafeterias;
  - bares/pubs.

### 3. Mapa interativo

- A aplicação usa Leaflet para renderizar o mapa.
- Existem opções de visualização em mapa de ruas e satélite.
- Cada ponto pode ser clicado para ver detalhes relevantes.

### 4. Carrossel de resultados

- Os estabelecimentos são exibidos em cards ordenados pela distância até o campus.
- Ao clicar em um card, o mapa foca no local correspondente.

### 5. Upload de camadas customizadas

- O usuário pode enviar arquivos geoespaciais e sobrepor informações personalizadas no mapa.
- Isso pode ser útil para representar rotas, pontos de interesse, áreas ou outros dados do entorno universitário.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Leaflet
- OpenStreetMap
- Overpass API
- shpjs
- leaflet-omnivore

## Como executar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. O site carregará o mapa e buscará os estabelecimentos próximos ao campus selecionado.


## Estrutura do projeto

- `index.html` — interface principal, estilos e lógica da aplicação.
- `README.md` — documentação do projeto.

## Integrantes

- Fernando Porto
- Fabiano Queiroz

## Observação

Este projeto foi desenvolvido como parte da disciplina de Engenharia de Software II, com foco em geolocalização, análise espacial e visualização de dados urbanos para suporte à comunidade universitária.
