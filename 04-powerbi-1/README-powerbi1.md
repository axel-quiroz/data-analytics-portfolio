# Mini-Dashboard Power BI 1

## Objetivo  
Familiarizarme con Power BI Desktop: importar datos, crear medidas y visualizaciones.

## Archivo  
- `mini-dashboard1.pbix`

## Cómo abrir  
1. Instalar Power BI Desktop (gratuito).  
2. Abrir `mini-dashboard1.pbix`.  
3. Revisar hojas “Data”, “Model” y “Report”.

## Detalles técnicos  
- **Fuente**: CSV de ejemplo de energía.  
- **Medidas DAX**:  
  - `TotalEnergy = SUM(Data[Energy])`  
  - `AvgPerDay = AVERAGE(Data[EnergyDaily])`

## Conclusiones  
- Aprendido el flujo ETL + modelado + visualización.  
- Retos al crear relaciones uno-a-muchos.
