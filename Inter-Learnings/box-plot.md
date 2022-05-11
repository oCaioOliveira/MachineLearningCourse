## Box Plot
Box plot é uma maneira gráfica de representar a alteração dos dados por meio de quartis (Q1 & Q3), um método alternativo ao histograma. 
Exemplo de box plot na imagem a seguir, onde Q1 e Q3 representam os quartis 1 e 3, LS e LI o Limite Superior e Inferior, e AIQ representa 
a Amplitude Interquartílica.<br><br>
![image](https://user-images.githubusercontent.com/54439337/167869522-38b32bfa-c2f1-4688-8a83-59c656ac9964.png)<br>
Fórmulas para calcular os Limites Superior e Inferior: LS = Q3 + 1.5 * (Q3 - Q1); LI = Q1 - 1.5 * (Q3 - Q1);<br><br>
Exemplo:<br>
Conjunto de dados = {-2, 3, 5, 8, 9, 11, 13, 14, 15, 17, 35}<br>
Mediana = 11;<br>
Q1 = 5;<br>
Q3 = 15;<br>
LS = 15 + 1.5 * (15 - 5) = 30;<br>
LI = 5 - 1.5 * (15 - 5) = -10;<br>
Gerando o seguinte box plot:<br><br>
![image](https://user-images.githubusercontent.com/54439337/167872314-81475e8f-efb6-42ad-9127-2b3443b4d8c5.png)<br>
Como o valor 35 do nosso conjunto de dados ele se tranforma em um outlier, representado por uma bolinha acima do LS. Outlier significa um ponto 
fora da curva, ou seja, um dado que está fora do LS ou LI, valores que podem atrapalhar a mostragem de dados.
