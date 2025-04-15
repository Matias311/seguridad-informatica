# Seguridad Informática

### Presentación
Los archivos están organizados de la siguiente manera:

1. **Documentos Word y Presentación**
   - En la carpeta `Archivos Presentacion` se guardó el documento Word (informe) y la presentación.

2. **Video de Evidencia**
   - [Ver video de evidencia](https://youtu.be/PhhxSCtKjBE)

3. **Archivos JSON**
   - Los archivos `.json` contienen los resultados de las consultas realizadas. Estos son:
     - `consulta1.json`
     - `consulta2.json`
     - `consulta3.json`

### Consultas Realizadas
A continuación, se presentan las consultas utilizadas para obtener los resultados:

```python
consulta1 = 'filetype:sql "MySQL dump" (pass|password|pwd)' 
consulta2 = '"MySQL dump" filetype:sql intext: -- Host:'
consulta3 = '"MySQL dump" site:github.com'
