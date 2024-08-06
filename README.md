# ACTIVIDAD-2
## 1. Diagrama de bloques:
![Diagrama de bloques](file:///C:/Users/Maria%20Paz/Downloads/Diagrama%20de%20flujo.pdf) 
## 2. Casos de aplicación: 
### Velocidad:
| Caso | Sensor    | Encabezado | Datos binarios | Paridad | Valor Dec. | Set Point | Error | Error binario | K_P | Control | Codificación CPU    | 
| 1    | Velocidad | 00         | 0100110101     | 1       | 309 mph    | 320 mph   | -11   | 1111110100    | 1,5 | -16,5   | 0001001101010000001 | 
| 2    | Velocidad | 00         | 1010010100     | 0       | 660 mph    | 650 mph   | 10    | 0000001010    | 1,5 | 15      | 0010100101000000000 |
| 3    | Velocidad | 00         | 0111101011     | 0       | 491 mph    | 500 mph   | -9    | 1111110110    | 1,5 | -13,5   | 0001111010110000000 |
### Altitud:
| Caso | Sensor    | Encabezado | Datos binarios | Paridad | Valor Dec. | Set Point | Error | Error binario | K_P | Control | Codificación CPU    |
| 1    | Altitud   | 01         | 0000100011     | 1       | 1373 ft    | 1400 ft   | -27   | 1111100100    | 1,2 | -32,4   | 0100001000110000001 |  
| 2    | Altitud   | 01         | 0000111101     | 1       | 2420 ft    | 2500 ft   | -80   | 1110101111    | 1,2 | -96     | 0100001111010000001 |  
| 3    | Altitud   | 01         | 0010000000     | 0       | 5005 ft    | 5100 ft   | -95   | 1110100000    | 1,2 | -114    | 0100100000000000000 | 
### Temperatura:
| Caso | Sensor      | Encabezado | Datos binarios | Paridad | Valor Dec. | Set Point | Error | Error binario | K_P | Control | Codificación CPU    |  
| 1    | Temperatura | 10         | 000000110110   | 1       | 54°C       | 50°C      | 4     | 000000000100  | 0,8 | 3,2     | 1000000011011000001 | 
| 2    | Temperatura | 10         | 000001110011   | 0       | 115°C      | 110°C     | 5     | 000000000101  | 0,8 | 4       | 1000000111001100000 | 
| 3    | Temperatura | 10         | 000010101000   | 1       | 168°C      | 160°C     | 8     | 000000001000  | 0,8 | 6,4     | 1000001010100000001 | 
## 3. Conclusiones:
- El diseño de un sistema de control de variables para una aeronave demuestra la importancia de integrar múltiples módulos y sistemas. Cada componente, desde los sensores hasta la CPU, debe funcionar de manera coherente para garantizar una operación precisa y segura.
-  La conversión de datos binarios a decimales y viceversa es fundamental para la interpretación y procesamiento de la información.
- La actividad fue una oportunidad muy importante para comprender y aplicar conceptos clave de la ingeniería. 