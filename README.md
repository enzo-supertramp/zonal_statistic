# zonal_statistic
bjetivo: Aplicar algoritmo de estatística zonal em rasters (precipitação) e vetores (rotas) dentro do município de São Paulo. 

O repositório divide-se em três etapas que foram desagregados em três arqivos .ipynb da sguinte maneira:
<br>**1ª Etapa:** Desagregar os arcos de cada rota obtida via TOMTOM extraindo seus shapefiles.
<br>**2ª Etapa:** Aplicar estatística zonal para cada um dos arcos de todas as rotas, associando os valores de refletividade-Z em cada segmento do arco no momento exato da vigem.
<br>**3ª Etapa:** Geração de uma planilha final em formato .xlxs com as informações agregadas de cada uma das rotas, contendo os valores de Precipitação Média Acumulada; Distância Percorrida Acumulada; Tempo de Viagem Acumulado; Nível de Precipitação Total
<br>
<br>Com os arquivos GeoTIFF, os valores da refletividade equivalente foram agregados às rotas obtidas, através de um algoritmo de estatística zonal que faz a conjunção de informações de dados raster (em grade) com dados vetoriais (polígonos)
