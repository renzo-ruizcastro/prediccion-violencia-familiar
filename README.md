# Sistema de predicción de violencia familiar

Utilizar la carpeta [datalake](https://drive.google.com/drive/folders/1NUT4hjeMkFuw7nAiMSNxJ-YkPfhJWklh?usp=sharing).

### Diccionario de datos del datalake integrado

- COMISARIA: Nombre de la comisaría
- CUADRA: Número de cuadra
- DERIVADA_FISCALIA: Nombre de la fiscalía a la que se derivó la denuncia
- DIRECCION: Indicada en la denuncia como la dirección del lugar en que sucedió el delito
- DIST_CIA: Distrito donde se realizó la denuncia
- DIST_HECHO: Distrito donde ocurrió el delito
- DPTO_CIA: Departamento donde se realizó la denuncia
- DPTO_HECHO: Departamento donde ocurrió el delito
- EDAD: Edad de la persona que figura en el registro de la denuncia
- ESTADO_DEN: Estado de la denuncia
- EST_CIVIL: Estado civil de la persona que figura en el registro de la denuncia
- FECHA_HORA_HECHO: Indicada en la denuncia como la fecha en que sucedió el delito
- ID_COMISARIA: Identificador de la comisaría
- ID_EST_CIVIL: Identificador del estado civil de la persona que figura en el
  registro de la denuncia
- ID_MODALIDAD: Indentificador de la modalidad del delito que figura en el registro de la denuncia.
- ID_NIVEL_EDUCATIVO: Identificador del nivel educativo de la persona que figura en el registro de la denuncia
- ID_REGION: Identificador de la región donde se realizó la denuncia
- ID_TIPO_DENUNCIA: Identificador del tipo de denuncia que figura en el registro de la denuncia
- MODALIDAD: Modalidad del delito que figura en el registro de la denuncia.
- NIVEL_EDUCATIVO: Nivel educativo de la persona que figura en el registro de la
  denuncia
- OCUPACION: Ocupación de la persona que figura en el registro de la denuncia
- PROV_CIA: Provincia donde se realizó la denuncia
- PROV_HECHO: Provincia donde ocurrió el delito
- REGION: Región donde ocurrió la denuncia
- SEXO: Sexo de la persona que figura en el registro de la denuncia
- TIPO_DENUNCIA: Tipo de denuncia
- UBICACION: Ubicación donde se realizó la denuncia
- UBIGEO_CIA: Código ubigeo del lugar donde se realizó la denuncia
- UBIGEO_HECHO: Código ubigeo donde ocurrió el delito.
- VIA: Tipo de contexto espacial en donde ocurrió el delito
- fec_registro: Fecha de registro de la denuncia
- pais_natal: País natal de la persona que figura en el registro de la denuncia

### Cómo correr el proyecto

1. Descargar los archivos de la carpeta datalake/sources del repositorio en Google Drive indicado al inicio de este documento.
2. Correr el archivo integracion.ipynb
3. Correr el archivo preprocesamiento.ipynb
4. Correr los archivos de la carpeta seleccion_caracteristicas en la siguiente secuencia: i)pca.ipynb, ii) chi-cuadrado.ipynb, iii) anova.ipynb
5. Correr el archivo analisis_exploratorio.ipynb
6. Optar por utilizar modelos con dataset balanceado o sin balancear

- Balanceado: archivos de la carpeta modelos
- Sin balancear: archivos del archivo modelos.ipynb
