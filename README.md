# Data_Wrangling_Preparanndo_Dados
Manipulação e limpeza de base de dados


Bem vindo!
Ao final deste notebook, você terá aprendido os fundamentos do Data Wrangling!

Conteúdo
Identificando e lidando com a falta de valores (missing data)
Identificando valores faltantes
Lidando com valores faltantes
Corrigindo o formato dos dados
Padronizando os dados
Normalizando os dados (centering/scaling)
Binning
Variável indicadora

PAssos para trabalhar com dados faltantes:

Identificar onde faltam dados
Lidar com os dados faltantes
Corrigir o formato dos dados
Identificando e lidando com valores faltantes
Identificando valores faltantes
Vamos converter o caractere "?" para NaN, o identificador de campo vazio (Not a Number) do Python
No dataset de carros, os dados perdidos (faltantes) vieram com um ponto de interrogação "?". Vamos substituir o "?" com NaN (Not a Number), que é o marcador padrão do Python para valores faltantes, por questões de velocidade computacional e conveniência. Vamos usar a seguinte função para isso:
