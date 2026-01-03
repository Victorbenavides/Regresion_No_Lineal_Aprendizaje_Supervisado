# Regresion_No_Lineal_Aprendizaje_Supervisado
Analizamos la relación: Tenemos un conjunto de datos donde comparamos años de experiencia con el salario.

Preparamos los datos: Dividimos todo en X (los años) y y (el sueldo) para que el modelo sepa qué queremos predecir.

Aplicamos una curva, no una línea: Usamos PolynomialFeatures(degree=3). Esto lo hacemos porque asumimos que el sueldo no sube de forma recta y constante, sino que tiene curvas más realistas según pasan los años.

Entrenamos el algoritmo: Separamos los datos en grupos de entrenamiento y prueba para verificar que la IA no esté "haciendo trampa" al memorizar los resultados.

Medimos qué tan bien nos fue: Al final, calculamos el error. Vemos que tenemos un margen de error del 13.5% aproximadamente, con una diferencia de unos 4,197 pesos/dólares respecto a la realidad.
<img width="1154" height="492" alt="image" src="https://github.com/user-attachments/assets/85e28a71-f0ec-40e1-845b-8be8b8ba5605" />
