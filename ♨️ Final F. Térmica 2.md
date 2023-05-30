
### Organización de temas por capítulos:
---
1-Entalpía, entropía y energía de Gibbs  -  Focus 2, 3
2-Transiciones de fase de sustancias simples.  - Focus 4
3-Mezclas simples.  - Focus 5
4-Diagramas de fase de mezclas simples  - Focus 5
5-Equilibrio químico.   - Focus 6
6-Cinética química  - Focus 17
**Total de páginas:** Aprox 250 - 20 por día

**Fecha de examen:**  10 de Abril, faltan 12 días, contando descansos.

[[▶️ Focus 2 - Primera Ley Termodinámica]]
[[▶️ Focus 3 - Segunda y Tercera Ley]]
[[▶️ Focus 4 - Transformaciones físicas de sustancias puras]]
[[▶️ Focus 5 - Mezclas simples]]
[[▶️ Focus 6 - Equilibrio químico]]
[[▶️ Focus 17 Cinemática química]]

### Dudas
---
- ¿Por qué es válida la desigualdad de Clausius?
  ![[Pasted image 20230405005841.png]]
  (ES UN PRINCIPIO)
  - ¿Cómo el ciclo de carnot prueba que la entropía es una función de estado? Relacionar con irreversibilidad (NO ENTRA)
  - ¿Por qué la fusión o solidificación de un sólido a su punto de sufión es un proceso espontáneo que puede permanecer constante?  (TOMAR ENERGIA DE GIBBS O POTENCIAL QUIMICO)

### Preguntas cuestionarios (total 63)
---
#### Unidad 1

1 - Defina entalpía y muestre que coincide con el calor intercambiado si el proceso tiene lugar a presión constante
?
$H = U + pV$
Como **U, p y V son funciones de estado, H también lo es**. Como consecuencia, $\Delta H$ entre un par de estados inicial y final, es **independiente del recorrido** entre estos.
A partir de la definición de cambios infinitinesimales de la entalpía **H + dH**, la energía interna dU, y el **trabajo de expansión** $dw = -p dV$, llegamos a que $dH = dq_p$ y por lo tanto integrando $\Delta H = q_p$
<!--SR:!2023-05-02,9,210-->

2 - Relacione el cambio de entalpía para un gas ideal con su energía interna
?
En un gas ideal, H se relaciona con U de la siguiente manera
$H = U + pV = U + nRT$      Por lo que un cambio en la entalpía es
$\Delta H = \Delta U + \Delta n_{g}R T$
<!--SR:!2023-04-25,2,190-->

3 - Encuentre una expresión para el cambio de entalpía con la temperatura; utilice una fórmula empírica para el calor específico
?
Tenemos que $dH = C_{p}dT$, por lo que si integramos, llegamos a que $\Delta H = \int_{T_1}^{T_{2}}C_{p}dT$ que puede ser $\Delta H = C_{p} \Delta T$. Usamos la fórmula empírica $C_{p,m} = a + bT + c/T^2$
<!--SR:!2023-04-30,11,202-->

==4 - Defina estado estándar de una sustancia. Defina la entalpía estándar de una transición de fase y de una reacción química==
?
El **estado estándar** de una sustancia es a una T específica a 1 bar. 
La **entalpía estándar de una transición** se denota por $\Delta_{trs} Hº$ y es la cantidad de energía liberada o absorbida cuando se produce un cambio de fase a STP. El mismo valor de esta, es obtenido independendiente del recorrido.
La **entalpía de reacción estándar** es $\Delta_{r}Hº = \sum_{p} v H_{m}^{º}-\sum_{r} v H_{m}^{º}$
<!--SR:!2023-04-29,10,202-->

5 - Explique la ley de Hess y qué es la entalpía de formación estándar
?
La estalpía estándar de reacción es la suma de los valores de las reacciones individuales en los que la reacción se divice.
La **entalpía de formación estándar**, es la entalpía de reacción estándar para la formación del compuesto en su estado de referencia: su estado estable a 1 bar.
<!--SR:!2023-06-11,49,290-->

6 - Indique cómo varía la entalpía de una reacción con la Temperatura (ley de Kirchoff)
?
De $dH = C_{p}dT$ sale que cuando una sustancia es calentada desde $T_1$ hasta $T_2$, su entalpía cambia $H(T_{2})= H(T_{1}) + \int_{T_1}^{T_{2}}C_{p}dT$
Como esta ecuación aplica a cada sustancia en la reacción, la entalpía estándar de reacción cambia:  $\Delta_{r} H^º(T_{2})= \Delta_{r} H^º(T_{1}) + \int_{T_1}^{T_{2}}\Delta_{r}C_{p}^ºdT$
<!--SR:!2023-05-01,12,202-->

