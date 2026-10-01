# Concepto preliminar: Sistema Integrado de Videovigilancia, Drones y Analítica para la provincia de Sullana

> Borrador de trabajo derivado de `01-diagnostico-provincia-sullana.md`.
> Las cantidades de equipos son **hipótesis de dimensionamiento**. Se validarán con el levantamiento de campo y el mapa de calor delictivo.

## 1. Problema que resuelve

El diagnóstico identifica cinco problemas:

- **Sicariato.** Sullana concentra casi la mitad de los homicidios de Piura, y 9 de cada 10 son con arma de fuego.
- **Extorsión en crecimiento.** Incluye ataques con explosivos y cupos a obras, comercios, colegios y transporte.
- **Frontera y economía ilícita.** Corredores fronterizos (Lancones y la vía Sullana–La Tina) usados para armas, droga, contrabando y trata.
- **Videovigilancia que no funciona.** Pocas cámaras, muchas inoperativas, sin integración con la PNP y sin personal capacitado.
- **Desconfianza institucional.** Hay casos de corrupción policial documentados.

El proyecto no es "poner cámaras". Es darle a las autoridades **capacidad de detectar, verificar, despachar e investigar**, con evidencia trazable.

## 2. Objetivos medibles (propuesta)

| Objetivo | Indicador | Línea de base |
|---|---|---|
| Reducir homicidios por arma de fuego en las zonas intervenidas | Homicidios SINADEF por sector | 48 en enero–setiembre de 2026 |
| Reducir el tiempo de respuesta | Minutos desde la alerta hasta la llegada de la unidad | Por levantar |
| Aumentar la identificación de vehículos y motos usados en delitos | Coincidencias LPR con requisitorias de vehículos o placas | 0 (no existe LPR) |
| Disponibilidad del sistema | Porcentaje de cámaras operativas | ~70% en Sullana y ~20% en Bellavista |
| Aportar evidencia a la Fiscalía | Número de clips entregados con cadena de custodia | Por levantar |

## 3. Componentes

### 3.1 Capa de sensores

1. **Cámaras fijas urbanas** (domo PTZ y bullet) en puntos críticos.
   - Zonas: El Obrero, Nueva Sullana, Santa Teresita, AH Manuel Seoane, AH Jesús María, Nueve de Octubre, centro de Sullana, mercados y Bellavista.
   - Lo primero es **rehabilitar las 54 cámaras existentes** y las 35 de Bellavista.
2. **Pórticos de lectura de placas (LPR / ANPR)** en los accesos a la provincia:
   - Panamericana Norte (entrada sur y salida a Talara);
   - vía a Paita;
   - vía Sullana–Tambogrande–La Tina;
   - puentes sobre el río Chira;
   - acceso a Lancones.
   - Objetivos: requisitorias, vehículos robados y patrones de motos usadas en sicariato.
3. **Drones (RPAS):**
   - **Urbanos de respuesta táctica:** acuden a una alerta y siguen al vehículo en fuga.
   - **De patrullaje rural y fronterizo** con cámara térmica, para Lancones, Marcavelica y el valle del Chira.
   - Se coordinarán con la PNP y el Ejército, que ya tienen antecedentes de cooperación local.
4. **Botones de pánico y cámaras comunitarias:**
   - para comercios, colegios y mototaxis (gremios);
   - integración opcional de cámaras privadas.
5. **Detección acústica de disparos** (opcional, piloto) en los sectores con más sicariato.

### 3.2 Analítica (IA)

- Lectura de placas con alertas contra listas de requisitorias.
- Detección de eventos:
  - personas armadas;
  - aglomeraciones;
  - **motocicleta con dos ocupantes en patrón sospechoso**, que es el modus operandi típico del sicariato;
  - vehículo detenido frente a un objetivo protegido.
- Búsqueda forense por atributos: color, tipo de vehículo, vestimenta.
- **Reconocimiento facial: solo como módulo opcional y condicionado.** Es dato sensible según el DS 016-2024-JUS. Requiere evaluación de impacto, base legal, listas controladas (requisitorias judiciales) y auditoría.
- Mapas de calor y análisis predictivo de zonas y horarios, a partir de SIDPOL, SINADEF y los incidentes del propio sistema.

### 3.3 Centro de mando provincial (C2 / C4 provincial)

- Sala de monitoreo con operadores por turnos y un supervisor de la PNP en sitio.
- Plataforma VMS / PSIM con despacho integrado a serenazgo, PNP (105) y bomberos.
- **Interoperabilidad con el C4 PNP y la plataforma del Mininter (Amper).** Es un requisito, no un complemento.
- Nodos distritales (Bellavista, Marcavelica, Querecotillo, Lancones) conectados al centro de mando.
- Respaldo eléctrico y de enlaces: fibra, radioenlaces y 4G/5G de respaldo.

### 3.4 Gobernanza, transparencia y anticorrupción

- Registro inmutable de accesos. Cada consulta, búsqueda de placa y exportación queda auditada.
- Cadena de custodia digital para entregar evidencia a la Fiscalía.
- Protocolo de datos personales: ley 29733, retención definida y evaluación de impacto.
- Comité de seguimiento dentro del COPROSEC, con indicadores públicos trimestrales.

### 3.5 Operación y mantenimiento sostenible

Es la causa principal del fracaso de los proyectos anteriores en Piura y Sullana. El proyecto debe incluir:

- contrato de mantenimiento con niveles de servicio (SLA), con una disponibilidad mínima de cámaras de 95%;
- capacitación y certificación de operadores;
- fuente de financiamiento recurrente identificada desde el inicio: presupuesto municipal, transferencias del Mininter u operación incluida en la OxI.

## 4. Despliegue por fases (propuesta)

| Fase | Alcance | Plazo estimado |
|---|---|---|
| 0. Diagnóstico de campo | Inventario de cámaras, mapa de calor con la Divopus y REDES, sitios de LPR, estudio de conectividad, levantamiento de línea base | 4–6 semanas |
| 1. Piloto de impacto rápido | Rehabilitar cámaras existentes, centro de mando mínimo, 2 drones urbanos, LPR en 3 accesos, integración con la PNP | 3–4 meses |
| 2. Expansión urbana | Sullana y Bellavista: cámaras nuevas, analítica, botones de pánico | 6–9 meses |
| 3. Cobertura provincial y frontera | Distritos rurales, drones térmicos, LPR en el corredor Sullana–La Tina y Lancones | 9–12 meses |
| 4. Operación y mejora continua | SLA, indicadores, analítica predictiva | Permanente |

## 5. Vías de financiamiento

- **Obras por Impuestos (OxI).** La municipalidad ya anunció un proyecto de S/25 millones. Hay que identificar el CUI y la empresa financista y evaluar el encaje.
- Transferencias del Mininter / fondos de seguridad ciudadana y el programa "Barrio Seguro", ya lanzado en Sullana en noviembre de 2024.
- Gobierno Regional de Piura.
- Cooperación con el sector agroexportador y portuario, que tiene interés en la seguridad del corredor Chira–Paita.

## 6. Próximos pasos

1. Validar el diagnóstico con actores locales: Municipalidad, Divopus Sullana, COPROSEC, Fiscalía y gremios.
2. Revisar en Invierte.pe y ProInversión los proyectos en curso (OxI de S/25 millones y convenio de 194 cámaras) para no duplicar.
3. Definir el interlocutor según el resultado electoral del 4 de octubre de 2026, con la transición en enero de 2027.
4. Preparar la presentación ejecutiva y el presupuesto referencial por fase.
