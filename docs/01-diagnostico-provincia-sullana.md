# Diagnóstico de seguridad: provincia de Sullana (Piura, Perú)

**Fecha de corte:** 1 de octubre de 2026
**Objetivo:** reunir los datos que sustentan un proyecto de videovigilancia, drones y analítica con respuesta coordinada de las autoridades.

## Convenciones

- **[SULLANA]** es un dato de la provincia o de uno de sus distritos. **[PIURA]** es un dato del departamento o región de Piura.
- **(NV)** marca un dato no verificado en fuente primaria. Antes de usarlo en una presentación formal hay que contrastarlo.
- Hay dos fuentes de homicidios y no deben mezclarse:
  - **SINADEF** (Minsa) cuenta defunciones.
  - **SIDPOL** (Mininter / PNP) cuenta denuncias.
  - Los totales de una y otra son muy distintos.

---

## 1. Resumen ejecutivo

1. **Sullana es el epicentro de la violencia homicida de Piura.**
   - Entre enero y el 14 de setiembre de 2026 registró **48 homicidios** (SINADEF). Son el **45,7% de toda la región**, con aproximadamente una sexta parte de su población.
   - Frente al mismo periodo de 2025 (29 homicidios), el aumento es de **+65,5%**.
   - El **89,6%** de esos homicidios se cometió con **arma de fuego**.
2. **La tasa de homicidios más que duplica el promedio nacional.**
   - 2025: 54 homicidios entre unos 356 000 habitantes, alrededor de **15 por 100 000** (cálculo propio).
   - Promedio nacional 2025: unos 6,4 por 100 000 (2 218 homicidios, SINADEF).
   - Si 2026 sigue al ritmo actual, Sullana cerraría el año cerca de **19 por 100 000**.
3. **La extorsión es el delito de mayor crecimiento.**
   - Las denuncias de enero a julio pasaron de **194 en 2023 a 704 en 2025** (×3,6).
   - Entre enero y setiembre de 2025 la tasa fue de **256 por 100 000**, la más alta de Piura. En 2019 era de 12.
   - Hubo ataques con explosivos a viviendas y comercios, amenazas a colegios y asesinatos por cobro de cupos en obras.
4. **Piura es la segunda región del país en trata de personas.**
   - En 2024 tuvo 218 casos fiscales (15,7% del país) y 255 víctimas.
   - En Sullana operan bares y night clubs con víctimas menores de edad y mujeres extranjeras en situación irregular.
5. **Sullana está en el corredor fronterizo del crimen.**
   - **Lancones** limita con Ecuador.
   - La vía Sullana–La Tina conecta con el puente de Macará.
   - Se documentan rutas informales (El Alamor–Lancones–Sullana) para droga, armas, contrabando y migración irregular.
   - Ejemplo: en diciembre de 2025 se incautaron **3,4 toneladas de cocaína** camufladas en banano orgánico en la carretera Sullana–La Tina.
6. **El Estado ha respondido sobre todo con estados de emergencia, con resultados limitados.** Hubo un estado de emergencia en 2023 y otros cuatro decretos en 2026. El DS 126-2026-PCM está vigente desde setiembre de 2026, y aun así la violencia continúa.
7. **La videovigilancia municipal existente es escasa y está deteriorada.**
   - Sullana tiene 54 cámaras, con entre 12 y 15 inoperativas según la Contraloría y la prensa.
   - En Bellavista, el 80% de las cámaras están inoperativas (28 de 35), sin interconexión y con personal no capacitado.
   - Hay corrupción policial documentada: en noviembre de 2025 se dictó prisión preventiva al comisario de El Obrero.

**Conclusión para el proyecto.** No basta con instalar cámaras. Hace falta un **sistema integrado** que incluya:
- sensores: cámaras fijas, lectoras de placas (LPR) y drones;
- analítica;
- un centro de mando conectado a la PNP (C4 / 105);
- protocolos de respuesta;
- **mantenimiento y operación sostenibles**, que es donde han fallado todos los proyectos anteriores en Piura.

---

## 2. Territorio y población