9 - Defina las energías de Helmholtz y Gibbs
?
La introducimos para obtener un criterio de espontaneidad. La **energía de Hemholtz** : $A = U - TS$
Y la **energía de Gibbs:**  $G = H - TS$   (Escribir diferenciales). El criterio de cambio espontáneo es que deben ser negativas.
<!--SR:!2023-04-25,2,190-->

11 - Defina la energía de Gibbs estándar de una reacción, y la energía de Gibbs estándar de formación
?
Combinamos entropías estándar y entalpías de reacción para formar
$\Delta_{r} G^{º}= \Delta_{r} H^{º} - T \Delta_{r}  S^º$   o su implementación práctica
$\Delta_{r} G^{º}= \sum_{p} v \Delta_{f} G^{º} - \sum_{r} v \Delta_{f} G^{º}$
Y la **energía estándar de Gibbs de formación** es la misma.
<!--SR:!2023-05-16,26,262-->

13 - Encuentre cómo varía la energía de Gibbs con la temperatura
?
A partir de $\large \bigg( \frac{\partial G}{\partial T}\bigg)_{p}= -S$  llegamos a que  $\large \bigg( \frac{\partial G/T}{\partial T}\bigg)_{p}= -H/T^2$    (ecuación de Gibbs-Helmholtz)
<!--SR:!2023-04-28,9,182-->

==14 - Encuentre cómo varía la energía de Gibbs con la presión==
?
Está esta expresión, y sino la que es igual al volumen
$\large G_{m}(p_{f}) = G_m(p_{i})+ (p_{f}- p_{i}) V_m$
Suponiendo que delta p no es muy graNDE
<!--SR:!2023-05-18,29,250-->

15 - Defina el potencial químico y encuentre su valor para un gas ideal
?
Es la capacidad del sistema de sufrir cambio químico. Para una sola sustancia,  $\large \mu = G_m$
Su valor **para un gas ideal** es $\large \mu = \mu^{º} + R T ln(\frac{p}{p^º})$
<!--SR:!2023-04-26,2,190-->

### Unidad 2
1 - Indique cómo varía el potencial químico cuando una sustancia pura pasa de la fase sólida a la líquida y posteriormemente a la gaseosa
?
El potencial químico se mantiene constante
<!--SR:!2023-05-21,32,277-->

2 - Explique los siguientes conceptos: punto de ebullición, punto de fusión, punto triple y punto crítico
?
El **punto de ebullición** normal, es a 1 atm, punto en donde la presión de vaporiación de un líquido es igual a la presión externa.
El **punto de fusión normal** es la temperatura de fusión a 1 atm
El **punto triple** es un punto en donde las condiciones permiten la coexistencia de las tres fases de la sustancia, y es característica de esta.
El **punto crítico** es tal que las fases líquida y gaseosa coexisten, se vuelven indistinguibles.
 
==4 - Cuál es el criterio termodinámico de equilibrio entre fases==
pENsarlo desde elp pot químico
<!--SR:!2023-04-28,5,217-->

5 - Explique cómo cambia el potencial químico frente a cambios de temperatura y presión
?
$\Large \Big( \frac{\partial \mu}{\partial T} \Big)_{p}= -S_m$
$\Large \Big( \frac{\partial \mu}{\partial p} \Big)_{T}= V_m$
<!--SR:!2023-04-27,5,217-->

7 - Deduzca la ecuación de Clausius-Clapeyron
?
A partir de la ecuación de Clapeyron $\Large \frac{\partial p}{\partial T} = \frac{\Delta_{trs} S}{\Delta_{trs} V}$   y que $\Large S_{vap} = \Delta_{vap} H / T$
Como el volumen molar de un gas es mucho mayor al de un líquido, $\Large \Delta_{vap} V \approx V_{m}(g)$, y que  $\Large \frac{dx}{x}= d \ln x$  entonces
$\Large \frac{d \ln p}{d T} = \frac{\Delta_{vap} H}{RT^2}$  (Ecuación de Clausius-Clapeyron)
<!--SR:!2023-04-25,1,157-->

==9 - Explique la clasificación de Ehrenfest de las transiciones de fase==
?
Transiciones de primer orden: Son aquellas transiciones de fase que implican un **cambio discontinuo** en la energía libre del sistema. Un cambio abrupto en alguna propiedad termodinámica, como la entalpía o el volumen, mientras que otras propiedades, como la energía interna y la entropía, son continuas. Ejemplos de transiciones de primer orden incluyen la solidificación del agua, la fusión del hielo y la evaporación del agua.
<!--SR:!2023-04-25,2,197-->

