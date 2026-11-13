# <center>Proyecto brechas potenciales de exportación en Colombia - Modelo gravitacional estructural y Machine Learning</center>
### **Título:** Identificación del comercio potencial y diversificación exportadora para productos No minero-energéticos de Colombia.  

### **Integrantes:**
- Andrés Felipe Linares
- Juan Esteban Roa 
- Juan Pablo Lozano 

## Descripción del Proyecto
El proyecto consiste en un ejercicio econométrico con una posterior aplicación de Machine Learning, que consiste en identificar las relaciones producto–país de destino de la canasta exportadora colombiana no minero-energética que presentan la brecha de comercio potencial no realizado de Colombia, medida por un modelo gravitacional estructural, para posteriormente, mediante un árbol de decisión (Random Forest), el modelo prediga qué variables incluidas tienen una mayor repercusión sobre la probabilidad de disminuir la brecha existente.

**Problema:** 
Históricamente en Colombia las exportaciones han estado muy concentradas en el sector extractivo o minero-energético. Sin embargo, en Colombia se ha intentado diversificar la canasta exportadora, tratando de identificar potencial exportador, tanto en productos alternativos, como en principales mercados para estos productos.  

**Entrega de Valor:** 
Será identificar las combinaciones producto-país con mayor oportunidad de exportación, que sirva como insumo para orientar decisiones de política comercial, promoción de exportaciones y priorización empresarial.


## Desarrollo
El proyecto se desarrolla en python y se ejecuta en nueve notebooks principales .ipynb.  
| Notebook | Resultado |
| --- | --- |
| 01 | Importación BACI, fuentes geográficas, PIB y membresías. |
| 02 | Exportaciones colombianas, siete covariables y catálogo de destinos. |
| 03 | Exploración y visualizaciones de la muestra econométrica. |
| 04 | PPML, panel completo, coeficientes y brechas. |
| 05 | Quince variables ML e importación de los complementos preparados. |
| 06 | Filtros, conversión a USD, integración y tratamiento de variables de destino; conserva VA/CI sin imputar. |
| 07 | Exploración de la base final, correlación y pairplot. |
| 08 | Árbol, Random Forest, Gradient Boosting, umbral y dos gráficos SHAP. |
| 09 | Puntajes de 2024 y rankings por par y producto. |


## Resultados 
Las brechas corresponden a referencias estimadas dentro de la muestra. El ranking constituye una herramienta exploratoria de acceso a mercados, costos logísticos y condiciones empresariales.

## Fuentes principales

- [BACI:](https://www.cepii.fr/DATA_DOWNLOAD/baci/baci_webpage.html) flujos comerciales internacionales y catálogos de países y productos. 
- [CEPII Gravity:](https://www.cepii.fr/CEPII/en/bdd_modele/presentation.asp?id=8) información geográfica y variables utilizadas en el modelo gravitacional.
- Banco Mundial — WDI y WGI: indicadores económicos, demográficos, de desarrollo y estabilidad política.
- Naciones Unidas — M49: clasificación geográfica de países y territorios.
- DANE: información sectorial de valor agregado y consumo intermedio.
- Banco Mundial — Pink Sheet: tasa representativa del mercado y precios internacionales del petróleo Brent y del café arábica.
- OMC y OCDE: información de membresías.E. 

