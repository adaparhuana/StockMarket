

<a href="https://imgbb.com/"><img src="https://i.ibb.co/crQFVxr/P2.png" alt="space" width="1000" height="450"></a>


<!-- TABLA DE CONTENIDO -->
## Indice
<details open="open">
  <summary>Tabla de contenido: </summary>
  <ol>
    <li>
      <a href="#Introducción">Introducción</a>
    </li>
    <li>
      <a href="#Objetivo">Objetivo</a>
    </li>
    <li>
      <a href="#EDA">EDA</a>
    </li>
    <li>
      <a href="#Stack-tecnológico">Stack tecnológico</a>
    </li>       
  </ol>
</details>


## Introducción

Como parte de la etapa de labs de Ciencia de Datos en Henry, se nos asignó el rol de Data Analyst. 

El proyecto consistió en proporcionar una recomendación de inversión para una empresa interesada en acciones del índice SP500 en el mercado bursátil. Además, nos solicitaron un análisis de los eventos ocurridos desde el año 2000 en este mercado, evaluando tanto impactos positivos como negativos. 

El objetivo fue realizar un análisis de los datos, identificando patrones, outliers y posibles anomalías para brindar información valiosa a la empresa para tomar decisiones de inversión.

## Objetivo

### Situación del mercado bursátil
El mercado bursátil ha experimentado diferentes tendencias y volatilidades en los últimos 23 años, aquí algunas hechos más relevantes:

1. El auge de las empresas de tecnología: En la década de 1990, hubo un auge en las empresas de tecnología, especialmente en el sector de Internet. Esto llevó a un aumento en el índice NASDAQ, que alcanzó su punto máximo en marzo de 2000 antes de sufrir una corrección significativa.

2. La recesión de 2001: Después del auge de las empresas de tecnología, el mercado bursátil sufrió una caída significativa en 2001 debido a la recesión económica.

3. La burbuja inmobiliaria: A mediados de la década de 2000, hubo un aumento en la inversión en bienes raíces que llevó a una burbuja inmobiliaria. Sin embargo, esta burbuja estalló en 2008, lo que llevó a la Gran Recesión.

4. La recuperación después de la Gran Recesión: Después de la Gran Recesión, el mercado bursátil se recuperó significativamente. El índice S&P 500 alcanzó un máximo histórico en septiembre de 2018.

5. La pandemia de COVID-19: La pandemia de COVID-19 tuvo un impacto significativo en el mercado bursátil en 2020, con una caída significativa en marzo de 2020, seguida de una rápida recuperación.

En resumen, el mercado bursátil ha experimentado muchas tendencias y volatilidades en los últimos 23 años, pero ha demostrado ser bastante resistente y capaz de recuperarse de las caídas significativas.

### Dashboard

[Dashboard Stock Market](https://drive.google.com/file/d/1_E5f8k3WCu7c33-9eIloDEBn0Xh75fEE/view?usp=share_link)


### Recomendación de inversión

<a href="https://imgbb.com/"><img src="assets\c_medias.png" alt="space" width="1000" height="450"></a>

## EDA
EL proceso de EDA consistió en utilizar técnicas y herramientas para analizar y explorar los datos con el objetivo de obtener información útil para realizar la recomendación de inversión. 

En los notebooks EDA_S&P500 y EDA_ETF encontrarán toda los pasos e instrucciones necesarias para para realizar el procesamiento de los datos.

DICCIONARIO DE DATOS

| Features | Descripción | 
| --- | --- | 
| Open | Precio de apertura de una acción en un día determinado.| 
| High | Precio más alto alcanzado por una acción en un día determinado. | 
| Close | Precio de cierre de una acción en un día determinado.| 
| Adj Close | Precio de cierre ajustado de una acción en un día determinado, teniendo en cuenta cualquier evento que pudiera afectar el precio de la acción, como dividendos, divisiones de acciones, etc. | 
| Volume | Número total de acciones negociadas en un día determinado. | 
| Symbol | código de identificación único utilizado para identificar una acción en particular. | 
| GICS Sector | El sector GICS (Global Industry Classification Standard) al que pertenece una acción en particular. | 
| GICS Sub-Industry | La sub-industria GICS a la que pertenece una acción en particular.  | 

### Análisis Exploratorio S&P500

<a href="https://imgbb.com/"><img src="assets\gspc.png" alt="space" width="1000" height="450"></a>

*En los precios del índice S&P500, vemos que para el 2009 el valor High estuvo por debajo de la media durante mucho tiempo, por lo que podemos decir que hubo algunas pérdidas debido a  momentos de mayor incertidumbre.*

<a href="https://imgbb.com/"><img src="assets\r_day.png" alt="space" width="1000" height="450"></a>

*Se encontraron patrones regulares y predecibles en el comportamiento de las acciones del índice SP500. Los casos más comunes han sido los efectos de los días jueves (el rendimiento de los jueves es en promedio mayor al resto de días de la semana). Siento el mejor día para invertir. Un efecto contrario a los lunes.*

<a href="https://imgbb.com/"><img src="assets\r_sector.png" alt="space" width="1000" height="450"></a>

*Durante los últimos años, el sector de tecnología ha experimentado un crecimiento constante en su rendimiento acumulativo, superando a otros sectores. Esto podría sugerir una fase de auge en la industria tecnológica durante ese período.*

<a href="https://imgbb.com/"><img src="assets\c_sector.png" alt="space" width="1000" height="450"></a>

*En el S&P 500, los sectores con la mayor cantidad de empresas son el sector industrial, el sector financiero, el sector tecnológico y el sector de Salud.*

*La cantidad de empresas que conforman un sector en el S&P 500 resulta de la diversidad inherente a la economía y al mercado financiero, así como de la amplia variedad de industrias y segmentos*

<a href="https://imgbb.com/"><img src="assets\sharpe.png" alt="space" width="1000" height="450"></a>

## Stack tecnológico

+ Python
+ Power BI
+ Yfinance
+ Web Scrapping
