# Repositório com notebooks e ferramentas relacionadas a visão computacional.

Projetos do repositório:

### 01 - Semelhança de Imagens:

Notebook onde falo um pouco sobre como detectar se duas imagens são iguais, diferentes ou semelhantes, sem usar nenhuma rede neural, apenas trabalhando com ferramentas simples e eficazes.

### 02 - Detecção de objetos:

Nesse notebook, a ideia principal é usar duas ferramentas poderosas de maneira conjunta para detectar objetos em imagens, usamos o Selective Search do OpenCV e a VGG19 do Keras de maneira conjunta, o Selective search para recortar a imagem em diversas outras imagens selecionadas pelo algoritmo, e usar essas novas imagens no VGG19, afim de fazer a deteção do objeto da imagem de maneira eficaz. 

### 03 - Deep_Leaning_e_construção_de_imagens:

Aqui nos usamos a tecnica de autoencoder variacional e usamos um dataset com mais de 20 mil imagens de face para fazer que o algoritmo aprenda a construir faces, faces de todas as etnias, idades e gêneros. Treinamos o modelo por apenas 20 minutos em um computador pessoal e já foi suficiente para ele aprender a reconstruir faces muito bem feitas.
