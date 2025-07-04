# 📐 Guía de estilos de diseño

## Paleta de colores
### Colores para métricas:

| Métrica              |	Color	      | Hex	       | Uso recomendado                      |
|----------------------|--------------|------------|--------------------------------------|
| Conteo de letras     |	Azul        |	#3c78b4 |	Color primario para conteo de letras |
| Conteo de palabras   |	Verde       |	#28a745 |	Para representar conteo de palabras  |
| Conteo de frases     |	Naranja     |	#f39c12 |	Color cálido para conteo de frases   |
| Tiempo de lectura    |	Morado      |	#6f42c1 |	Distintivo para tiempo estimado      |
| Densidad de letras   |	Rojo suave  |	#e74c3c |	Para indicar frecuencia de letras    |
| Contador de espacios |	Gris oscuro |	#555555	| Neutro para conteo de espacios       |

### Colores generales:

| Uso              |	Color            |	Hex      |
|------------------|-------------------|-----------|
| Color primario   |	Azul             |	#3c78b4 |
| Color secundario |	Blanco           |	#ffffff |
| Fondo claro      |	Gris muy claro   |	#f5f7fa |
| Fondo oscuro     |	Negro casi total |	#121212 |
| Texto principal  |	Gris oscuro      |	#212121 |
| Texto secundario |	Gris medio       |	#666666 |
| Color de acento  |	Rosa fuerte      |	#e94e77 |

 |Uso                   |	Color acrílico (RGBA)      |
 |----------------------|----------------------------|
 |Fondo claro acrílico  |	rgba(245, 247, 250, 0.5) |
 |Fondo oscuro acrílico |	rgba(18, 18, 18, 0.7)    |
 |Primario acrílico     |	rgba(60, 120, 180, 0.6)  |
 |Acento acrílico       |	rgba(233, 78, 119, 0.5)  |

## Tipografía
- Fuente principal: `'Montserrat', sans-serif`.

- Tamaño base: 16px.

## Jerarquía de tamaños:

- **H1**: 2rem (32px)

- **H2**: 1.5rem (24px)

- **H3**: 1.25rem (20px)

- **Texto normal**: 1rem (16px)

- **Texto pequeño**: 0.875rem (14px)

## Espaciados y layout
- **Margen y padding estándar**: 16px o múltiplos para mantener consistencia.

- **Grid**: usar sistema de columnas con gap de 16px.

- **Ancho máximo**: 1200px para contenido principal.

## Botones y estados

 | Propiedad         |	Botón Principal                   |	Botón Secundario                    |
 |-------------------|------------------------------------|-------------------------------------|
 | Color (texto)     |	#ffffff                          |	#3c78b4                           |
 | Background-color  |	#3c78b4                          | transparent                         |
 | Border            |	none                              | 2px solid #3c78b4                 |
 | Box-shadow        |	0 2px 4px rgba(60,120,180,0.4)  |	none                                |
 | Font-size         |	0.875rem                          | (14px)	0.875rem (14px)             |
 | Font-weight       |	600                               |	600                                 |
 | Line-height       |	1.25rem (20px)                    |	1.25rem (20px)                      |
 | Border-radius     |	0.25rem (4px)                     |	0.25rem (4px)                       |
 | Hover-Color       |	#ffffff                          |	#2a5c85                           |
 | Hover-Background  |	#335a8a                          |	rgba(60,120,180,0.1)             |
 | Hover-Border      |	none                              |	2px solid #2a5c85                 |
 | Hover-Box-shadow  |	0 4px 8px rgba(60,120,180,0.6)  |	none                               |
 | Active-Color      |	#e0e0e0                          |	#1f3d5c                           |
 | Active-Background |	#2a4d70                          |	rgba(60,120,180,0.2)             |
 | Active-Border     |	none                              |	2px solid #1f3d5c                 |
 | Active-Box-shadow |	inset 0 2px 4px rgba(0,0,0,0.3) |	inset 0 2px 4px rgba(0,0,0,0.15) |

## Iconografía y elementos visuales
- Iconos svg descargados desde [ionicons](https://ionic.io/ionicons).
- Tamaño fijo de los iconos: 1.5rem x 1.5rem (24px x 24px).
