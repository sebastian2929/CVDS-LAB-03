# CVDS-LAB-03
Sebastian David Blanco Rodriguez
Laboratorio 3 donde se implementas las pruebas de unidad

# AeroDescuentos

  1. De acuerdo con lo indicado,y teniendo en cuenta que NO hay precondiciones,en qué casos se debería arrojar una excepción de tipo ExcepcionParametrosInvalidos?. Agregue esto a la especificación.

   * Cuando la edad es negativa
   * El descuento no es valido para la edad
   * Cuando el viaje es menor a 20 dias
   * La tarifa del vuelo es incorrecta

  2. En la siguiente tabla enumere un conjunto de clases de equivalencia que -según usted-creen una buena división del conjunto de datos de entrada de la función anterior:
  
| Numero| Clase Equivalencia| Resultado correcto/incorrecto |
|:------|-------------------|-------------------------------|
| #1 | dias > 20| correcta| 
| #2 | edad < 18 & edad > 65| correcta |
| #3 | edad > 18 & edad < 65| incorrecta |
| #4 | edad < 18| correcta |
| #5 | tarifa < 0| incorrecta |
| #6 | edad < 0| incorrecta |


  3. Para cada clase de equivalencia, defina un caso de prueba específico, definiendo: parámetros de entrada y resultados esperados.

  4. A partir de las clases de equivalencia identificadas en el punto 2, identifique las condiciones límite o de frontera de las mismas.

  5. Para cada una de las condiciones de frontera anteriores, defina casos de prueba específicos.
