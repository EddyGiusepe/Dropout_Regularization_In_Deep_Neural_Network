# Dropout Regularization In Deep Neural Network

Aqui aprenderemos a utilizar e a entender o uso do método Dropout. 

O arquivo "sonar.mines" contém 111 padrões obtidos através da projeção de sinais de sonar de um cilindro de metal em vários ângulos e sob várias condições. O arquivo "sonar.rocks" contém 97 padrões obtidos de rochas em condições semelhantes. O sinal de sonar transmitido é um chiado de frequência modulada, aumentando em frequência. O conjunto de dados contém sinais obtidos de uma variedade de ângulos de aspecto diferentes, abrangendo 90 graus para o cilindro e 180 graus para a rocha. 


Cada padrão é um conjunto de $60$ números no intervalo de $0.0$ a $1.0$. **Cada número representa a energia dentro de uma determinada banda de frequência, integrada ao longo (over) de um determinado período de tempo**. A abertura de integração para frequências mais altas ocorre mais tarde, uma vez que essas frequências são transmitidas mais tarde durante o chiado (chirp).


O rótulo associado a cada registro contém a letra ``R`` se o objeto for uma rocha e ``M`` se for uma mina (cilindro de metal). Os números nas etiquetas estão em ordem crescente de ângulo de aspecto, mas não codificam o ângulo diretamente.


O Dataset pode ser encontrado [aqui](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks).


Uma explicação em vídeo [pode ser assistido aqui](https://www.youtube.com/watch?v=lcI8ukTUEbo&list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO&index=20).



Thanks God!
