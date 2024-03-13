# Projeto Integrador 3 - Sistema de aferição de medição de proximidade para medição de vibração relativa de eixo

O sistema de medição de proximidade é empregado para determinar a distância até a superfície do aço AISI 4140, especialmente para a medição da vibração relativa do eixo. Nesse processo, quanto mais próxima a superfície, menor é a tensão DC gap medida, estabelecendo uma relação inversamente proporcional.

![](https://github.com/maiteluisaa/pi3/blob/main/figures/sensor.jpeg)

O sistema é composto por uma sonda, um cabo de extensão e um proxímetro. 

![](https://github.com/maiteluisaa/pi3/blob/main/figures/sensor.jpeg)

A curva do proxímetro é fornecida pelo datasheet do fabricante e adaptada às características do aço AISI 4140, geralmente apresenta um fator de escala incremental de aproximadamente 7.87 V/mm.

Atualmente, a verificação da precisão do sistema de medição é realizada manualmente. Este processo envolve o uso de um micrômetro para ajustar a distância até a superfície do aço AISI 4140, enquanto a tensão de saída do sensor é medida. Cerca de 10 medições são executadas dentro do intervalo estabelecido pelo fornecedor. Os dados coletados são então transferidos para uma planilha do Excel, onde são utilizados para gerar um gráfico e calcular o erro. É importante observar que o fator de escala incremental deve estar dentro de uma tolerância de 5%.

No entanto, este método de aferição é intensivo em mão de obra e sujeito a erros humanos. Portanto, este projeto visa automatizar o processo de aferição. Com a capacidade de conter até 20 proxímetros em um tubo gerador, o sistema automatizado eliminará a necessidade de intervenção manual para cada unidade. Isso resultará na redução significativa de erros humanos, otimização do tempo necessário para aferição e aumento da eficiência do trabalho, evitando tarefas repetitivas e monótonas para os trabalhadores.
