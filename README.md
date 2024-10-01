# Control de Brazo Robot con Arduino y Joysticks

Este proyecto permite controlar un brazo robótico utilizando un Arduino y dos joysticks analógicos. Aquí encontrarás el código fuente para modificar el comportamiento del brazo, un diagrama de conexión, un video demostrativo y toda la información necesaria para empezar a utilizar el sistema.

## Contenido del Repositorio

- **BrazoRobot.ino**: Código principal en Arduino para el control del brazo robot.
- **VideoDemostrativo.mp4**: Un video donde se muestra el funcionamiento del brazo robótico con los joysticks.
- **DiagramaDeConexion.png**: Diagrama de conexión para ensamblar los joysticks con el Arduino y los servomotores.
- **README.md**: Archivo de documentación del proyecto (este archivo).

## Descripción

Este proyecto utiliza un Arduino para controlar un brazo robot a través de dos joysticks analógicos. Cada joystick se utiliza para controlar distintos grados de libertad del brazo:

- **Joystick 1**: Controla la base y el hombro del brazo.
- **Joystick 2**: Controla el codo y la muñeca.

El código está diseñado para ser flexible y fácil de modificar, permitiéndote personalizar los movimientos del brazo según tus necesidades.

## Cómo Utilizar el Código

1. **Conectar los Componentes**: Sigue el **Diagrama de Conexión** para ensamblar el brazo, conectando los servos al Arduino y los joysticks a los pines analógicos indicados.
2. **Cargar el Código**: Abre el archivo `BrazoRobot.ino` en el IDE de Arduino y cárgalo en tu placa Arduino.
3. **Alimentar el Sistema**: Conecta la alimentación de los servos y el Arduino.
4. **Controlar el Brazo**: Usa los joysticks para controlar el movimiento del brazo.

## Requisitos

- Arduino Uno o similar
- 7 servomotores
- 2 joysticks analógicos
- Fuente de alimentación adecuada para los servos
- Cableado y componentes de montaje

## Cómo Modificar el Código

Puedes personalizar el comportamiento del brazo modificando los valores en el archivo `BrazoRobot.ino`:
- **Velocidades de los servos**: Ajusta las variables `s1Vel`, `s2Vel`, etc., para cambiar la velocidad de movimiento de los distintos servos.
- **Rangos de movimiento**: Usa la función `map()` para adaptar los rangos de los joysticks al movimiento deseado.

## Video Demostrativo

Puedes ver un video demostrativo del funcionamiento del brazo en [VideoDemostrativo.mp4](VideoDemostrativo.mp4).

## Créditos

Este proyecto fue inspirado y desarrollado gracias a los diseños de [FabríCreator](https://www.youtube.com/@FABRIcreator). Agradecemos su trabajo por proporcionar los planos y los diseños para el brazo robótico.

## Contribuciones

Si deseas contribuir al proyecto, siéntete libre de hacer un **fork** del repositorio y realizar un **pull request** con tus mejoras o sugerencias.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.
