# BI ImageFit

![HTML5](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-3-1572B6?logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-222222?logo=github)
![Privacy](https://img.shields.io/badge/Privacy-100%25%20local-2EA44F)
![Version](https://img.shields.io/badge/Version-0.1.0-007EC6)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Herramienta gratuita para adaptar, redimensionar y optimizar imágenes directamente en el navegador. Diseñada inicialmente para Power BI, también resulta útil para presentaciones, sitios web, redes sociales y documentos.

**[Abrir la aplicación](https://goyoaga.github.io/bi-image-fit/)**

## Funcionalidades

- Carga de imágenes mediante selector de archivos o arrastrar y soltar.
- Proporciones 16:9 y 1:1, sin deformar la imagen.
- Recorte centrado o conservación de la imagen completa.
- Exportación JPG con calidad ajustable (40–95 %, 82 % por defecto) y PNG.
- Fondo blanco, negro o transparente (PNG).
- Vista previa, dimensiones, peso y comparación con el archivo original.
- Modo claro/oscuro con preferencia local.
- Interfaz adaptable a escritorio y móvil.

## Resoluciones

| Perfil | 16:9 | 1:1 |
| --- | --- | --- |
| Ligera | 640 × 360 | 400 × 400 |
| Estándar (por defecto) | 1280 × 720 | 600 × 600 |
| Alta | 1920 × 1080 | 1080 × 1080 |

## Cómo utilizarla

1. Abre la aplicación.
2. Selecciona o arrastra una imagen.
3. Elige proporción, adaptación, resolución, formato y fondo.
4. Si exportas a JPG, ajusta la calidad.
5. Comprueba el resultado y su peso.
6. Descarga la imagen optimizada.

JPG suele ser apropiado para fotografías; PNG para gráficos o transparencias. El peso final depende de la imagen y de los ajustes: no se garantiza una reducción en todos los casos.

## Privacidad y tecnología

HTML, CSS y JavaScript nativo, con File API, Image.decode y Canvas API. Las imágenes se procesan en el dispositivo y no se envían a ningún servidor. No hay cuentas, base de datos, backend ni dependencias de ejecución externas. La preferencia de tema se guarda en localStorage. Los enlaces de apoyo son opcionales y externos.

## Ejecución local

Clona el repositorio y abre `index.html` en un navegador moderno.

```bash
git clone https://github.com/goyoaga/bi-image-fit.git
cd bi-image-fit
```

No es necesario instalar paquetes ni compilar el proyecto.

## Estructura

```text
bi-image-fit/
├── index.html
├── assets/
│   └── bytehive-lab-logo.png
├── README.md
└── LICENSE
```

El isotipo del footer está integrado como SVG; el PNG original se conserva como recurso de marca.

## Compatibilidad y límites

Los formatos de entrada dependen de la capacidad de decodificación del navegador. HEIC, RAW y TIFF no están garantizados. No incluye procesamiento por lotes ni un límite de peso automático. La prueba inicial móvil y los ajustes visuales han sido confirmados por el usuario; la validación específica en escritorio y Power BI sigue pendiente.

## Licencia

Código y documentación bajo [MIT](LICENSE). Se permite su uso, modificación y distribución, incluso comercial, conservando el aviso de copyright y licencia. La licencia del software no concede derechos sobre marcas o logotipos de bytehive lab.

## Créditos

Desarrollado por [bytehive lab](https://bytehive.pro).

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Invítame%20un%20café-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/arielgoyoaga)
