# Dashboard de Accidentes en Carreteras Federales (2018–2020)

Este dashboard fue realizado para el evento **Acelerador de Carrera con Power BI** organizado por **Daxus Latam**.

Analizo los accidentes en carreteras federales entre 2018 y 2020 para identificar patrones y tendencias útiles para la prevención y la toma de decisiones en seguridad vial.

---

## Datos principales

- 🚧 Total de accidentes analizados: **60,531**  
- ⚰️ Fallecidos: **4,062**  
- 🤕 Personas heridas: **71,260**  
- 🚑 Eventos con 3 o más víctimas: **103**

---

## Visualizaciones incluidas

- Las 7 causas más comunes de accidentes  
- Tendencias mensuales  
- Distribución por día y franja horaria  
- Eventos por estación del año  
- Mapa geográfico con IconMap  

---

## Herramientas utilizadas

- Power BI - DAX
- Power Query  
- Flaticon (para íconos)  
- Software de diseño vectorial para el layout  

---

## Diseño

El dashboard apuesta por un diseño limpio, minimalista y claro, destacando los datos más importantes y con foco en la usabilidad.

---

##  Modelado con DAX

El modelo incluye medidas básicas y personalizadas usando DAX, enfocadas en facilitar el análisis de causas, víctimas y distribución temporal de los accidentes.  
Medidas realizadas:

* Cantidad Accidentes = COUNTROWS(registro_acidente)

* Cantidad Accidentes > 3 Victimas = COUNTROWS(FILTER(registro_acidente, [Cantidad Fallecidos] >= 3))

* Cantidad Fallecidos = SUM(registro_acidente[Muertos])
 
* Cantidad Heridos = SUM(registro_acidente[Heridos])

---

## Contacto

Para más información o consultas, podés contactarme a través de mis redes o por email (opcional).

(Linkedin)[https://www.linkedin.com/in/gpelo-data/]

Correo: gaston.pelo.contacto@gmail.com
---
