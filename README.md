# TextAnalizer

TextAnalyzer es una aplicación web liviana desarrollada con **JavaScript puro** (_vanilla JS_), pensada para ofrecer un análisis rápido y detallado de cualquier texto ingresado.
Permite contar caracteres, palabras y frases, establecer un límite de caracteres, calcular el tiempo estimado de lectura, y analizar la frecuencia de cada letra en el texto. Además, está diseñada con enfoque en **accesibilidad** y adaptación a distintos tamaños de pantalla.

## ✨ Funcionalidades principales

Esta aplicación permite al usuario **analizar y visualizar información** detallada sobre un texto ingresado. Entre sus funciones destacadas se incluyen:

- **Conteo de caracteres, palabras y frases**:
  Incluye la opción de contar los caracteres con o sin espacios.

- **Límite de caracteres personalizable**:
  El usuario puede establecer un límite y recibir una advertencia si lo supera.

- **Estimación del tiempo de lectura**:
  Basado en el contenido del texto y el promedio de lectura humana.

- **Análisis de densidad de letras**:
  Muestra cuántas veces se repite cada letra del alfabeto en el texto.

- **Modo de color personalizable**:
  El usuario puede seleccionar el tema visual que prefiera.

- **Accesibilidad por teclado**:
  Toda la navegación y funcionalidades son operables sin usar el mouse.

- **Diseño responsivo**:
  La interfaz se adapta automáticamente al tamaño de pantalla del dispositivo.

- **Indicadores visuales de interacción**:
  Todos los elementos interactivos muestran estados visibles al pasar el cursor o al enfocarlos mediante teclado.

- **Estimación del tiempo de lectura**: Calcula el tiempo aproximado que tomaría leer el texto, utilizando una velocidad promedio de lectura de 200 palabras por minuto.

## Funciones secundarias

- **Análisis de densidad de palabras**: Muestra cuántas veces se repite cada palabra dentro del texto, facilitando identificar términos frecuentes.

- **Estimación de tiempo de lectura en voz alta**: Calcula el tiempo aproximado para leer el texto en voz alta, útil para guiones de video o presentaciones.

- **Contador de espacios**: Permite conocer la cantidad exacta de espacios presentes en el texto ingresado.

## 🎨 Configuración y personalización

- **Modo claro y oscuro**:
  El usuario puede elegir entre tema claro u oscuro para adaptar la interfaz a sus preferencias o condiciones de luz.

- **Soporte multilenguaje**:
  La aplicación incluye traducción al español, permitiendo que la interfaz y mensajes estén en el idioma local para mejor accesibilidad y comprensión.

## 🚀 Inicio rápido

## Requisitos

- [Node.js](https://nodejs.org/es) instalado
- npm (viene incluido con Node.js)

### Instalación

```bash
npm install
```

### Ejecutar en entorno local

```bash
npm start
```

Asegúrate de tener instalado `live-server` o cualquier servidor local que uses. Puedes agregarlo como dependencia de desarrollo si no está.

## 🤝 Cómo contribuir

1. Haz un **fork** de este repositorio.
2. Crea una nueva rama desde `main`:

```bash
git checkout -b feat/nombre-de-tu-rama
```

3. Realiza tus cambios y haz commits en inglés siguiendo la convención [Conventional Commits](https://dev.to/achamorro_dev/conventional-commits-que-es-y-por-que-deberias-empezar-a-utilizarlo-23an).

4. Empuja tus cambios a tu fork:

```bash
git push origin feat/nombre-de-tu-rama
```

5. Abre un **Pull Request** describiendo claramente lo que hiciste.

Asegúrate de que tu código pase los **linters** antes de enviar un **PR**.
