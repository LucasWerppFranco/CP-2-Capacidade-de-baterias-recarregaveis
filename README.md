# Lista de Exercícios sobre Capacidade das Baterias Recarregáveis

Este repositório contém uma lista de exercícios resolvidos sobre a capacidade e consumo de baterias recarregáveis, com foco no dimensionamento de tempo de operação, corrente e capacidade elétrica.

---

## Questão 01 - Cálculo de tempo de descarga

**Enunciado:**  
Uma bateria de chumbo-ácido de 12V e 7Ah é usada para alimentar um sistema de comunicação emergencial. Esse sistema possui três circuitos distintos funcionando simultaneamente: um rádio que consome 0,6A, um sistema de iluminação que consome 0,8A e um módulo Wi-Fi que consome 0,9A.

**Pergunta:**  
Considerando a descarga completa da bateria, por quanto tempo o sistema pode operar ininterruptamente?

**Cálculo:**  
Corrente total:  
\( i = 0,6A + 0,8A + 0,9A = 2,3A \)  
Capacidade da bateria:  
\( \Delta Q = 7Ah \)  

Tempo de operação:  
\( \Delta t = \frac{\Delta Q}{i} = \frac{7}{2,3} \approx 3,04h \)

---

## Questão 02 - Cálculo de tempo de descarga

**Enunciado:**  
Um Power Bank de 5V e 10.000mAh é utilizado para carregar um tablet que consome 1,2A. Contudo, há uma perda de eficiência de 15% no circuito de conversão de tensão e regulação interna.

**Pergunta:**  
Considerando essa perda, estime por quanto tempo o tablet poderá operar com esse Power Bank.

**Cálculo:**  
Capacidade efetiva considerando 15% de perda:  
\( \Delta Q = 10.000mAh \cdot (1 - 0,15) = 8500mAh = 8,5Ah \)

Corrente de consumo:  
\( i = 1,2A \)

Tempo de operação:  
\( \Delta t = \frac{\Delta Q}{i} = \frac{8,5}{1,2} \approx 7,08h \)

---

## Questão 03 - Cálculo da capacidade necessária da bateria

**Enunciado:**  
Um transmissor portátil de rádio opera com uma tensão de 9V e consome 300mA. Ele precisa funcionar por 6 horas sem recarga.

**Pergunta:**  
Qual deve ser a capacidade mínima da bateria, em mAh, para suportar essa operação?

**Cálculo:**  
\( \Delta Q = i \cdot \Delta t = 300mA \cdot 6h = 1800mAh \)

---

## Questão 04 - Cálculo da capacidade necessária da bateria

**Enunciado:**  
Você está desenvolvendo um protótipo alimentado por uma bateria Li-Ion de 3,7V, que consome 2A por 1h45min de uso contínuo.

**Pergunta:**  
Qual a capacidade mínima (em Ah) da bateria para suportar essa carga?

**Cálculo:**  
Tempo convertido:  
\( \Delta t = 1h45min = \frac{7}{4}h \)

\( \Delta Q = i \cdot \Delta t = 2A \cdot \frac{7}{4} = 3,5Ah \)

---

## Questão 05 - Corrente média consumida

**Enunciado:**  
Uma bateria de Li-Po de 11,1V e 2200mAh alimentou um drone por 18 minutos até descarregar completamente.

**Pergunta:**  
Qual foi a corrente média consumida (em A) durante o voo?

**Cálculo:**  
Tempo convertido:  
\( \Delta t = \frac{18}{60}h = 0,3h \)  
Capacidade da bateria:  
\( \Delta Q = 2200mAh = 2,2Ah \)

Corrente média:  
\( i = \frac{\Delta Q}{\Delta t} = \frac{2,2}{0,3} \approx 7,33A \)

---
