                                                                 -Como Remover a Tatuagem do Kratos
                                                                 
Esse é um tipo de mod fácil de se fazer mas bem interessante e útil. no Meu canal eu fiz um video mostrando o processo: https://youtu.be/66Jw9D6FSt4?si=EKmBaxuW3KOEgRZj
Aqui eu vou dizer exatamente o que eu fiz. então, vamos lá;

- Parte 1

     Para começar, você deve abrir seu Gow Browser e ir até o Wad do Hero (Kratos). você escolhe qual deseja tirar a tatuagem.
     próximo passo, baixe o hero_0 "esse é o modelo bruto, sem texturas, ele é totalmente branco.) com ele em mãos, jogue no HxD, você verá o binario dele.
      com tudo isso, você deve olhar no Gow Browser a parte que começa a ter tatuagem, sabendo disso, no HxD você aperta CTRL+F, Valores Hexadecimais, tudo, coloca 0e 00 00 00 02. isso é a Flag de Parte de modelo que você viu no Browser.
       com tudo isso, vá na parte que tem a tatuagem, se for por exemplo a parte 9, você vai descendo e verá colunas de 80 80 80 80, isso é cor em HeX, RGBA. no Caso do Kratos Normal, a cor vermelha da Tatuagem é 4C 1E 24 80. basta subistiuit por 80.
        Para subistituir corretamente, você deve modificar depois do 6E e antes do 01, vou mostrar em uma imagem>>

   <img width="636" height="378" alt="image" src="https://github.com/user-attachments/assets/3da5df92-69ea-445b-b41c-46e2b75726e8" />

   começa do 6e e acaba no 01, se passar deles, o jogo trava.

- esse é um tutorial bem fácil e simples, mas legal de se fazer.
