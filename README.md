# Metodo de Bell Delawere

1. Determinar las temperaturas de entrada y salida del lado de la coraza y de los tubos.

2. Calcular la diferencia de temperaturas mediaa logaritmica (DMTL):

$$
DMTL = \frac{\Delta T_{1} - \Delta T_{2}}{Ln\frac{\Delta T_{1}}{\Delta T_{2}}} \tag{1}
$$

Sindo

$\Delta T_{1} = T_{1} - t_{2}$

$\Delta T_{2} = T_{2} - t_{1}$

3. Calcular R y S:

$$
R = \frac{T_{1} - T_{2}}{t_{2} - t_{1}} \tag{2}
$$

$$
S = \frac{t_{2} - t_{1}}{T_{1} - t_{1}} \tag{3}
$$

Para determinar el número de corazas requeridas de tal manera que el factor de corrección de temperatura no sea menor de 0.8.

4. Determinar la diferencia de temperatura media logaritmica corregida (DTML)_{c}:

$$
DTML_{c} = DMTL \cdot FT \tag{4}
$$

5. Determinar las temperaturas de bulbo del lado de los tubos y coraza (TbT y TbS):

$$
TbT = \frac{t_{1} + t_{2}}{2} \tag{5}
$$

$$
TbS = \frac{T_{1} + T_{2}}{2} \tag{6}
$$

6. A la temperatura de bulbo de lado de los tubos, determine las propiedades del fluido:

+ Gravedad espeficica (SGT)
+ Viscosidad (\mu T), cp
+ Capacidad calorifica (CT), $\frac{BTU}{lb°F}$
+ Conductividad térmica (kT), $\frac{BTU}{hr-ft-°F}$

7. A la temperatura de bulbo del lado de la coraza, determine las propiedades del fluido:

+ Gravedad espeficica (SGS)
+ Viscosidad (\mu S), cp
+ Capacidad calorifica (CS), $\frac{BTU}{lb°F}$
+ Conductividad térmica (kS), $\frac{BTU}{hr-ft-°F}$

8. Determinar los fluidos másicos del lado de la coraza, WS (lb/hr) y del lado de los tubos, WT (lb/hr).

9. Determinar la carga de calor Q, usando los datos del lado de la coraza o del lado de los tubos.

a. Asumir un valor el coeficiente total de diseño (UD).
b. Calcular el area total (AT):

$$
AT = \frac{Q}{[UD(DTML)_{c}]} \tag{7}
$$

10. Elejir los siguientes parametros:

    + Número de pasos por el lado de los tubos (NPT).
    + Longitud de los tubos, (L) ft.
    + Diametro interior de los tubos, (di) in.
    + Diametro exterior de los tubos, (do) in.
    + Tipo de arreglo triangular, cuadrado o rotado.
    + Pitch de los tubos, (PT) in.
    + Pitch normal de los tubos, (PN) in.
    + Pitch paralelo, (PP) in.
    + Porciento de corte de la mapara.
    + Número de fajas de sellos (NSS).

11. Calcular el número de tubos del intercambiador de calor, (NT):

$$
\text{Numero de tubos} = \frac{A}{(\pi(\frac{do}{12})L)} \tag{8}
$$

Se pude modificar la longitud a la longitud a la longitud efectiva, usando L-0.5, en lugar de L, considerando que en promedio se tiene 0.5 pies por los espesores de los espejos, en los dos extremos del intercambiador del calor.

12. Determinar el área del intercambiador de calor:

$$
A = \pi (\frac{do}{12}L * \text{No. tubos}) \tag{9}
$$

13. Calcular el coeficiente global de transferencia de calor de diseño, (UD):

$$
UD = \frac{Q}{(NCO(DTML)_{c}A)} \tag{10}
$$

14. De acuerdo al número total de tubos y al tipo de arreglo, determinar el diametro exterior de haz de tubos. DOTL (in). 

## Calculo del coeficiente de pelicula del lado de la coraza.

15. Determinar el número de hileras cruzadas en una sección transversal (entre los extremos de las mamparas), NC:

    $$
    NC = \frac{D(1 - (\frac{2LC}{D}))}{PP} \tag{11}
    $$

16. Calcular la fracción de tubos totales en la sección de flujo transversasl:

    $$
    FC = \frac{1}{\pi}(\pi 2(\frac{D-(2LC)}{DOTL}))Sen(Cos^{-1} \frac{D-(2LC)}{DOTL})-2Cos^{1}(\frac{D-(2LC)}{DOTL}) \tag{12}
    $$

    Donde todos los ángulos estan en radianes.

17. Estimar el número efectivo de hileras en flujo transversal en cada ventana, (NCW):

    $$
    NCW = \frac{(0.8LC)}{PP} \tag{13}
    $$

    Esta ecuación asume que el fluido en el lado de la coraza cruzada, en promedio, la mitad de las hileras de tubos en la ventana (cada una de esas hileras dos veces) y que las hileras de extienden 0.8 de la distencia del extremo de la mampara al diametro interior de la coraza.

18. Numero de mamparas, (NB)

    $$
    NB = \frac{12L-LSI-LSO}{LS} + 1 \tag{14}
    $$

    Está ecuación considera que el espaciamiento de entrada y/o salida entre mamparas puede ser diferente del espaciamiento entre mamparas centrales.

19. Area de flujo transversal en/o cerca de la linea de centros para una sección de flujo transversal, SM:

    Para arreglo cuadrado y cuadrado rotado:
    
    $$
    SM = LS[D-DOTL+(\frac{DOTL-do}{PN})(PT-do)] \tag{15}
    $$

    Para arreglo triangular:

    $$
    SM = LS[D-DTOL+(\frac{DTOL-do}{PT})(PT-do)] \tag{16}

20. Calcular la fracción de área de flujo transversal disponible para flujo de "desvio", PSBP estimada de:

    $$
    FSBP = (\frac{D-DOTL}{SM})LS \tag{17}
    $$

21. Calcular el área de fugas tubo-mampara para una mampara.














53. Calcular el área requerida:

$$
A0 = \frac{Q}{UO(DMTL)_{c}}
$$

54. Calcular el porciento de sobrediseño

$$
SD = (\frac{A}{A0} - 1) \cdot 100
$$
