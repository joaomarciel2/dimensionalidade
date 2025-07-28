# dimensionalidade
### Desafio DIO - Redução de Dimensionalidade em Imagens para Redes Neurais

Recentemente, mergulhei em um desafio prático da DIO de processamento de imagens utilizando Python, com o objetivo de aplicar técnicas de redução de dimensionalidade. Para isso, escolhi uma imagem colorida do renomado golfista Tiger Woods como ponto de partida. Minha tarefa consistiu em transformar essa imagem, originalmente rica em detalhes e composta por três canais de cor (vermelho, verde e azul), em versões mais simplificadas: uma em tons de cinza e, posteriormente, uma binarizada (preto e branco).

O primeiro passo foi converter a imagem colorida para tons de cinza. Essa etapa crucial representa uma significativa redução de dimensionalidade, pois condensa a informação de cor para apenas a intensidade luminosa de cada pixel. Em seguida, para otimizar a qualidade e preparar a imagem para a segmentação, apliquei um filtro de desfoque Gaussiano. Essa técnica é essencial para suavizar ruídos e realçar as características importantes, facilitando as etapas subsequentes de análise.

Por fim, utilizei o método de limiarização (thresholding) para gerar a versão binarizada da imagem. Aqui, os pixels são representados exclusivamente como preto ou branco, com base em um valor de corte predefinido. Esse processo resultou em uma representação de alta compressão, onde apenas a presença ou ausência de uma característica é destacada.
