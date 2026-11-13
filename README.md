# Proyecto brechas potenciales de exportación de Colombia - Modelo gravitacional estructural y Machine Learning

### **Título:** Identificación del comercio potencial y diversificación exportadora para productos No minero-energéticos de Colombia.  

### **Integrantes:**
- Andrés Felipe Linares
- Juan Esteban Roa 
- Juan Pablo Lozano 

## Descripción del Proyecto
El proyecto consiste en un ejercicio econometrico con una posterior aplicación de Machine learning, que consisite en identificar la relación producto–país destino de la canasta exportadora colombiana no minero-energética que presentan la brecha de comercio potencial no realizado de Colombia medido por un modelo gravitacional estructural, para posteriormente mediante un arbol de decisión (Rambom Forest) el modelo prediga que variables incluidas tienen una mayor repercución sobre la probabilidad de disminuir la brecha existente.

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



## Fuentes

Fuentes principales: [BACI](https://www.cepii.fr/DATA_DOWNLOAD/baci/baci_webpage.html), [CEPII Gravity](https://www.cepii.fr/CEPII/en/bdd_modele/presentation.asp?id=8), Banco Mundial WDI/WGI, Naciones Unidas M49, DANE. 

