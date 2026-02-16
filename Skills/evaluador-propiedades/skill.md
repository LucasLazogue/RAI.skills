# Evaluador de Propiedades Inmobiliarias

## Descripción
Proporciona análisis detallado de propiedades inmobiliarias incluyendo ubicación, infraestructura, beneficios fiscales y riesgos geográficos.

## Capacidades
- Evaluación de ubicación geográfica y accesibilidad
- Análisis de beneficios fiscales por región
- Identificación de riesgos ambientales y naturales
- Verificación de disponibilidad de servicios
- Comparación de opciones inmobiliarias
- Generación de reportes ejecutivos

## Información que proporciona

### Ubicación
- Coordenadas geográficas
- Acceso a vías principales
- Proximidad a centros urbanos
- Distancia a puertos/aeropuertos
- Conectividad de transporte

### Beneficios Fiscales
- Incentivos por zona económica especial
- Deducibles por inversión
- Exoneraciones regionales
- Beneficios tributarios por actividad
- Período de vigencia de beneficios

### Riesgos Asociados
- Riesgos sísmicos y geológicos
- Riesgos climáticos (inundaciones, huracanes)
- Estabilidad política y seguridad
- Regulaciones ambientales
- Restricciones de uso de suelo

### Infraestructura
- Disponibilidad de servicios (agua, energía, internet)
- Cercanía a hospitales y educación
- Zonas comerciales e industriales
- Estado de vías de acceso

## Información Requerida

- **region**: Región a evaluar
- **tipo_terreno**: agrícola, comercial, industrial, mixto
- **area_hectareas**: Extensión del terreno
- **presupuesto**: Presupuesto disponible
- **actividad_proyectada**: Tipo de actividad a desarrollar

## Output Esperado

```json
{
  "ubicacion": {
    "region": "...",
    "accesibilidad": "Excelente|Buena|Regular|Limitada",
    "distancia_capital": "km",
    "vias_principales": "..."
  },
  "beneficios_fiscales": {
    "zona_especial": "Si|No",
    "incentivos_disponibles": ["..."],
    "ahorro_estimado": "porcentaje"
  },
  "riesgos": {
    "nivel_riesgo": "Alto|Medio|Bajo",
    "factores_principales": ["..."],
    "seguros_recomendados": ["..."]
  },
  "infraestructura": {
    "servicios": ["agua", "energía", "internet"],
    "certificaciones": ["..."]
  },
  "viabilidad_general": "Viable|Condicionado|No Viable",
  "observaciones": "Detalle de factores críticos"
}
```

## Metadatos
- **Confiabilidad**: Alta
- **Tiempo de respuesta**: 2-5 segundos
- **Cobertura**: Nacional
- **Actualización**: Mensual

## Limitaciones
- Información pública solamente
- No evalúa capacidad de crédito
- Riesgos políticos estimativos
- Precios de referencia aproximados
