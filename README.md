# Jalisco: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Jalisco, Mexico, which global-law reads at `mexico/jalisco/acts/`.

The law of the State of Jalisco (Estado Libre y Soberano de Jalisco, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-jal/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

87 ordenamientos with 1598 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE JALISCO | 130 | as first published, then each reform: 22 July 1917 to 20 September 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE JALISCO | 124 | as first published, then each reform: 7 March 1995 to 21 June 2026 |
| `codigo-de-asistencia-social/` | CODIGO DE ASISTENCIA SOCIAL DEL ESTADO DE JALISCO | 7 | as first published, then each reform: 1 February 2019 to 26 November 2025 |
| `codigo-de-gobierno-municipal-de-guadalajara-jalisco/` | CODIGO DE GOBIERNO MUNICIPAL DE GUADALAJARA, JALISCO | 41 | as first published, then each reform: 1 June 2020 to 26 October 2023 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE JALISCO | 81 | as first published, then each reform: 1 January 1939 to 7 July 2021 |
| `codigo-electoral/` | CODIGO ELECTORAL DEL ESTADO DE JALISCO -- ANTES CODIGO ELECTORAL Y DE PARTICIPACION SOCIAL DEL ESTADO DE JALISCO -- ANTES CODIGO ELECTORAL Y DE PARTICIPACION CIUDADANA DEL ESTADO DE JALISCO -- | 18 | as first published, then each reform: 6 August 2008 to 25 July 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE JALISCO | 24 | as first published, then each reform: 17 December 1997 to 17 May 2026 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE JALISCO | 181 | as first published, then each reform: 1 November 1982 to 9 September 2026 |
| `codigo-urbano/` | CODIGO URBANO PARA EL ESTADO DE JALISCO | 40 | as first published, then each reform: 1 January 2009 to 28 June 2026 |
| `ley-agroalimentaria/` | LEY AGROALIMENTARIA DEL ESTADO DE JALISCO | 4 | as first published, then each reform: 1 January 2020 to 9 November 2022 |
| `ley-constitutiva-del-a-comision-de-planeacion-de-la-costa-de/` | LEY CONSTITUTIVA DEL A COMISION DE PLANEACION DE LA COSTA DE JALISCO | 1 | as first published: 20 October 1956 |
| `ley-contra-la-delincuencia-organizada/` | LEY CONTRA LA DELINCUENCIA ORGANIZADA DEL ESTADO DE JALISCO | 5 | as first published, then each reform: 11 March 2004 to 30 August 2019 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO DE JALISCO | 34 | as first published, then each reform: 26 June 2008 to 26 May 2026 |
| `ley-de-acuacultura-y-pesca/` | LEY DE ACUACULTURA Y PESCA PARA EL ESTADO DE JALISCO | 1 | as first published: 27 June 2021 |
| `ley-de-amnistia-para-las-mujeres-victimas-de-violencia-de-ge/` | LEY DE AMNISTIA PARA LAS MUJERES VICTIMAS DE VIOLENCIA DE GENERO DEL ESTADO DE JALISCO | 1 | as first published: 27 November 2019 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 4 | as first published, then each reform: 20 November 2019 to 19 June 2026 |
| `ley-de-asociaciones-intermunicipales/` | LEY DE ASOCIACIONES INTERMUNICIPALES DEL ESTADO DE JALISCO | 1 | as first published: 31 October 2021 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS DEL ESTADO DE JALISCO | 12 | as first published, then each reform: 29 March 2014 to 26 November 2025 |
| `ley-de-austeridad-y-ahorro/` | LEY DE AUSTERIDAD Y AHORRO DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 8 | as first published, then each reform: 1 January 2015 to 5 October 2021 |
| `ley-de-benemeritos/` | LEY DE BENEMERITOS DEL ESTADO DE JALISCO -- ANTES LEY PARA DECLARAR Y HONRAR LA MEMORIA DE LOS BENEMERITOS DEL ESTADO DE JALISCO -- | 7 | as first published, then each reform: 14 March 2001 to 15 January 2023 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO DE JALISCO | 5 | as first published, then each reform: 24 August 2012 to 28 July 2019 |
| `ley-de-catastro-municipal/` | LEY DE CATASTRO MUNICIPAL DEL ESTADO DE JALISCO | 18 | as first published, then each reform: 18 December 1997 to 10 March 2024 |
| `ley-de-ciencia-desarrollo-tecnologico-e-innovacion/` | LEY DE CIENCIA, DESARROLLO TECNOLOGICO E INNOVACION DEL ESTADO DE JALISCO | 13 | as first published, then each reform: 10 October 2014 to 8 October 2023 |
| `ley-de-compras-gubernamentales-enajenaciones-y-contratacion/` | LEY DE COMPRAS GUBERNAMENTALES, ENAJENACIONES Y CONTRATACION DE SERVICIOS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 15 | as first published, then each reform: 25 January 2017 to 28 August 2026 |
| `ley-de-control-de-confianza/` | LEY DE CONTROL DE CONFIANZA DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 20 August 2012 to 18 November 2018 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE JALISCO CON SUS MUNICIPIOS | 26 | as first published, then each reform: 31 December 1996 to 1 January 2024 |
| `ley-de-coordinacion-metropolitana/` | LEY DE COORDINACION METROPOLITANA DEL ESTADO DE JALISCO | 19 | as first published, then each reform: 4 February 2011 to 22 April 2022 |
| `ley-de-cultura-de-paz/` | LEY DE CULTURA DE PAZ DEL ESTADO DE JALISCO | 2 | as first published, then each reform: 12 May 2021 to 4 August 2023 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE JALISCO | 19 | as first published, then each reform: 20 April 2012 to 28 August 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE JALISCO | 16 | as first published, then each reform: 23 July 2004 to 5 July 2026 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE JALISCO | 25 | as first published, then each reform: 20 January 2007 to 5 July 2026 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE JALISCO | 20 | as first published, then each reform: 28 December 2004 to 18 March 2027 |
| `ley-de-deuda-publica-y-disciplina-financiera/` | LEY DE DEUDA PUBLICA Y DISCIPLINA FINANCIERA DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 27 November 2016 to 7 July 2021 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO LIBRE Y SOBERANO DE JALISCO | 30 | as first published, then each reform: 16 May 2020 to 20 September 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE JALISCO | 4 | as first published, then each reform: 26 December 2021 to 4 July 2025 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE JALISCO | 5 | as first published, then each reform: 24 February 2023 to 17 July 2026 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA-RECEPCION DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 16 October 2012 to 22 April 2020 |
| `ley-de-evaluacion-y-supervision-de-medidas-cautelares-y-susp/` | LEY DE EVALUACION Y SUPERVISION DE MEDIDAS CAUTELARES Y SUSPENSION CONDICIONAL DEL PROCESO DEL ESTADO DE JALISCO | 3 | as first published, then each reform: 26 March 2019 to 7 August 2020 |
| `ley-de-expropiacion-de-bienes-muebles-e-inmuebles-de-propied/` | LEY DE EXPROPIACION DE BIENES MUEBLES E INMUEBLES DE PROPIEDAD PRIVADA | 9 | as first published, then each reform: 19 May 1923 to 31 July 2026 |
| `ley-de-filmaciones/` | LEY DE FILMACIONES DEL ESTADO DE JALISCO | 3 | as first published, then each reform: 5 March 2021 to 25 February 2024 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 3 | as first published, then each reform: 27 December 2013 to 7 July 2021 |
| `ley-de-fiscalizacion-superior-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 7 | as first published, then each reform: 1 January 2018 to 22 September 2026 |
| `ley-de-fomento-a-la-cultura/` | LEY DE FOMENTO A LA CULTURA DEL ESTADO DE JALISCO | 20 | as first published, then each reform: 22 December 2000 to 18 April 2021 |
| `ley-de-fomento-al-emprendimiento/` | LEY DE FOMENTO AL EMPRENDIMIENTO DEL ESTADO DE JALISCO | 2 | as first published, then each reform: 3 October 2021 to 15 January 2023 |
| `ley-de-fomento-apicola-y-proteccion-de-agentes-polinizadores/` | LEY DE FOMENTO APICOLA Y PROTECCION DE AGENTES POLINIZADORES DE JALISCO | 6 | as first published, then each reform: 21 October 2015 to 27 November 2019 |
| `ley-de-fomento-y-desarrollo-pecuario/` | LEY DE FOMENTO Y DESARROLLO PECUARIO DEL ESTADO DE JALISCO | 21 | as first published, then each reform: 25 June 2003 to 21 June 2026 |
| `ley-de-gestion-integral-de-los-residuos/` | LEY DE GESTION INTEGRAL DE LOS RESIDUOS DEL ESTADO DE JALISCO | 8 | as first published, then each reform: 25 May 2007 to 28 April 2019 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE JALISCO | 24 | as first published, then each reform: 24 September 2000 to 25 February 2024 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE JALISCO | 86 | as first published, then each reform: 6 April 1984 to 17 October 2025 |
| `ley-de-incompatibilidades-para-los-servidores-publicos-regla/` | LEY DE INCOMPATIBILIDADES PARA LOS SERVIDORES PUBLICOS REGLAMENTARIA DEL ARTICULO 112 DE LA CONSTITUCION POLITICA DEL ESTADO DE JALISCO -- ANTES LEY REGLAMENTARIA DEL ART. 62, ANTES DEL ART. 61-- DE LA CONSTICUCION POLITICA DEL ESTADO DE JALISCO | 10 | as first published, then each reform: 6 January 1980 to 11 August 2019 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE JALISCO PARA EL EJERCICIO FISCAL 2026 | 3 | as first published, then each reform: 1 January 2026 to 9 September 2026 |
| `ley-de-ingresos-del-municipio-de-zapopan-jalisco-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE ZAPOPAN, JALISCO, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 28 December 2025 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE JALISCO | 21 | as first published, then each reform: 18 April 2000 to 23 August 2026 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE JALISCO | 20 | as first published, then each reform: 2 February 2007 to 23 July 2023 |
| `ley-de-la-comision-estatal-de-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS DEL ESTADO DE JALISCO | 20 | as first published, then each reform: 19 February 1998 to 10 March 2024 |
| `ley-de-limites-territoriales-de-los-municipios/` | LEY DE LIMITES TERRITORIALES DE LOS MUNICIPIOS DEL ESTADO DE JALISCO | 2 | as first published, then each reform: 29 December 2019 to 25 April 2020 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE JALISCO | 2 | as first published, then each reform: 15 October 2024 to 18 March 2027 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes-en-el-esta/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES EN EL ESTADO DE JALISCO | 31 | as first published, then each reform: 1 January 2016 to 29 July 2026 |
| `ley-de-los-simbolos-oficiales/` | LEY DE LOS SIMBOLOS OFICIALES DEL ESTADO DE JALISCO | 7 | as first published, then each reform: 8 August 2010 to 28 February 2020 |
| `ley-de-mecenazgo-cultural/` | LEY DE MECENAZGO CULTURAL DEL ESTADO DE JALISCO | 4 | as first published, then each reform: 15 June 2014 to 12 February 2020 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 21 July 2019 to 30 July 2021 |
| `ley-de-movilidad-seguridad-vial-y-transporte/` | LEY DE MOVILIDAD, SEGURIDAD VIAL Y TRANSPORTE DEL ESTADO DE JALISCO | 7 | as first published, then each reform: 20 October 2022 to 16 August 2026 |
| `ley-de-nutricion-adecuada-y-estilos-de-vida-saludables/` | LEY DE NUTRICION ADECUADA Y ESTILOS DE VIDA SALUDABLES DEL ESTADO DE JALISCO | 1 | as first published: 10 March 2024 |
| `ley-de-obra-publica/` | LEY DE OBRA PUBLICA PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 9 | as first published, then each reform: 2 February 2018 to 3 June 2026 |
| `ley-de-patrimonio-cultural/` | LEY DE PATRIMONIO CULTURAL DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 7 | as first published, then each reform: 27 August 2014 to 7 July 2023 |
| `ley-de-personas-desaparecidas/` | LEY DE PERSONAS DESAPARECIDAS DEL ESTADO DE JALISCO | 3 | as first published, then each reform: 6 March 2021 to 7 September 2025 |
| `ley-de-planeacion-participativa/` | LEY DE PLANEACION PARTICIPATIVA PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 3 | as first published, then each reform: 21 December 2018 to 15 May 2026 |
| `ley-de-prevencion-social-de-la-violencia-y-la-delincuencia/` | LEY DE PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE JALISCO | 1 | as first published: 30 August 2015 |
| `ley-de-promocion-y-desarrollo-artesanal/` | LEY DE PROMOCION Y DESARROLLO ARTESANAL DEL ESTADO DE JALISCO | 7 | as first published, then each reform: 18 December 2015 to 22 November 2020 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE JALISCO | 29 | as first published, then each reform: 11 July 1993 to 16 August 2026 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-de-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DE TABACO PARA EL ESTADO DE JALISCO | 2 | as first published, then each reform: 18 December 2020 to 17 July 2022 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 4 | as first published, then each reform: 26 July 2017 to 16 May 2021 |
| `ley-de-proteccion-y-atencion-de-los-migrantes-en-el-estado-d/` | LEY DE PROTECCION Y ATENCION DE LOS MIGRANTES EN EL ESTADO DE JALISCO | 7 | as first published, then each reform: 18 November 2016 to 16 August 2026 |
| `ley-de-proteccion-y-cuidado-de-los-animales/` | LEY DE PROTECCION Y CUIDADO DE LOS ANIMALES DEL ESTADO DE JALISCO | 12 | as first published, then each reform: 30 November 2012 to 9 July 2021 |
| `ley-de-proteccion-conservacion-y-fomento-de-arbolado-y-areas/` | LEY DE PROTECCION, CONSERVACION Y FOMENTO DE ARBOLADO Y AREAS VERDES URBANAS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 4 | as first published, then each reform: 9 June 2017 to 3 June 2026 |
| `ley-de-proyectos-de-inversion-y-de-prestacion-de-servicios/` | LEY DE PROYECTOS DE INVERSION Y DE PRESTACION DE SERVICIOS DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 10 | as first published, then each reform: 10 May 2008 to 14 May 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 8 | as first published, then each reform: 1 January 2004 to 8 November 2020 |
| `ley-de-responsabilidades-politicas-y-administrativas/` | LEY DE RESPONSABILIDADES POLITICAS Y ADMINISTRATIVAS DEL ESTADO DE JALISCO | 13 | as first published, then each reform: 27 September 2017 to 15 March 2023 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE JALISCO | 37 | as first published, then each reform: 6 December 2018 to 21 August 2026 |
| `ley-de-salud-mental-y-adicciones/` | LEY DE SALUD MENTAL Y ADICCIONES DEL ESTADO DE JALISCO | 2 | as first published, then each reform: 14 July 2024 to 8 March 2026 |
| `ley-de-sujetos-protegidos/` | LEY DE SUJETOS PROTEGIDOS PARA EL ESTADO DE JALISCO | 6 | as first published, then each reform: 30 September 2014 to 30 August 2019 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE JALISCO Y SUS MUNICIPIOS | 25 | as first published, then each reform: 9 August 2013 to 4 August 2023 |
| `ley-de-turismo/` | LEY DE TURISMO PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 4 | as first published, then each reform: 6 June 2018 to 16 November 2022 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE JALISCO | 7 | as first published, then each reform: 10 May 2014 to 17 May 2026 |
| `ley-del-agua/` | LEY DEL AGUA PARA EL ESTADO DE JALISCO Y SUS MUNICIPIOS | 22 | as first published, then each reform: 25 February 2007 to 21 June 2026 |
| `ley-del-centro-de-atencion-para-las-victimas-del-delito/` | LEY DEL CENTRO DE ATENCION PARA LAS VICTIMAS DEL DELITO | 7 | as first published, then each reform: 8 March 1998 to 4 October 2020 |
| `ley-del-gobierno-y-la-administracion-publica-municipal/` | LEY DEL GOBIERNO Y LA ADMINISTRACION PUBLICA MUNICIPAL DEL ESTADO DE JALISCO | 90 | as first published, then each reform: 22 May 2001 to 8 March 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
