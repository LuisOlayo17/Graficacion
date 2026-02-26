# 1.1 Historia y Evolución de la Graficación por Computadora

La graficación por computadora es una disciplina que estudia la generación, manipulación y representación de imágenes mediante sistemas computacionales.

## Orígenes (1950-1960)

En la década de 1950 se comenzaron a utilizar osciloscopios para mostrar gráficos simples.  
En 1963, Ivan Sutherland desarrolló Sketchpad, considerado el primer sistema de diseño asistido por computadora (CAD).


## Desarrollo (1970-1990)

Durante estas décadas se desarrollaron:

- Algoritmos de rasterización
- Modelos de iluminación
- Representaciones tridimensionales
- Simuladores de vuelo

## Era moderna (2000-Actualidad)

- Uso de GPU
- Renderizado en tiempo real
- Ray Tracing
- Realidad Virtual y Aumentada
- Inteligencia Artificial aplicada a gráficos

![Magnavox Odyssey_thumb](https://github.com/user-attachments/assets/7eef34f5-0518-4d78-94f2-060c50e316e1)


# 1.2 Áreas de Aplicación

La graficación por computadora se aplica en diversos campos:

## Videojuegos
Creación de entornos 3D, personajes y efectos visuales.

![download](https://github.com/user-attachments/assets/fdba0e78-2d93-4a38-a3b9-59cb3824c66b)


## Cine y Animación
Producción de efectos especiales (CGI).

![download](https://github.com/user-attachments/assets/6fb67ed6-f450-416c-9721-bf6575c626ef)


## Diseño Asistido por Computadora (CAD)
Utilizado en arquitectura e ingeniería.

<img width="512" height="320" alt="unnamed" src="https://github.com/user-attachments/assets/23871ddb-e710-4d85-a17c-f7bd9d8b5882" />


## Medicina
Visualización de tomografías y modelos anatómicos 3D.

![images](https://github.com/user-attachments/assets/3ffb6b9c-eaf3-4b18-8c36-f6c6494c6394)


## Realidad Virtual y Aumentada
Aplicaciones educativas y de entretenimiento.

![download](https://github.com/user-attachments/assets/600fb97f-012f-44ca-a277-adc9ed38cf3d)


# 1.3 Aspectos Matemáticos de la Graficación

Las matemáticas son el fundamento principal de la graficación por computadora.

## Sistemas de Coordenadas

Se utilizan sistemas cartesianos bidimensionales (x,y) y tridimensionales (x,y,z). Cada objeto se representa mediante un conjunto de vértices definidos por coordenadas.

## Vectores

Un vector representa dirección y magnitud. En gráficos 3D se utilizan vectores para:

- Representar posiciones.
- Calcular iluminación.
- Determinar normales de superficies.

## Matrices de Transformación

Las transformaciones geométricas se realizan mediante multiplicación de matrices:

### Traslación

| 1 0 Tx |
| 0 1 Ty |
| 0 0 1  |

### Rotación (2D)

| cosθ -sinθ 0 |
| sinθ cosθ  0 |
| 0     0    1 |

### Escalamiento

| Sx 0  0 |
| 0  Sy 0 |
| 0  0  1 |

## Producto Punto y Producto Cruz

El producto punto se usa para calcular ángulos entre vectores y determinar iluminación.

El producto cruz permite calcular vectores normales en superficies 3D.

## Curvas y Superficies

Se utilizan ecuaciones paramétricas para representar:

- Curvas Bézier
- Superficies NURBS
- Splines

Estos elementos permiten generar formas suaves y complejas.

| 1 0 Tx |
| 0 1 Ty |
| 0 0 1  |

También intervienen conceptos de trigonometría para calcular ángulos y orientación en espacios tridimensionales, así como cálculo diferencial para modelar curvas y superficies suaves.

![download](https://github.com/user-attachments/assets/db50d23a-36db-433a-a166-e398c4cdeccf)



# 1.4 Modelos de Color: RGB, CMY, HSV y HSL

Los modelos de color permiten representar matemáticamente la percepción del color.

## Modelo RGB

Modelo aditivo basado en la mezcla de luz roja, verde y azul. Es utilizado en pantallas y dispositivos electrónicos.

Cada color se representa con valores entre 0 y 255.

Ejemplo:
Rojo puro = (255,0,0)

## Modelo CMY

Modelo sustractivo usado en impresión. Se basa en la absorción de luz.

Cian absorbe rojo.
Magenta absorbe verde.
Amarillo absorbe azul.

## Modelo HSV

Representa el color de forma más intuitiva:

- Hue: Ángulo en la rueda de color (0°–360°).
- Saturation: Intensidad.
- Value: Brillo.

## Modelo HSL

Similar al HSV, pero utiliza luminosidad en lugar de valor.

---

## Iluminación en Blender

La iluminación en Blender se basa en:

- Tipo de luz (Point, Sun, Spot).
- Intensidad.
- Sombras.
- Materiales PBR.

Se pueden modificar parámetros como rugosidad, especularidad y reflexión para obtener mayor realismo.

![maxresdefault](https://github.com/user-attachments/assets/a2f2e730-76f5-4518-a14f-e4bd499ced84)
