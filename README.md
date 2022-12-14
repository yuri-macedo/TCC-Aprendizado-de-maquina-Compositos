<h1 align="center"> 
Estimativa das propriedades mecânicas de compósitos utilizando algoritmos de aprendizado de máquina
</h1>
<p align="center">
<a href="https://colab.research.google.com/drive/1bmaxFWeC6xBBDyvjLAhj3bn_b4F2FJeS?usp=sharing">Google Colab</a>
</p>

<p align="justify">
A escolha do material a ser utilizado é uma importante etapa em um projeto de engenharia para verificar se as propriedades do mesmo atendem ou não os requisitos necessários. O processo para a determinação de tais propriedades envolve a elaboração de corpos de provas e a realização de ensaios mecânicos nos mesmos, envolvendo gastos de recursos e tempo (MERAYO, 2020). Nesse contexto, esse trabalho possui o objetivo de estimar as propriedades mecânicas de compósitos unidirecionais com matriz polimérica e reforçados com fibras de vidro e fibras de carbono, aplicando algoritmos de aprendizado de máquina, evitando ou reduzindo os gastos do processo. A metodologia aplicada neste trabalho envolve a obtenção dos dados, divisão dos mesmos em treino e teste, utilização dos dados nos algoritmos de aprendizado de máquina e a verificação desses resultados por meio de métricas pré-estabelecidas. Os algoritmos de aprendizado de máquina requerem alto volume de dados (milhares), enquanto é possível obter na literatura entre dezenas e centenas. Assim, somente com os dados experimentais disponíveis, não é possível realizar o treinamento dos algoritmos de aprendizado de máquina para obter uma solução satisfatória. Devido a essa escassez de dados experimentais disponíveis, foram produzidos dados através do método da homogeneização assintótica (VIGNOLI, 2019) para o treinamento dos algoritmos, e a utilização dos dados experimentais na validação. Assim, os dados obtidos pelo modelo são: o módulo de elasticidade e coeficiente de Poisson da matriz; módulos de elasticidade longitudinal e transversal, módulos de cisalhamento no plano e fora do plano e o coeficiente de Poisson no plano das fibras e da lâmina; e a fração volumétrica das fibras. A abordagem implementada considera como dados de entrada as propriedades da fibra, da matriz e a fração volumétrica, sendo a saída as propriedades da lâmina. Em relação aos algoritmos utilizados, foram implementados os modelos de regressão linear, árvore de decisão, florestas aleatórias e redes neurais. Para avaliar os resultados, foram utilizadas as métricas R2, MAE (erro médio absoluto), MSE (erro médio  quadrático), o RMSE (raiz do erro médio quadrático) e PE (erro percentual) e comparado as métricas entre os diferentes métodos. Os resultados obtidos variam de acordo com a propriedade desejada, modelo de aprendizado de máquina, e a métrica analisada, mas em geral apresentou resultados satisfatórios.
</p>

<p align="justify">
<b>Palavras-chaves:</b> aprendizado de máquina, materiais compósitos, propriedades mecânicas, redes neurais.
</p>

<h2>
Referências bibliográficas:
</h2>

<p align="justify">
MERAYO, David; RODRÍGUEZ-PRIETO, Alvaro; CAMACHO, Ana María. Prediction of Physical and Mechanical Properties for Metallic Materials Selection Using Big Data and Artificial Neural Networks. IEEE Access, v. 8, p. 13444-13456, 2020.

VIGNOLI, Lucas L. et al. Comparative analysis of micromechanical models for the elastic composite laminae. Composites Part B: Engineering, v. 174, p. 106961, 2019.
</p>
