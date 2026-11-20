**Título: Validando hipótesis de negocio con pruebas estadísticas**

**¿Una nueva versión de la página de inicio puede mejorar la conversión y el valor económico por usuario?** En este proyecto analicé un experimento A/B que comparaba dos versiones de una *landing page*, con el objetivo de evaluar sus resultados y convertir la evidencia estadística en recomendaciones útiles para el negocio.

- **Problema:** Comparar el desempeño de las versiones A y B sin basarse únicamente en diferencias observadas en los datos. Para ello, era necesario elegir pruebas estadísticas apropiadas e interpretar sus resultados considerando las métricas del negocio.
- **Qué hice:** Exploré y validé los datos del experimento, comparé las métricas entre ambos grupos y apliqué pruebas estadísticas según el tipo de variable analizada. Utilicé pruebas de proporciones y de independencia para métricas categóricas, y pruebas de hipótesis para comparar variables numéricas. También visualicé los resultados para facilitar su interpretación.
- **Resultado o aprendizaje:**
    
    **Comparación de página (A vs B)**
    
    - **Gasto promedio por usuario convertido:** fue mayor en B (68.745) que en A (61.087). La diferencia fue estadísticamente significativa (prueba t, *p* = 3.63 × 10⁻²¹).
    - **Tasa de conversión:** B convirtió al 15.96% de sus usuarios (3,194 de 20,018), frente al 12.57% de A (2,512 de 19,982). La diferencia de 3.39 puntos porcentuales fue estadísticamente significativa (prueba z, *p* = 3.76 × 10⁻²²).
    
    **Conclusión:** En este experimento, la página B obtuvo una mayor tasa de conversión y un mayor gasto promedio entre quienes convirtieron.
    
    **Resultados por segmento**
    
    - **Fuente de tráfico:** Email tuvo la tasa de conversión más alta (14.99%), seguido de Ads (14.74%), Referral (13.88%) y Organic (13.79%). La asociación entre canal y conversión fue significativa (χ² = 8.662, *p* = 0.034), aunque las diferencias entre tasas fueron pequeñas. Antes de reasignar presupuesto, conviene considerar también el volumen, los costos y los ingresos de cada canal.
    - **Tipo de usuario:** la conversión fue similar para usuarios nuevos (14.36%) y recurrentes (14.09%). No se encontró una asociación estadísticamente significativa entre el tipo de usuario y la conversión (χ² = 0.513, *p* = 0.474).
    
    Las visualizaciones complementaron las pruebas estadísticas y facilitaron la comunicación de los resultados. En conjunto, el análisis permitió comparar las páginas y formular recomendaciones basadas en la evidencia, distinguiendo la significancia estadística de la relevancia comercial.
    
- **¿Qué demuestra este proyecto?**
    
    Este trabajo muestra mi capacidad para diseñar un flujo de análisis de experimentos A/B, seleccionar y aplicar pruebas estadísticas, interpretar resultados con criterio y presentar conclusiones accionables para apoyar la toma de decisiones.
    

**🛠️ Skills:** 

- **Jupyter Notebook**
- **Python** | Pandas | numpy | seaborn | matplotlib | scipy.stats( chi2_contingency, ttest_ind, levene) | statsmodels.stats.proportion (proportions_ztest)
