# Lector PDF Mistral

Un sistema de lectura y procesamiento de documentos PDF utilizando la API de Mistral para OCR (Reconocimiento Óptico de Caracteres) y extracción de texto.

## Descripción

Este proyecto permite extraer y procesar texto de archivos PDF utilizando la tecnología de IA de Mistral. El sistema lee documentos PDF, ejecuta OCR cuando es necesario, y convierte el contenido a archivos markdown para facilitar su posterior procesamiento y análisis.

## Estructura del Proyecto

```
.
├── Inputs/               # Carpeta para archivos PDF de entrada
│   └── MC0003272.pdf     # Ejemplo de archivo PDF
├── Log/                  # Registros de ejecución
│   └── lectura_pdf.log   # Archivo de registro de la última ejecución
├── Outputs/              # Resultados generados
│   └── Markdowns/        # Archivos markdown extraídos
│       └── MC0003272.md  # Ejemplo de archivo markdown generado
└── Script/               # Scripts y código fuente
    ├── .env              # Archivo de configuración con claves API
    └── Mistral_OCR_pdf_local.ipynb  # Notebook principal con el código
```

## Requisitos

- Python 3.8+
- Jupyter Notebook
- Bibliotecas de Python (detalles en el notebook)
- Clave API de Mistral

## Instalación

1. Clone este repositorio
2. Instale las dependencias necesarias:
   ```
   pip install -r requirements.txt
   ```
3. Configure su clave API de Mistral en el archivo `.env`

## Uso

1. Coloque sus archivos PDF en la carpeta `Inputs/`
2. Ejecute el notebook `Script/Mistral_OCR_pdf_local.ipynb`
3. Los archivos procesados se guardarán en `Outputs/Markdowns/`

## Características

- Reconocimiento Óptico de Caracteres (OCR) utilizando IA
- Conversión automática de PDF a markdown
- Registro detallado del proceso
- Procesamiento local de documentos

## Licencia

[Incluir licencia]

## Contacto

[Información de contacto]