| Indicador | Dato | Fuente |
|---|---|---|
| Superficie | 5 423,61 km² | [Wikipedia](https://es.wikipedia.org/wiki/Provincia_de_Sullana) |
| Población, Censo 2017 | 311 454 habitantes censados | INEI |
| Población proyectada 2025 | 356 232 | Ficha del Observatorio Nacional de Seguridad Ciudadana (ver §3) |
| Población, Censos 2025 | unos 350 949, de los cuales el distrito de Sullana tiene 196 103 y Bellavista 38 370 (NV) | [CityPopulation](https://citypopulation.de/en/peru/piura/admin/2006__sullana/) |
| Límites | Norte: Tumbes. Sur: Piura. Este: Ecuador y Ayabaca. Oeste: Paita y Talara | Wikipedia |

**Distritos (Censo 2017):**

| Distrito | Población | Superficie | Nota para el proyecto |
|---|---|---|---|
| Sullana | 169 335 | 488 km² | Núcleo urbano. Incluye El Obrero, Nueva Sullana, Santa Teresita y Manuel Seoane, todas zonas con sicariato |
| Bellavista | 37 530 | 3,9 km² | Conurbado con Sullana, muy denso. 80% de sus cámaras inoperativas |
| Marcavelica | 29 569 | 1 688 km² | Zona agrícola. Triple crimen de 2024 (Samán Chico). Trata en El Monterón |
| Querecotillo | 26 395 | 270 km² | Valle del Chira |
| Ignacio Escudero | 20 479 | 307 km² | Panamericana Norte hacia Talara |
| Lancones | 13 028 | 2 189 km² | **Frontera con Ecuador** (Zapotillo, El Alamor). Rural y extenso; candidato natural a drones |
| Miguel Checa | 9 036 | unos 449 km² (NV) | |
| Salitral | 7 047 | 28 km² | |

**Corredores clave:**
- Panamericana Norte (PE-1N).
- Ramal Sullana–Tambogrande–Las Lomas–Suyo–La Tina (puente Macará), parte del Eje Vial Binacional Piura–Guayaquil.
- Conexión con el **puerto de Paita**, que movió 427 490 TEU en 2025 y concentra el 49% de las agroexportaciones del país ([Revista Economía](https://www.revistaeconomia.com/puerto-de-paita-marca-un-record-historico-en-movimiento-de-contenedores/)). Es la salida natural del narcotráfico que se camufla en la fruta.
- **Río Chira** y reservorio de Poechos.
- Ecuador cerró el paso Macará–La Tina y el de Lancones–Zapotillo (cierre total desde el 1 de julio de 2026). Luego anunció la reapertura con despliegue de seguridad ([Infobae 06/07/2026](https://www.infobae.com/peru/2026/07/06/frontera-peru-ecuador-restricciones-en-el-puente-macara-paralizan-el-comercio-y-mantienen-en-incertidumbre-a-cientos-de-familias/)).
- La Defensoría documentó rutas irregulares: El Alamor–Lancones–Sullana y Macará–La Tina–Suyo–Las Lomas ([El Comercio 2019](https://elcomercio.pe/peru/piura/venezolanos-peru-venezuela-rutas-ilegales-migracion-aumenta-ingreso-irregular-extranjeros-peru-noticia-ecpm-678471-noticia/)).

**Socioeconomía:**
- **[PIURA]** Pobreza monetaria de 31,9% en 2024 ([IPE](https://ipe.org.pe/piura-registra-su-tercera-mayor-tasa-de-pobreza-de-los-ultimos-10-anos/)).
- **[PIURA]** Informalidad laboral de 63,9% ([El Tiempo](https://eltiempo.pe/local/informalidad-en-piura-alcanza-los-639/)).
- La economía se basa en el banano orgánico del valle del Chira (unas 16 500 ha certificadas en la región), el comercio y el transporte.
- Los mototaxis son un sector masivo y en gran parte informal: se estiman entre 22 000 y 30 000. Son blanco frecuente de extorsión.
- **[PIURA]** Hay unos 25 000 migrantes venezolanos en la región (NV, sin fecha).

---

## 3. Criminalidad: cifras oficiales

### 3.1 Homicidios

**SINADEF (defunciones)**

Cifras de [La República, 19/09/2026](https://larepublica.pe/sociedad/2026/09/19/casi-8-de-cada-10-asesinatos-en-piura-se-cometen-con-armas-de-fuego-exjefe-policial-advierte-abandono-del-estado-700036), salvo donde se indique otra fuente.

| Ámbito | Periodo | Homicidios | Nota |
|---|---|---|---|
| **[SULLANA]** | 01/01–14/09/2026 | **48** | +65,5% frente a 2025 (29). 89,6% con arma de fuego |
| **[SULLANA]** | Año 2025 | 54 | Unos 15 por 100 000 (cálculo propio) |
| **[PIURA]** | 01/01–14/09/2026 | 105 | Por provincia: Sullana 48, Piura 34, Talara 10, Paita 6, Ayabaca 3, otras 4 |
| **[PIURA]** | Año 2025 | 151–154 | 4.ª región del país en números absolutos. Total nacional: 2 218 ([Infobae 31/12/2025](https://www.infobae.com/peru/2025/12/31/peru-cierra-el-2025-como-el-ano-mas-sangriento-de-su-historia-mas-de-2200-asesinatos-fueron-registrados-por-el-sinadef/)) |
| **[PIURA]** | Año 2024 | 106 | Tasa de 5,5 por 100 000, 7.ª del país. En 2019 era 1,1 ([Correo 15/04/2025](https://diariocorreo.pe/edicion/piura/piura-es-la-region-con-mas-tasa-de-homicidios-noticia/)) |

**Sicariato [SULLANA]:** Panamericana cuenta 46 víctimas de sicariato en 2026 hasta el 9 de setiembre, frente a 45 en todo 2025 ([Panamericana](https://panamericana.pe/buenosdiasperu/nacionales/474061-piura-registra-45-victimas-sicariato-2026)). No cita la fuente oficial.

**SIDPOL (denuncias por homicidio) [SULLANA], enero a julio**

Fuente: [ficha provincial del Observatorio Nacional de Seguridad Ciudadana](https://observatorio.regionpiura.gob.pe/documentos/publicaciones/FILE_SST_20250818114235.pdf).

| Año | Denuncias | Tasa por 100 000 |
|---|---|---|
| 2023 | 30 | 8,5 |
| 2024 | 19 | 5,4 |
| 2025 | 20 | 5,6 |

**Conteo municipal [SULLANA]:** el PAPSC 2024–2027, basado en hechos públicos, registra 19 homicidios en 2021, 38 en 2022 y 43 en 2023 (hasta octubre).

### 3.2 Extorsión

| Ámbito | Periodo | Dato | Fuente |
|---|---|---|---|
| **[SULLANA]** | Ene–jul 2023 / 2024 / 2025 | 194 / 445 / **704** denuncias. Tasas de 55 / 126 / **198** por 100 000 | Observatorio Nacional (SIDPOL) |
| **[SULLANA]** | Ene–set 2025 | **256 por 100 000**, la más alta de Piura (Talara 173, Piura 107). En 2019 era 12 | [Infobae 31/10/2025](https://www.infobae.com/peru/2025/10/31/piura-denuncias-por-extorsion-se-multiplicaron-por-nueve-en-los-ultimos-seis-anos/) |
| **[SULLANA]** | 2024 | 237 por 100 000, más del doble del promedio regional (102) | [Infobae 17/05/2025](https://www.infobae.com/peru/2025/05/17/piura-fue-la-tercera-region-con-mas-denuncias-por-extorsion-en-2024/) |
| **[PIURA]** | 2025 | 2 791 denuncias, 3.ª región del país | Correo / Mininter |
| **[PIURA]** | Ene–jul 2026 | 752 denuncias, −58% frente a 2025. Piura y Sullana concentran cerca del 70% | [Correo 08/09/2026](https://diariocorreo.pe/edicion/piura/denuncias-por-extorsion-caen-pero-la-region-aun-concentra-uno-de-los-mayores-registros-del-pais-noticia/) |

> **Advertencia sobre 2026.** La caída de denuncias de extorsión en 2026 coincide con un aumento de los homicidios. Esto suele indicar **subregistro por miedo** y no una mejora real.

### 3.3 Robos y hurtos [SULLANA], enero a julio (SIDPOL)

| Año | Robos | Hurtos | Denuncias totales |
|---|---|---|---|
| 2023 | 808 | 923 | 5 166 |
| 2024 | 909 | 961 | 5 446 |
| 2025 | 483 | 607 | 4 208 |

La caída de 2025 está sesgada. El propio Observatorio advierte que, desde noviembre de 2024, la plataforma de denuncia digital está fuera de línea y esas denuncias no se cuentan.

### 3.4 Trata de personas

- **[PIURA]** 2024: 218 casos fiscales (15,7% del país), **2.ª región después de Lima**, y 255 víctimas (117 en 2023).
  - Entre 2021 y agosto de 2025 hubo solo 14 sentencias.
  - La región tiene 2 fiscales especializados ([Convoca 25/09/2025](https://convoca.pe/investigacion/piura-la-segunda-region-con-mas-casos-de-trata-solo-tiene-dos-fiscales-y-no-cuenta)).
- **[PIURA]** 2025: 237 casos y 237 víctimas (NV, según [Wayka](https://wayka.pe/falta-de-personal-recursos-y-refugio-pone-en-mayor-riesgo-a-victimas-de-trata-en-piura/)).
- **[SULLANA]** No hay cifras provinciales públicas. Hay operativos documentados (ver §4.4).

### 3.5 Armas

- **[PIURA]** Más de 3 500 armas de fuego incautadas en 2025 ([SUCAMEC](https://www.gob.pe/institucion/sucamec/noticias/1381189-piura-sucamec-presenta-mas-de-3-500-armas-de-fuego-incautadas-y-refuerza-acciones-contra-la-ilegalidad-en-la-region)).
- **[PIURA]** Entre mayo de 2025 y marzo de 2026, 2 086 armas: 851 revólveres, 507 pistolas, 491 escopetas y 237 carabinas (exposición de SUCAMEC ante el Congreso, 28/04/2026; NV).
- **[SULLANA]** El 89,6% de los homicidios de 2026 se cometió con arma de fuego. No hay datos de incautaciones desagregados por provincia.

### 3.6 Victimización y percepción

- Nacional urbano, segundo semestre de 2025: 23,9% de la población fue víctima de algún delito (INEI, ENAPRES).
- No hay un desglose oficial reciente para Piura ni para Sullana. **Esto justifica levantar una línea de base propia dentro del proyecto.**

---

## 4. Criminalidad según la prensa: dinámica y actores

### 4.1 Organizaciones criminales identificadas

| Banda | Hechos | Fuente |
|---|---|---|
| Los Payasitos de Nuevo Sullana | Triple crimen de ingenieros y topógrafa (set 2024), por un cupo de S/100 000 | [RPP](https://rpp.pe/peru/piura/piura-detienen-a-presuntos-involucrados-en-asesinato-de-dos-ingenieros-y-una-topografa-noticia-1588622) |
| La Mudanza | Desarticulada en el "Operativo Titánico 2026". Asesinato del exdirigente de construcción civil C. Rodríguez (3 mar 2026) | [Cutivalú](https://www.cutivalu.pe/fecor-piura-desarticula-presunta-banda-criminal-vinculada-al-sicariato-en-sullana/) |
| Los Bolongos | Cobradores de extorsión, AH Jesús María (1 may 2026) | [Correo](https://diariocorreo.pe/edicion/piura/detienen-a-dos-presuntos-integrantes-de-la-banda-los-bolongos-noticia/) |
| Los Gatilleros del Obrero | Captura de "Barbero" con armas y droga (set 2024) | [El Regional](https://elregionalpiura.com.pe/locales/146-sullana/67626-sullana-capturan-a-presunto-integrante-de-la-banda-delincuencial-los-gatilleros-del-obrero) |
| Los Boca Secas de Bellavista / Los Malditos de la Reconstrucción | Antecedentes de 2018. A la segunda la abastecían de armas militares y policías | [RPP](https://rpp.pe/peru/piura/la-policia-desbarato-la-banda-los-boca-secas-de-bellavista-en-un-megaoperativo-en-piura-noticia-1144967), [Correo](https://diariocorreo.pe/edicion/piura/oficiales-del-ep-y-policias-abastecian-de-armas-sicarios-840605/) |
| Los Pulpos (Trujillo) | En junio de 2026 se capturó en Suyo, en la frontera, a un presunto nexo con 4 pistolas, 6 granadas, 1 750 municiones y unos 9 kg de cocaína | [Infobae 10/06/2026](https://www.infobae.com/peru/2026/06/10/capturan-a-presunto-integrante-de-los-pulpos-en-frontera-con-ecuador-transportaba-armas-de-guerra-granadas-y-droga/) |

Sobre las bandas ecuatorianas (Los Lobos, Los Choneros, Los Tiguerones) solo hay menciones genéricas como posibles proveedoras de armas. No hay atribución judicial en Sullana (NV). Tampoco se encontró cobertura sobre presencia del Tren de Aragua en Sullana.

### 4.2 Casos emblemáticos

- **06/09/2024.** Triple asesinato en Samán Chico (Marcavelica), un día después de la visita presidencial. Provocó un paro ciudadano que bloqueó la Panamericana ([La República](https://larepublica.pe/sociedad/2024/09/06/triple-asesinato-en-piura-matan-a-dos-ingenieros-y-a-una-topografa-por-presunto-cobro-de-cupos-en-sullana-dina-boluarte-pnp-500838)).
- **21/12/2025.** Sicariato de un obrero en Bellavista. A los implicados se les incautó dinamita ([Poder Judicial](https://www.pj.gob.pe/wps/wcm/connect/cortesuperiorsullanapj/s_csj_sullana_nuevo/as_inicio/as_imagen_prensa/as_noticias/csjsull_n_juez_ordena_prision_preventiva_tres_sujetos_presunto_sicariato_tenencia_explosivo_30122025)).
- **05/06/2026.** Masacre de 4 miembros de una familia, entre ellos un menor, con más de 50 disparos en Santa Teresita ([El Comercio](https://elcomercio.pe/peru/piura/piura-sicarios-asesinan-a-cuatro-miembros-de-una-familia-entre-ellos-un-menor-en-sullana-ultimas-noticia/)).
- **02/08/2026.** Explosivo en la vivienda de la cantante Thamara Gómez, con exigencia de S/50 000 ([Infobae](https://www.infobae.com/peru/2026/08/02/thamara-gomez-denuncia-extorsion-detonan-un-explosivo-en-su-vivienda-en-sullana-y-le-exigen-pago-de-50-mil-soles/)).
- **09/08/2026.** Secuestro y ejecución de un comerciante. Se reforzó la vigilancia en Lancones y Suyo ([El Tiempo](https://eltiempo.pe/local/sullana-refuerzan-vigilancia-en-la-frontera-tras-crimen-de-comerciante/)).
- **Setiembre de 2026.** Ataque armado en el AH Manuel Seoane, con 2 muertos y 2 heridos, en plena vigencia del estado de emergencia. La Defensoría pidió reforzar la inteligencia policial ([NP 525/2026](https://www.defensoria.gob.pe/wp-content/uploads/2026/09/NP-525-2026.pdf)).

### 4.3 Extorsión: modalidades

- **Explosivos contra viviendas y comercios**, con exigencias de entre S/20 000 y S/50 000.
- **Cupos en obras de construcción civil.**
- **Amenazas a colegios.** El Colegio Villarreal pasó a clases virtuales en julio de 2025.
- **Ataques a mototaxistas y transportistas.**

### 4.4 Trata y explotación sexual

- **Rescate de 3 adolescentes** de 13, 15 y 17 años en el bar "La Teresita", en El Monterón (Marcavelica) ([RPP](https://rpp.pe/peru/piura/sullana-pnp-rescata-a-tres-adolescentes-victimas-de-trata-y-detiene-a-dos-mujeres-noticia-1689430)).
- **Operativo en night clubs** (24/03/2026). Se intervino el local Teymar, en la vía Sullana–Tambogrande, y el Club Cavally. Se halló a mujeres venezolanas, colombianas y ecuatorianas en situación irregular ([El Regional](https://elregionalpiura.com.pe/locales/146-sullana/72864-operativo-en-prostibulos-de-sullana-deja-local-clausurado-y-extranjeras-intervenidas)).

### 4.5 Droga y frontera

- **07/12/2025.** Incautación de 3 407 kg de cocaína en banano orgánico, en la vía Sullana–La Tina (El Cucho), con destino a Paita ([Infobae](https://www.infobae.com/peru/2025/12/07/incautan-en-piura-cargamento-narco-de-mas-de-3-toneladas-de-cocaina-camuflada-listo-para-salir-del-pais/)).
- Hay **más de 40 pasos ilegales** en la frontera de Piura con Ecuador ([Canal N](https://canaln.pe/peru/ecuador-cerro-sus-fronteras-peru-salvo-punto-tumbes-n489252), NV fecha).

### 4.6 Corrupción policial

- **15/11/2025.** Prisión preventiva para el mayor PNP comisario de El Obrero y dos suboficiales, por exigir S/5 000 ([La República](https://larepublica.pe/sociedad/2025/11/15/dictan-prision-preventiva-a-mayor-y-suboficiales-pnp-por-pedir-s5000-para-devolver-vehiculo-en-sullana-1310265)).
- **02/11/2025.** El alcalde pide el estado de emergencia y la rotación total del personal policial ([Infobae](https://www.infobae.com/peru/2025/11/02/alcalde-de-sullana-pide-al-gobierno-declarar-estado-de-emergencia-por-ola-de-sicariato-y-corrupcion-policial/)).
- **Informe Defensorial n.° 266 (2026).** Encontró deficiencias logísticas y operativas graves en comisarías de Piura y Sullana ([Defensoría](https://www.defensoria.gob.pe/wp-content/uploads/2026/02/Informe-Defensorial-n.%C2%B0-266_Situaci%C3%B3n-de-las-unidades-a-cargo-de-la-prevenci%C3%B3n-del-delito-Supervisi%C3%B3n-Nacional-a-Comisar%C3%ADas-B%C3%A1sicas-de-la-Polic%C3%ADa-Nacional-del-Per%C3%BA.pdf)).

> **Implicancia de diseño.** Dada la corrupción documentada, el sistema debe tener **trazabilidad y auditoría de accesos**. Cada consulta, exportación de video o búsqueda de placa debe quedar registrada.

---

## 5. Respuesta estatal y capacidades existentes

### 5.1 Estados de emergencia

| Decreto supremo | Fecha | Ámbito |
|---|---|---|
| 105-2023-PCM | Set 2023, 60 días | 7 distritos de Sullana. Lancones ya estaba en emergencia por otra norma |
| 030-2026-PCM | 07/03/2026 | Sullana, Bellavista y otros distritos de Piura, Paita y Talara |
| 064-2026-PCM | 06/05/2026 | Prórroga |
| 101-2026-PCM | Desde 06/07/2026 | Prórroga |
| **126-2026-PCM** | 05/09/2026 | Nueva declaratoria, **vigente**. Vencería hacia el 04/11/2026 (cálculo propio, NV) |

Fuentes: [El Peruano 064](https://busquedas.elperuano.pe/dispositivo/NL/2512962-2), [El Peruano 101](https://busquedas.elperuano.pe/dispositivo/NL/2531903-1), [126](https://actualidadcivil.pe/normas-legales/decreto-supremo-126-2026-PCM/9e25dcc8-3b19-444c-8232-4359a792bb28).

### 5.2 Policía y serenazgo

- Las comisarías dependen de la **Divopus Sullana**, dentro de la Región Policial Piura.
  - En el distrito de Sullana: Sullana, Nueva Sullana, San Jacinto, Los Encuentros y El Obrero.
  - En el resto de la provincia: Bellavista, Marcavelica, Querecotillo, Salitral, Miguel Checa y Lancones.
- En 2023 Sullana tenía **6 patrulleros para unos 300 000 habitantes** ([La República](https://larepublica.pe/sociedad/2023/09/19/sullana-en-emergencia-tiene-solo-6-patrulleros-para-300000-habitantes-estado-de-emergencia-en-piura-pnp-lrnd-278863)).
- En setiembre de 2024 el Mininter anunció el despliegue de más de 1 000 policías y 50 agentes del GRECCO.
- **Serenazgo:**
  - La municipalidad gasta unos S/12 millones al año de recursos propios.
  - El MEF transfiere unos S/2,2 millones al año.
  - En 2022 había 159 serenos (NV).

### 5.3 Videovigilancia municipal: historial

| Fecha | Hecho | Fuente |
|---|---|---|
| 2019 | Proyecto CUI 2611522 (NV): 54 cámaras, 5 camionetas y 5 motos, por unos S/9 millones | [La República](https://larepublica.pe/sociedad/2019/10/01/con-54-camaras-vigilaran-calles-y-avenidas-en-sullana) |
| Nov 2021 | Contraloría: 12 de 54 cámaras de Sullana con fallas. En Bellavista, 7 de 30 operativas | [Cutivalú](https://www.cutivalu.pe/contraloria-124-camaras-de-videovigilancia-de-piura-sullana-bellavista-talara-paita-y-sechura-estan-inoperativas/) |
| Dic 2022 | 15 cámaras inoperativas. Base Orión de serenazgo con el monitor apagado | [La Hora](https://lahora.pe/local/sullana-quince-camaras-de-vigilancia-se-encuentran-inoperativas/) |
| 2023 | Mantenimiento. Se presentó a la presidencia un proyecto de unos S/16 millones con 100 cámaras, 16 de reconocimiento facial y 14 lectoras de placas | [gob.pe](https://www.gob.pe/institucion/munisullana/noticias/750489-municipalidad-de-sullana-inicia-mantenimiento-de-camaras-de-video-vigilancia-para-ayudar-en-la-lucha-contra-la-inseguridad-ciudadana), [Correo](https://diariocorreo.pe/edicion/piura/estado-de-emergencia-en-sullana-presentan-proyecto-de-videovigilancia-a-presidenta-dina-boluarte-noticia/) |
| Jun 2025 | Bellavista: 28 de 35 cámaras inoperativas, solo 25 días de grabación, sin interconexión | [El Regional](https://elregionalpiura.com.pe/index.php/locales/147-bellavista/70114-sullana-el-80-de-camaras-de-videovigilancia-no-funcionan-en-bellavista) |
| 2025 (NV) | Vigilancia con drones en alianza con la 1.ª Brigada de Caballería del Ejército | [Correo](https://diariocorreo.pe/edicion/piura/implementan-sistema-de-vigilancia-con-drones-en-sullana-noticia/) |
| 06/08/2026 | Convenio con el "Consorcio de Sullana" para 194 cámaras, 5 camionetas y motos | [Producciones LVR](https://www.produccioneslvr.com/2026/08/firman-convenio-para-la-ampliacion-y.html) |
| 22/09/2026 | Anuncio de un proyecto de **S/25 millones por Obras por Impuestos** (OxI), con reconocimiento facial y de placas | [Cutivalú](https://www.cutivalu.pe/sullana-anuncia-proyecto-de-seguridad-por-25-millones-de-soles/) |

> **Hallazgo clave.** Ya existe un proyecto municipal de S/25 millones por OxI en curso o en preparación, además del convenio por 194 cámaras. **Nuestra propuesta debe posicionarse frente a ese proyecto**: complementarlo con drones, analítica, integración y operación, o competir como empresa ejecutora u operadora. Hay que verificar el CUI, el estado en Invierte.pe y la empresa financista en ProInversión.

### 5.4 Contexto nacional

- **Plataforma Mininter con IA (Amper, julio de 2025, S/37 millones).** Integrará unas 3 000 cámaras de 70 municipios con el **C4 de la PNP** ([Amper](https://www.grupoamper.com/sala-de-prensa/el-ministerio-del-interior-de-peru-adjudica-a-amper-el-contrato-para-su-sistema-de-videovigilancia-inteligente/)). No se sabe si Sullana está incluida (NV). Cualquier propuesta debe ser **compatible e interoperable** con esta plataforma.
- **Contraloría a nivel nacional.** 1 553 de 6 144 cámaras inoperativas (20%) en 248 municipios.
- **Referentes:**
  - **Positivos:**
    - Miraflores: 1 399 cámaras con analítica de rostros, placas y armas.
    - San Isidro: 664 cámaras.
    - San Juan de Lurigancho: 610 cámaras y botones de pánico, además de drones térmicos del Ejército.
    - Trujillo: más de 1 000 cámaras.
  - **Negativos:**
    - Piura ciudad: solo 1 de 45 cámaras operativas en la base Paraíso, y 83 cámaras sin conectar ([Defensoría 25/05/2026](https://www.defensoria.gob.pe/nota_de_prensa/nota-de-prensa-n-254-ogco-dp-2026/)).
    - Callao: 284 cámaras inoperativas.

### 5.5 Autoridades y calendario político

- **Alcalde provincial 2023–2026:** Marlem Mogollón Meca. Ha pedido públicamente el estado de emergencia y denunciado corrupción policial.
- **Elecciones regionales y municipales: 4 de octubre de 2026.** Las nuevas autoridades asumen el **1 de enero de 2027**.
  - **Implicancia:** la propuesta debe presentarse tanto a la gestión saliente, por la continuidad de la OxI, como a las autoridades electas.
  - Los compromisos de inversión se decidirán en el periodo 2027–2030.

---

## 6. Marco normativo aplicable

| Norma | Relevancia |
|---|---|
| Ley 27933 (SINASEC), modificada por DL 1454 y Ley 32378 (2025) | Comités provincial y distritales (COPROSEC / CODISEC). El proyecto debe alinearse con el PAPSC |
| DL 1218 y Ley 30120; reglamento DS 007-2020-IN; DS 005-2026-IN | Uso de cámaras de videovigilancia, Plan de Adecuación e interconexión con la PNP |
| Ley 29733 y nuevo reglamento DS 016-2024-JUS (vigente desde marzo de 2025) | **La biometría es dato sensible.** El reconocimiento facial exige evaluación de impacto, base legal, medidas de seguridad y notificación de brechas en 48 horas |
| Ley 30740 y reglamento DS 012-2026-MTC; NTC 001-2015 de la DGAC (vigente en la transición) | Drones: registro, seguro, categorías (Abierta / Específica / Certificada), límites de altura. Las aeronaves municipales **no** están exceptuadas |
| Ley 31297 (Serenazgo) y DS 009-2022-IN | Funciones y límites del serenazgo en la respuesta |
| Plan de Acción Provincial de Seguridad Ciudadana (PAPSC) Sullana 2024–2027 ([gob.pe](https://www.gob.pe/institucion/munisullana/informes-publicaciones/4954317-plan-de-accion-provincial-de-seguridad-ciudadana-sullana-2024-2027)) | Delitos priorizados: **homicidios, extorsión, violencia física y microcomercialización de drogas** |

---

## 7. Vacíos de información

1. Tasa oficial de homicidios por provincia (SINADEF / INEI) y datos del Observatorio de Criminalidad del Ministerio Público.
2. Victimización y percepción (ENAPRES) para Piura o Sullana.
3. Datos de trata del sistema RETA o de la Fiscalía para la provincia.
4. CUI, estado y empresa del proyecto OxI de S/25 millones y del convenio de 194 cámaras (Invierte.pe, ProInversión).
5. Inventario real y actual de cámaras operativas en Sullana y en los demás distritos.
6. Si Sullana está incluida en la plataforma Mininter–Amper / C4.
7. Georreferenciación de los delitos para el mapa de calor. Se puede pedir a la Divopus Sullana o al Observatorio Regional (REDES).
8. Candidatos y resultados de las elecciones del 4 de octubre de 2026 en Sullana.
