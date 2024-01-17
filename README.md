# PolygonAreaCalculator

Neste projeto, você usará programação orientada a objetos para criar a classe Rectangle, para um retângulo, e a classe Square, para um quadrado. A classe Square deve ser uma subclasse da classe Rectangle e herdar métodos e atributos.

Classe do retângulo
Quando um objeto de retângulo é criado, ele deve ser inicializado com atributos width (largura) e height (altura). A classe também deve conter os seguintes métodos:

set_width
set_height
get_area: retorna a área (width * height)
get_perimeter: retorna o perímetro (2 * width + 2 * height)
get_diagonal: retorna a diagonal ((width ** 2 + height ** 2) ** .5)
get_picture: retorna uma string que representa a forma usando as linhas de "*". O número de linhas deve ser igual à altura e o número de "*" em cada linha deve ser igual à largura. Deve haver uma nova linha (\n) no final de cada linha. Se a largura ou altura for maior do que 50, é preciso retornar a string: "Too big for picture." (Muito grande para a imagem).
get_amount_inside: Pega outra forma (quadrado ou retângulo) como um argumento. Retorna o número de vezes que a forma passada como argumento poderia caber dentro da forma (sem rotações). Por exemplo, um retângulo com uma largura de 4 e uma altura de 8 poderia caber em dois quadrados com lados de 4.
Além disso, se uma instância de um retângulo for representada como uma string, ela deve ter a seguinte aparência: Rectangle(width=5, height=10)

Classe do quadrado
A classe Square (Quadrado) deve ser uma subclasse de Rectangle (Retângulo). Quando um objeto Square é criado, um único comprimento lateral é passado. O método __init__ deve armazenar o comprimento do lado nos atributos width e height da classe Rectangle.

A classe Square deve ser capaz de acessar os métodos da classe Rectangle, mas também deve conter um método set_side. Se uma instância de Square for representada como uma string, ela deve ter a seguinte aparência: Square(side=9)

Além disso, os métodos set_width e set_height na classe Square devem definir a largura e a altura.

![image](https://github.com/AlexandrePMiranda/PolygonAreaCalculator/assets/135765440/8d19d9b8-d405-44b0-bf1c-61d15500621f)


![image](https://github.com/AlexandrePMiranda/PolygonAreaCalculator/assets/135765440/77f63203-809d-4b5e-b8b4-0277a9111a67)

