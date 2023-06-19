<h2 align="center"> PREVISÕES CLIMÁTICAS: </h2>
<h3 align="center"> O USO DE REDES NEURAIS ARTIFICIAIS PARA A IDENTIFICAÇÃO DA TEMPERATURA DA SUPERFÍCIE MARÍTIMA NO EVENTO CLIMÁTICO 'EL NIÑO'. </h3>

<p align="center"><img src="https://github.com/alicevk/RNAG-TCS/assets/106678040/6dbf7b82-edee-49d6-971b-01e098442efe" height="500"></p>
<h5 align="center"> Fig. 1. Mapa com demarcações das boias que são usadas para as medidas. Para a construção da figura, foi utilizada a biblioteca "Folium" em Python. [Fonte: Autoral] </h5>

<h3 align='center'> <i> Você já se questionou se as redes neurais podem nos auxiliar na predição de dados climáticos? </i> </h3>


## Resumo
<p align="justify">
Em condições normais no Oceano Pacífico, os ventos alísios - deslocamentos de massas de ar quente e úmido que se propagam em um ponto comum em direção às áreas de baixa pressão atmosférica da zona equatorial do globo terrestre; sopram para oeste ao longo do Equador, levando água quente da América do Sul para a Ásia. De modo a substituir essa água quente, ocorre um fenômeno oceanográfico denominado de ressurgência que consiste na subida de águas subsuperficiais, mais frias, muitas vezes ricas em nutrientes, para camadas superficiais no oceano, sendo um processo de suma relevância para a vida marinha e a pesca visto que promove uma maior quantidade de microorganismos que servem de alimento para os peixes. 'El Niño' é o fenômeno climático que dá nome quando essa situação típica não ocorre e resulta em um aquecimento incomum das águas superficiais no leste do Oceano Pacífico que impacta as temperaturas oceânicas, a velocidade e força das correntes oceânicas, além de afetar a saúde da pesca costeira e no clima local da Austrália à América do Sul. O evento do 'El Niño' ocorre irregularmente em intervalos de dois a sete anos. </p>
<p align="justify"> Essa temática apresenta uma díficil matriz de relações e comportamentos multifacetados devido a inconsistência temporal do fenômeno. Logo, de modo a aprender padrões e relações complexas do 'El Niño' a partir de um conjunto de dados históricos (1993-1998), aplica-se as Redes Neurais Artificiais (RNA's). Estrututalmente, as redes se baseiam em um processamento de dados similar ao processamento de informações de um cérebro humano que ocorrem por meio de um conjunto extremamente complexo de células, os neurônios, responsáveis pela tomada de decisão do raciocínio e corpo humano. Os neurônios são formados por dendritos – conjuntos de terminais de entrada, pelo corpo central, e pelos axônios – terminais de saídas. Assim, as RNA's serão utilizadas nosso projeto para predizer a temperatura da superfície marítma, nos permitindo ver como os atributos climáticos podem afetar a temperatura do mar e consequentemente, provocar o efeito do 'El Niño'. </p>
<p align="justify">
Ficou curioso? Bora acompanhar o nosso repositório :ok_woman: </p>

## Descrição do Projeto
<p align="justify">
O presente projeto busca realizar previsões da temperatura da superfície maritíma em eventos de 'El Niño', por meio de RNA's que se utilizam da biblioteca Pytorch. É aplicado uma função de entrada ReLU para a predição dos dados, devido a sua aplicabilidade para a previsão de eventos climáticos e o comportamento observado do conjunto de dados utilizado devido a análise pela matriz de covariância que analisou a relação entre o Targe (Temperatura da Superfície Marítima) e os Atributos (Condições climáticos como umidade e temperatura), o resultado do modelo será analisado por métricas de desempenho, como o Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE) e o Root Mean Square Error (RMSE), com a finalidade analisar o comportamento do modelo após seu treinamento.  </p>

<p align="justify"> O presente repositório foi elaborado pelos discentes: Alice Vitti Kageyama <a href="https://github.com/alicevk"> (@alicevk)</a>, Haziel Sixto Baden Sanchez Hermoza  <a href="https://github.com/hazielll"> (@hazielll)</a>,  Monyque Karoline de Paula Silva <a href="https://github.com/monocas"> (@monocas)</a> e Pedro Thomazelli  <a href="https://github.com/Thomazellinho"> (@Thomazellinho)</a>,  durante o terceiro semestre de graduação da Ilum - Escola de Ciência, para a disciplina de Redes Neurais e Algortítimos Genéticos. </p>

## De onde vem o nosso conjunto de dados?
<p align="justify"> Os nossos dados foram obtidos por boias, dispersas por todo Oceano Pacífico. Os dados foram armazenados pelo Laboratório Ambiental Marinho do Pacífico, fazendo parte dos 7 laboratórios do NOAA (Administração Nacional Oceânica e Atmosférica). Essas boias são lançadas em uma região denominada de "Regiões do El Niño" que podem ser categorizadas como Região 1 + 2, 3, 3.4, ou 4 e tem esses nomes devidos suas coordenadas geográficas, além de serem áreas específicas do Oceano Pacífico que são monitoradas para detectar e acompanhar os eventos do El Niño. </p>


<details><summary><h3><b> Como se guiar no nosso GitHub?</h3></b></summary>
<p align="justify">
 É bem simples!  O código que demonstra o treinamento dos dados com redes neurais artificais pode ser observado em um arquivo de formato ipynb com o nome de "main.ipynb" e pode ser aberto pelo jupyter notebook, vscode, g. colab ou em seu ambiente de desenvolvimento preferido. Por sua vez, os dados utilizados estão em um arquivo .csv denominado de "el nino.csv" em uma pasta denominada de "dados". </p>

</details>

## Ferramentas
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" width="40" height="40"/>  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" width="40" height="40"/> <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="40" height="40"/>


## Autores
<table>
  <tr>
    <td align="center"><a href="https://github.com/alicevk"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/107062251?v=4" width="100px;" alt=""/><br /><sub><b>Alice Kageyama </b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/hazielll"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/106745124?v=4" width="100px;" alt=""/><br /><sub><b>Haziel Hermoza </b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/monocas"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/106678040?v=4" width="100px;" alt=""/><br /><sub><b>Monyque Silva</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Thomazellinho"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/106624831?v=4" width="100px;" alt=""/><br /><sub><b> Pedro Thomazelli</b></sub></a><br /></td>
  </tr>
</table>
