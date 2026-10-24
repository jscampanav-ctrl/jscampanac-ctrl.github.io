# Teorema de Conservación de la Energía

Aquí puedes escribir una pequeña introducción histórica o física sobre el teorema antes de entrar a los detalles rigurosos.

=== "1. Intuición Visual"
    Escribe aquí la explicación intuitiva o geométrica del fenómeno. Puedes añadir una gráfica o animación que exportes de Python o MATLAB.
    
    ![Animación de ejemplo](../img/tu_grafico.png)

=== "2. Rigor Físico (Cálculo)"
    Aquí desarrollas el formalismo estándar que se enseña en la carrera de física usando ecuaciones en LaTeX:
    
    Si la fuerza es conservativa, se puede definir a partir del gradiente de una energía potencial $V$:
    
    $$ \vec{F} = -\nabla V $$
    
    Aplicando la segunda ley de Newton e integrando respecto a la trayectoria:
    
    $$ \int_{r_1}^{r_2} \vec{F} \cdot d\vec{r} = \Delta K $$
    
    Por lo tanto, demostramos que la energía mecánica total se mantiene constante:
    
    $$ K_1 + V_1 = K_2 + V_2 $$

=== "3. Rigor Axiomático (Fundamentos)"
    En este nivel explicas la raíz matemática profunda. Por ejemplo, cómo la conservación de la energía no es más que una consecuencia directa del **Teorema de Noether** debido a la simetría de traslación temporal del Lagrangiano del sistema:
    
    $$ \frac{d}{dt} \left( \sum_i \dot{q}_i \frac{\partial L}{\partial \dot{q}_i} - L \right) = -\frac{\partial L}{\partial t} $$
    
    Si el Lagrangiano no depende explícitamente del tiempo ($\frac{\partial L}{\partial t} = 0$), la cantidad entre paréntesis (el Hamiltoniano/Energía) es una constante de movimiento rigurosa.
