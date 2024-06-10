# Animal-Pose-Estimation

O dataset consiste em imagens de diferentes animais, organizadas em pastas de acordo com as etiquetas dos animais. Para a análise específica, foi filtrado apenas as imagens etiquetadas como "antelope".
A distribuição do dataset é a seguinte:

Antelope: 152 imagens
Cada imagem foi redimensionada para um tamanho fixo de 100x100 pixels e convertida em um vetor de características. Isso resultou em uma matriz de dados de forma (152, 30000), onde cada linha representa uma imagem e cada coluna representa um pixel da imagem.

Insights da Análise Exploratória
PCA (Análise de Componentes Principais):

A PCA foi utilizada para reduzir a dimensionalidade dos dados de imagem, permitindo a visualização em um gráfico bidimensional.
No gráfico de PCA, cada ponto representa uma imagem de antílope. A dispersão dos pontos indica a variabilidade das imagens dentro da categoria de antílope.
Observa-se uma dispersão relativamente ampla, o que sugere que as imagens de antílope possuem variações significativas em termos de cores, texturas e outras características visuais.
Imagens Médias:

A imagem média foi calculada para todas as imagens de antílope. Isso ajuda a identificar as características visuais comuns e dominantes dentro desta categoria.
A imagem média representa uma antílope genérico com as características visuais mais frequentes entre todas as imagens da categoria. No entanto, devido à variação significativa nas imagens, a média pode parecer um pouco desfocada ou não clara.
