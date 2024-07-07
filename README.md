
# Resultado de Drivers

El proyecto "Resultado de Drivers" es una aplicación JavaFX diseñada para mostrar los resultados de los pilotos de Fórmula 1 en diferentes temporadas. A través de una interfaz gráfica, los usuarios pueden seleccionar un año específico y ver información detallada sobre los pilotos, como sus nombres, victorias, puntos totales y clasificación en esa temporada.

## Estructura del proyecto

A continuación, describiré las partes clave de la estructura del proyecto:

### Clase principal (`Main`):

- La clase `Main` es el punto de entrada de la aplicación. Se encarga de configurar la interfaz gráfica y gestionar la lógica principal.
- En el método `start`, se crea la ventana principal (`Stage`) y se organizan los componentes visuales (etiquetas, combobox y tabla) en un `BorderPane`.
- La tabla de resultados de pilotos se muestra en el centro del `BorderPane`.

### Componentes visuales:

- **Etiquetas (`Label`)**: Se utilizan para mostrar texto, como "Año:". Se configuran con una fuente y estilo específicos.
- **Combobox (`ComboBox`)**: Permite al usuario seleccionar un año de la lista de temporadas disponibles. Al seleccionar un año, se actualiza la tabla con los resultados correspondientes.
- **Tabla (`TableView`)**: Muestra los detalles de los pilotos, incluyendo su nombre, victorias, puntos totales y clasificación. Se configuran columnas específicas para cada atributo.

### Modelo de datos:

- Los datos de los pilotos y las temporadas se obtienen a través de repositorios (por ejemplo, `DriverResultRepository` y `SeasonRepository`).
- Las clases de modelo (como `DriverResult` y `Season`) representan la estructura de los datos y se utilizan para poblar la tabla.

### Diseño de la interfaz:

- El diseño se basa en un `BorderPane` con una etiqueta en la parte superior, un combobox en la parte superior central y la tabla en el centro.
- Se utiliza una combinación de `VBox` y `HBox` para organizar los componentes visualmente.

## Instrucciones para ejecutar el proyecto

1. **Requisitos previos**:
   - Asegúrate de tener Java instalado en tu sistema.
   - Clona este repositorio en tu máquina local.

2. **Ejecución**:
   - Abre el proyecto en tu IDE preferido (como IntelliJ IDEA o Eclipse).
   - Ejecuta la clase `Main` como una aplicación JavaFX.
   - Se abrirá una ventana con la interfaz de usuario.

3. **Uso**:
   - Selecciona un año en el menú desplegable.
   - Los resultados de los pilotos para ese año se mostrarán en la tabla.

## Autor

- Adrian Eduardo Pozo Torres

## Vista de la Aplicacion

![Captura de pantalla 2024-07-07 015324](https://github.com/AdrianPozoT/Interfaz-DriverResult/assets/168159379/807ad507-9119-4fa2-bf93-12d009d3b478)