10 - Explique qué es la tensión superficial, y la diferencia entre una gota y una cavidad
?
El trabajo necesario para cambiar diferencial de superficie $\Large dw = \gamma d \sigma$   donde $\Large \gamma$ es la tensión superficial, el máximo trabajo puede ser identificado con la energía de Helmholtz.  La energía dA decrece si el diferencia de superficie decrece. Por lo que las superficies tienden a contraerse. 
La gota está rodeada de gas. La cavidad de líquido.
Las gotas tienden a coalecer más fácilmente.
<!--SR:!2023-04-27,4,197-->

13 - Explique qué es la capilaridad

### Unidad 3
==3 - Exprese el primer principio para el caso en que cambia la composición de la mezcla==
?
$d u=-p dV + TdS + \mu dn$
<!--SR:!2023-04-26,5,229-->

==4 - Explique la ecuación de Gibbs-Duhem== 
?
$\Large \sum_{j} n_{j} d \mu_{j}$
El potencial químico de un componente de la mezcla no puede cambiar independientemente de los potenciales químicos de los otros componentes
<!--SR:!2023-04-26,2,177-->

6 - Defina una solución ideal. ¿Cuánto vale el potencial químico?
?
Por la ley de Raoult, son las que obedecen $\large p_{A}= x_{A} p_A^{*}$
El potencial químico vale $\large \mu_{A}(1) = \mu_{A}^{*} (1) + R T \ln x_A$
<!--SR:!2023-04-26,2,157-->

7 - Explique la ley de Henry
?
Da una relación entre la presión de un soluto, y su fracción molar (concentración) en la mezcla
$C_p = k P_{gas}$
<!--SR:!2023-04-26,3,197-->

15 - Defina fase, componente y grado de libertad de un sistema
?
Fase: Parte homogénea, físicamente distinguible. Ej: Agua y aceite
Componente: Químicamente distinguible. Ej: Agua y sal
Grado de libertad:  Número de variables independientes para describir el sistema.
El grado de libertad está relacionado por lo gral con el número de fases y/o componentes
<!--SR:!2023-04-30,7,237-->

### Unidad 4
2 - Explique qué es la energía de Gibbs de una reacción, y cómo se vincula con los potenciales químicos. ¿Cuánto vale en equilibrio?
?
$\large \Delta_{r} G = \Big( \frac{\partial G}{\partial \xi} \Big)_{p,T}$
En donde $\large \xi$ es el grado de la reacción, la cantidad que se convirtió A/B
Se vincula a los potenciales químicos:
$\large \Delta_{r}G = \mu_{B} - \mu_{A}$
En equilibrio, vale cero
<!--SR:!2023-04-25,1,149-->

6 - Explique qué es la constante de equilibrio de una reacción, y vincúlela a las energías de Gibbs de formación de reactivos y productos
?
La constante de equilibrio, es el cociente de la actividad de los productos sobre la de los reactivos. Es una medida de la relación entre las concentraciones de reactivos y productos; en equilibrio termodinámico:  $\large \sum_{j} a_{j}^{v_{j}}$
En equilibrio,  $\large \Delta_{r}G = 0$    y  $\large \Delta_{r}G^º =  -R T \ln K$
<!--SR:!2023-04-25,2,189-->

7 - Encuentre cómo depende la constante de equilibrio con la presión del sistema. Explique el principio de Le Chatelier
?

9 - Explique qué es el pH y el pOH
?


### Unidad 5
---
1 - Defina velocidad y orden de una reacción
?
La velocidad de la reacción es proporcional a las concentraciones de los reactantes
$\large v = k_{r}[A][B]$
El orden es a la potencia que la especie es elevada,  (el orden es la suma total). Este valor se determina experimentalmente.
<!--SR:!2023-04-26,2,198-->

3 - Analice el caso de reacciones de primer orden, cerca del equilibrio
?
Tenemos dos conversiones
![[Pasted image 20230422192807.png]]
==Completar==
Llegamos a que la constante de equibrio es
![[Pasted image 20230422192909.png]]
<!--SR:!2023-04-25,1,182-->

5 - Explique cómo cambia la constante de una reacción con la temperatura
?
Para explicarlo, usaremos la ecuación de **Arrhenius**
![[Pasted image 20230422193018.png]]
![[Pasted image 20230422193055.png]]
<!--SR:!2023-04-26,2,198-->

6 - Defina qué es una reacción elemental
?
Es una reacción que ocurre en un simple paso, sin necesidad de saltos de transición
![[Pasted image 20230422194835.png]]
<!--SR:!2023-04-26,2,198-->




#FT2