# AGENT.md

## Propósito del agente
Eres un asistente de IA diseñado para trabajar con este proyecto específico. Debes conocer la estructura de carpetas, los datos disponibles y los skills definidos en la carpeta `.agent`.

## Estructura del proyecto
- `.agent/`
  - `analista-datos-negocio.md`: skill para análisis de datos de negocio, limpiezas, KPIs, tendencias e insights.
  - `creador-contenido-ventas.md`: skill para generar copy y mensajes persuasivos de ventas.
  - `diseñador-clases-creativas.md`: skill para diseñar clases pedagógicas y materiales didácticos.
- `Data/raw/`
  - `Datos_Ventas_Prueba_BI_Agente - Datos_Ventas_Prueba_BI_Agente.csv`: datos crudos para procesos de análisis de datos.
- `Data/ventas/`
  - `Inventario de Productos.csv`: datos para el creador de contenido de ventas.
- `Informes/`
  - Carpeta destino para resultados del proyecto, reportes e informes generados.

## Cómo debes trabajar
1. Lee primero los archivos en `.agent/` para entender el propósito, las restricciones y el estilo requerido.
2. Cuando el objetivo sea análisis de negocio o BI, usa los datos en `Data/raw/`.
3. Cuando el objetivo sea generar contenidos comerciales o ventas, usa los datos en `Data/ventas/`.
4. Organiza los entregables y resultados en `Informes/`.

## Flujo recomendado
- Para análisis de datos:
  - Auditoría y limpieza de datos.
  - Cálculo de KPIs clave.
  - Detección de tendencias, anomalías y puntos de mejora.
  - Redacción de insights claros, con interpretación y recomendación.
- Para contenido de ventas:
  - Identificar pain points y beneficios.
  - Usar un tono cercano y persuasivo.
  - Formatear textos con mensajes claros, llamados a la acción y estructura legible.

## Reglas de estilo
- No entregues solo números. Explica el significado y la implicación para el negocio.
- Si los datos son insuficientes, señala claramente qué falta y qué se necesita.
- Mantén el español claro, directo y profesional.
- Prioriza la accionabilidad: cada hallazgo debe sugerir un paso concreto.

## Resultado esperado
- Informes en `Informes/` que contengan:
  - Resumen ejecutivo.
  - Estado de los datos.
  - Hallazgos clave.
  - Recomendaciones prácticas.

## Notas adicionales
- La carpeta `.agent` contiene los prompts y skills que guían tu comportamiento.
- Usa el archivo `Datos_Ventas_Prueba_BI_Agente - Datos_Ventas_Prueba_BI_Agente.csv` para análisis de ventas y métricas.
- Usa `Inventario de Productos.csv` para crear contenido de ventas, mensajes y presentaciones de producto.
