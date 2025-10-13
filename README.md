# STEM_LADAINA
This is repository for the project related to STEM careers it contains detailed files on wich would provide a better organzation, and a read me  explaining the structure 
1) Datasets_oficiales: Todos los datasets que esten limpios y con los que se pueda trabajar en orden de fecha AAMMDD 
2) Datasets_webscraping: Todos los data sets webscrapeados sin limpiar ubicados por carpetas en orden de fecha AAMMDD 
3) Codigo_Webscraping: Todo el codigo ubicado por carpetas de cada una de las fuentes scrapeado con orden de Nombre_Funcion.ipynb 
4) Codigo_Limpieza: Todos los archivos de codigo que esten realcionados unicamente con la limpieza directa de los datasets orientados por Nombre_Funcion 
5) Documentos_Taxonomia: Todos los documentos que tenga relacion unicamente con la estandarizacion categorica que sean de informacion 
6) Codigo_Clubstering: Todo el codigo que tenga relacion unicamente con la clubsterización del documento
La idea de usar esta esctrutura eque que podamos orientar las carpetas si es una carpeta que tiene datasets que se llame Datasets_Esperiencia y que cada data set este etiquetado con fecha_Experiencia y asi para otros temas lo mismo con el codigo  que tenga nombre por ejemplo: Limpieza_TextosyRuido. 
Estructura Formal:
📦 Proyecto_LADANA
│
├── 1_Datasets_Oficiales/
│   ├── 20240508_StemOficiales.csv
│   └── README.md
│
├── 2_Datasets_Webscraping/
│   ├── 20240508/
│   │   ├── Linkedin_raw.csv
│   │   ├── Empleo_raw.csv
│   │   └── Empleo_raw.csv
│   └── README.md
│
├── 3_Codigo_Webscraping/
│   ├── Linkedin/
│   │   ├── Extraer_Titulares.ipynb
│   │   ├── Extraer_Categorias.ipynb
│   │   └── README.md
│   └── ...
│
├── 4_Codigo_Limpieza/
│   ├── Limpieza_TextosyRuido.ipynb
│   ├── Limpieza_NulosyDuplicados.ipynb
│   └── README.md
│
├── 5_Documentos_Taxonomia/
│   ├── Taxonomia_Categorias.xlsx
│   ├── Mapa_Estandarizacion.pdf
│   └── README.md
│
├── 6_Codigo_Clustering/
│   ├── Clustering_Titulos.ipynb
│   └── README.md
│
└── README.md
Nota: Se propone que cada carpeta del proyecto incluya un archivo README.md que funciona como una bitácora técnica. En estos documentos se describe brevemente el propósito de cada módulo, los pasos principales de su ejecución y las decisiones tomadas durante su desarrollo. Esto permite mantener un registro ordenado del progreso y facilita la comprensión del trabajo a otros miembros del equipo o revisores.