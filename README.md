# AnestCalc

Aplicación móvil para anestesiólogos enfocada en cálculos críticos de dosis, vía aérea y riesgos en tiempo real dentro del quirófano. Este repositorio contiene la especificación inicial del MVP y la guía de alcance para el desarrollo en Flutter con enfoque **offline-first** y **modo oscuro obligatorio**.

## Objetivo del proyecto
- Proveer cálculos matemáticos médicos precisos y rápidos en un entorno clínico.
- Priorizar una UX/UI clara para situaciones de estrés.
- Desplegar en Android (Play Store) e iOS (App Store).

## Alcance del MVP
### Pantallas principales
- **Dashboard (Pantalla principal)** con header global de datos del paciente (Peso, Edad, Talla, Sexo).
- **Módulos interiores (6):**
  1. **Dosis:** Inducción, TIVA y mezclas vasoactivas.
  2. **Sangre:** Pérdida permisible, ajuste de Hb por altitud (geolocalización opcional), compatibilidad.
  3. **Vía Aérea:** Selección de tubos/mascarillas y checklist VAD.
  4. **Riesgo:** Escalas interactivas (ASA, Apfel).
  5. **Insulina:** Protocolos de corrección de glucosa.
  6. **Condiciones:** Guía de consulta rápida tipo acordeón.
- **Menú lateral:** Perfil del autor, Bibliografía, Disclaimer legal.

## Requerimientos técnicos
- **Sin backend complejo:** lógica matemática local; sin login en fase 1.
- **Offline-first:** funcionamiento completo sin conexión.
- **Modo oscuro por defecto** con alto contraste.
- **Código fuente documentado** y modular.

## Material del cliente
- Logo y paleta de colores definidos.
- Documento maestro con fórmulas médicas, constantes y algoritmos lógicos.

## Entregables esperados
- Diseño UX/UI consistente con estrés clínico (componentes grandes, jerarquía clara).
- Implementación Flutter (o tecnología equivalente) con navegación modular.
- Documentación técnica y notas de uso.

## Cronograma estimado
- **4 a 6 semanas** para MVP.

## Próximos pasos sugeridos
1. Importar el documento maestro con fórmulas y constantes.
2. Definir estructura de datos del paciente global.
3. Prototipar UI en modo oscuro y validar con el cliente.
4. Implementar módulos por prioridad clínica.
