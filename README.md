# Redução de Dimensionalidade

As técnicas de redução de dimensionalidade são empregadas para reduzir o número de variáveis em um conjunto de dados, imagens ou outros tipos de informações. Elas são usadas para eliminar ruídos e informações irrelevantes, facilitando sua aplicação em contextos específicos, como treinamento de redes neurais, regressão linear, classificação entre outros.

## Reduzindo canais de cores em imagens

Uma técnica bastante utilizada em machine learning, sao tecnicas de redução de cores em imagens para treinamento de redes neurais. Uma imagem RGB possui três dimensões de cores, Red (R), Green (G) e Blue (B). Cada pixel da imagem contém essas três dimensões, portanto, isso aumenta o custo operacional para que a rede seja treinada tornando o processo mais lento. Por isso, sao usadas técnicas de redução de dimensionalidade para transformar imagens RGB em imagens com uma dimensão de cor.

**As cores não são importantes?**

É importante destacar que, o processo de reduzir as dimensões de cores de uma imagem deve se basear no contexto em que serão aplicadas. Para treinar uma rede neural para identificar carros ou motos, a cor não uma variável relevante nesse contexto, porém, para identificar placas de transito a cor é uma característica importante.
