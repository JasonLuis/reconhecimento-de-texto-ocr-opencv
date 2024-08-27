O pacote Pillow, mais conhecido como PIL (Python Imaging Library), é uma biblioteca para manipulação de imagens. Dentro da sua [documentação](https://pillow.readthedocs.io/en/stable/) é possível ter acesso a todos os módulos da biblioteca e a um “Handbook”, traduzindo livremente para livro de mão, que trás diversos tutoriais e conceitos que podem ser aplicados utilizando a biblioteca PIL.

O módulo utilizado no curso é o [Image](https://pillow.readthedocs.io/en/stable/reference/Image.html) que é usado para representar uma imagem PIL e podemos utilizar esse módulo não apenas para exibir a imagem, mas também para abrir e girá-la. 

Segundo a documentação, para carregar, girar 45º e depois exibir uma imagem podemos utilizar o código abaixo:

```
from PIL import Image
with Image.open("imagem.jpg") as im:
    im.rotate(45).show()
```

Outros módulos existem na biblioteca PIL e podem ser explorados na [documentação](https://pillow.readthedocs.io/en/stable/).