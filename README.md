# Cena Unity 
Leonardo Macêdo e Lucas Noel
# Link para o projeto
https://drive.google.com/drive/folders/1k8xza7PdPU4IXTUcNMooaXildZhQksBg?usp=drive_link
# Descrição
Essa é uma cena no Unity 3D, onde tem um labirinto com vários obstáculos que o objetivo é chegar ao final sem bater e cair.
# Cena
Utilizamos GameObjects 3D, assests da loja e objetos modelados no Blender.

## GameObjects no Blender
 Pardedes e Teto - Chão - Espinhos - Portais - Pinos - Tunelzinho - Foice.
 
<img src = "img/blender.png" width = "470" height = "250">

## Assets da Loja
Setas - Pendûlos - Pneus - Obstáculos - Policoal - Arco - Letras (WIN) - Bichos De Pelúcia - Bandeira Final - Bola.

<img src = "img/loja.png" width = "470" height = "250">

## Unity
Luzes - Materiais.

<img src = "img/unity.png" width = "470" height = "250">

# Personagem
O personagem pegamos na loja de assets, adicionamos a bola em cima dele e a câmera para acompanha-lo enquanto anda.

<img src = "img/boneco.png" width = "470" height = "250">

<img src = "img/boneco1.png" width = "370" height = "300">

## Script
### Movimento
<img src = "img/movimenta.png" width = "650" height = "250">

Primeiro criamos uma variável para decidir a "velocidade" que o personagem andaria. Depois utilizamos o "if" para se uma tecla específica for clicada ele andaria para a frente, trás, direita e esquerda.

<img src = "img/movimenta1.png" width = "470" height = "500">

### Rotação
<img src = "img/roracao.png" width = "435" height = "205">

Primeiro criamos uma variável para decidir a "velocidade" que a câmera irá rotacionar. O código que faz a rotação captura o movimento do mouse horizontal e vertical, e aplica a rotação ao personagem com base na variável ´rotaçao´. A rotação ocorre no eixo horizontal (eixo X) do personagem.

<img src = "img/rotacao1.png" width = "285" height = "250">

### Escala
<img src = "img/escala.png" width = "405" height = "205">

Primeiro criamos três variáveis, 'minimo' e 'maximo' esses valores definem ate onde o personagem aumenta e diminui, e 'zoom' para a "velocidade" que roda o 'scroll'. O código calcula uma nova escala para o objeto tridimensional com base em um valor de rolagem e um fator de escala adicional. Em seguida, ele limita esse valor dentro de um intervalo específico. Por fim, atualiza a escala do objeto com o novo valor calculado, garantindo que os três eixos tenham a mesma escala.

<img src = "img/escala1.png" width = "325" height = "250">
