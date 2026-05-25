# 🚲 Análisis de Clientes Adventure Works — Tableau

## Objetivo
Identificar el perfil de los clientes de Adventure Works, 
analizar patrones de compra de bicicletas y segmentar 
clientes por ingreso, ocupación y grupo etario.

## 🔗 Ver dashboard interactivo
https://public.tableau.com/views/EntregaFinal_Carbajal/Documentacin?:language=es-

## Herramientas
- Tableau Desktop / Tableau Public
- Fuente: Kaggle — Adventure Works Dataset

## Vistas del dashboard
- KPI Clientes: 18,361 clientes totales
- Mapa Clientes: distribución geográfica por país
- Ingresos por País: benchmark de ingreso anual promedio
- Educación y Género: treemap de segmentación demográfica
- Compradores por Ocupación: análisis de conversión por ocupación
- Ingreso vs Gasto: correlación entre ingreso anual y gasto mensual
- Gasto por Edad: distribución por grupo etario

## Campos calculados creados
- Segmento de Ingresos (Alto/Medio/Bajo/Muy Bajo)
- Estado Comprador (Compró/No Compró)
- Grupo Etario (Joven/Adulto/Adulto Mayor/Senior)
- Promedio Gasto por País (LOD Fixed)

## Conclusiones
1. Clientes con ocupación Professional tienen mayor gasto mensual
2. El segmento de ingresos alto concentra más compradores
3. Australia y Estados Unidos lideran en cantidad de clientes
4. Adultos de 30-44 años son los compradores más activos
5. Existe correlación positiva entre ingreso anual y gasto mensual

## Fuente de datos
Kaggle — Adventure Works Dataset
AWCustomers.csv (18,361 clientes) + AWSales.csv
