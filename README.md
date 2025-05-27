# Proyecto de Brazo Robótico 
# Autoras: 
- Nicole Rodríguez
- Maryela Morales
  
Este proyecto permite el control de un brazo robótico por medio de cuatro Micro Servomotores. El sistema cuenta con dos modos de uso, manual y automático; el modo de uso es controlado por medio de un Switch. 

# Modo Manual 
Cada potenciómetro controla la posición de un servomotor 
- Servo 1 // Base
- Servo 2 // Brazo izquierdo
- Servo 3 // Brazo derecho
- Servo 4 // Garra

# Modo Automático
El brazo adopta distintas posiciones secuenciales por medio de presionar dos botones el botón de avance o retroceso. 

# Hardware utilizado 
- Arduino NANO
- 4 Micro Servomotores
- 4 Potenciómetros
- 2 botones
- 1 Switch
- 2 LEDs
- Resistencias de 330 ohms
- Protoboard y cables de conexión

# Diagrama de pines
|     Componente     |     Pin Arduino     |
| LED Automático     |           4         |
| LED Manual         |           5         |
| Botón Avance       |           7         |
| Botón Regreso      |           8         |
| Switch             |           6         |
| Potenciómetro 01   |           A0        |
| Potenciómetro 02   |           A1        |
| Potenciómetro 03   |           A2        |
| Potenciómetro 04   |           A3        |
| Servo 01           |           12        |
| Servo 02           |           11        |
| Servo 03           |           10        |
| Servo 04           |           9         |

# Salida serial 
El monitor serial muestra las posiciones actuales de los 4 Micro Servomotores en grados, cuando existe un cambio en estas

# Librerías agregadas 
- <servo.h> (incluida en el IDE de Arduino)
