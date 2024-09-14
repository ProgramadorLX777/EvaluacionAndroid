# EvaluacionAndroid (Jorge Lecaro - Área de Ingeniería en Informática)
Evaluación de dos casos a elección (Validador de Rut Chileno y una Calculadora IMC):

En este evaluación escogí dos casos:
- Validador de Rut Chileno
- Calculadora de IMC

Caso 1:
En el caso del Validador de rut chileno se utilizó un EditText para ingresar el rut, el cual posteriormente fue validado por diversos métodos 
como el Pattern y el Matcher, el pattern para crear un patrón de los carácteres y números que debían ir y el matcher para comparar.
Además se utilizo el método dv para validar el dígito verificador.

Caso 2:
En el caso de la calculadora de IMC se insertaron dos EditText para la altura y el peso el cual posteriormente mediante una tabla de valores referenciales, 
se utilizaron sentencias condicionales IF para evaluar cada resultado de la fórmula para calcular el IMC que es: (peso / altura^2).
Por último, se realizaron validaciones para los campos vacíos.

