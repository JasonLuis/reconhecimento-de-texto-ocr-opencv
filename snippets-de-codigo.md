O Google Colaboratory traz diversos recursos para que possamos utilizá-lo com widgets para interatividade do usuário. Um desses recursos é o utilizado em aula quando definimos o valor mínimo de confiança:

```
min_conf = 40 #@param {type: 'slider', min: 0, max: 100}
```

Para acessar outros parâmetros que podemos passar dentro de células de código no Colab, temos, na barra de menu, o quarto texto que é **Inserir**.Clicando nesse item, abrem-se opções do que podemos inserir no nosso notebook. Nós vamos clicar na quinta opção, chamada **Snippets de código**, que significa trechos de códigos, e também pode ser acessada com o comando **Ctrl+Alt+P**.

![Captura de tela “Reconhecimento de texto com OCR.ipynb”. O menu Inserir está aberto. Na parte inferior direita da tela, o botão Snippets de código está destacado com um retângulo vermelho sem preenchimento. ](https://cdn3.gnarususercontent.com.br/2663-visao-computacional/03/Aula3_cabecalho.png)

Assim que acessamos os Snippets de código, diversas opções irão aparecer na lateral direita da janela do Colab. A primeira opção é **Adding form fields** que adiciona um campo de formulário no nosso notebook. 

Essa seção lateral que aparece com os trechos de código mostra, na parte superior, uma lista com todos os snippets, e na parte inferior da coluna, uma breve descrição do que ele faz e o modelo de código que será adicionado. Ainda na parte inferior da coluna, alguns dos snippets trazem um link com exemplos, como o da imagem abaixo com diversos parâmetros. 

![Captura de tela do botão Snippets de Código na qual uma vez clicando nesse botão, foi aberta uma opção na parte inferior da tela chamada “Forms example” que está destacada com um retângulo vermelho sem preenchimento.](https://cdn3.gnarususercontent.com.br/2663-visao-computacional/03/Aula3_snippets.png) 

Vamos para o [**Forms example**](https://colab.research.google.com/notebooks/forms.ipynb#scrollTo=_B-89qQAolng) para entender melhor sobre parametrização dos códigos, nesse caso.

Dentro do [Forms](https://colab.research.google.com/notebooks/forms.ipynb#scrollTo=_B-89qQAolng) é possível ver diversos exemplos de uso do `#@param`, que deixa o código como um formulário. Seu uso pode ser extremamente útil em diversos casos, principalmente porque é possível esconder o código e deixar apenas o formulário feito, facilitando a inserção de dados ou a variação dos mesmos.

Além dos parâmetros encontrados no formulário fornecido na explicação, o Google Colaboratory também suporta o conjunto principal de widgets do Jupyter para fornecer interações entre o Python e o navegador. Esses widgets podem ser encontrados na [documentação da biblioteca Jupyter Widgets](https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Basics.html).