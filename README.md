# Basque Country: law history in git

The law of the autonomous community of Basque Country (Comunidad Autónoma del País Vasco, Spain) as a git history: one file per article, one commit per norm that changed it, dated the day the change took effect, with the amending norm as the commit's author. `git blame` names the norm behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `es-pv/`. Spain's national law is in [lexifina/spain-law](https://github.com/lexifina/spain-law).

The text is in Spanish, exactly as the BOE's consolidated text prints it. Texts in co-official languages are not included.

Basado en datos de la Agencia Estatal Boletín Oficial del Estado (<https://www.boe.es>). Every text here is a consolidated text for information only (texto consolidado de carácter meramente informativo), not an official publication.

## What this repository holds

200 norms with 561 versions so far: the Estatuto de Autonomía first, then the laws, decree-laws and legislative decrees in force that the BOE consolidates, oldest first, added in parts of about 50. 26 of them are repealed norms the BOE consolidates: their whole history is kept, and their last commit removes the text on the day the repeal took effect, credited to the repealing norm. Regulations are not included (the BOE consolidates no autonomic decrees or orders).

| Folder | Norm | Versions | History | BOE last updated |
| --- | --- | ---: | --- | --- |
| `estatuto-de-autonomia/` | Ley Orgánica 3/1979, de 18 de diciembre, de Estatuto de Autonomía para el País Vasco. | 1 | as first published: 11 January 1980 | 2026-07-24 |
| `ley-1981-002/` | Ley 2/1981, de 12 de febrero, sobre reconocimiento de los derechos de inviolabilidad e inmunidad de los miembros del Parlamento Vasco. | 3 | as first published, then each change: 10 April 1981 to 19 November 1981 | 2025-12-19 |
| `ley-1981-003/` | Ley 3/1981, de 12 de febrero, sobre Centros de Contratación de Cargas en Transporte Terrestre de Mercancías. | 6 | as first published, then each change: 10 April 1981 to 14 June 1991 | 2025-12-19 |
| `ley-1981-004/` | Ley 4/1981, de 18 de marzo, sobre Designación de Senadores representantes de Euskadi. | 4 | as first published, then each change: 12 May 1981 to 3 April 1986 | 2025-12-19 |
| `ley-1981-007/` | Ley 7/1981, de 30 de junio, sobre Ley de Gobierno. | 7 | as first published, then each change: 27 July 1981 to 27 December 2022 | 2025-12-19 |
| `ley-1982-005/` | Ley 5/1982, de 20 de mayo, de creación del Ente Público Radio Televisión Vasca. | 6 | as first published, then each change: 3 June 1982 to 23 January 2008 | 2025-12-19 |
| `ley-1982-007/` | Ley 7/1982, de 30 de junio, de Salud Escolar. | 1 | as first published: 2 September 1982 | 2025-12-19 |
| `ley-1982-009/` | Ley 9/1982, de 24 de noviembre, por la que se crea el Ente Vasco de la Energía. | 2 | as first published, then each change: 16 December 1982 to 3 April 1998 | 2025-12-19 |
| `ley-1982-010/` | Ley 10/1982, de 24 de noviembre, básica de normalización del uso del Euskera. | 3 | as first published, then each change: 17 December 1982 to 16 July 2022 | 2026-07-14 |
| `ley-1983-027/` | Ley 27/1983, de 25 de noviembre, de Relaciones entre las Instituciones Comunes de la Comunidad Autónoma y los Órganos Forales de sus Territorios Históricos. | 7 | as first published, then each change: 10 December 1983 to 10 April 2022 | 2025-12-19 |
| `ley-1983-029/` | Ley 29/1983, de 25 de noviembre, de creación del Instituto de Alfabetización y Reeuskaldunización de Adultos y de Regulación de los Euskaltegis. | 1 | as first published: 13 December 1983 | 2025-12-19 |
| `ley-1984-002/` | Ley 2/1984, de 30 de octubre, de Reversión de Bienes y Derechos Incautados. | 1 | oldest version available: 3 December 1984 | 2025-12-16 |
| `ley-1985-003/` | Ley 3/1985, de 27 de febrero, por la que se crea y regula la Institución del "Ararteko". | 1 | as first published: 22 April 1985 | 2025-12-19 |
| `ley-1985-009/` | Ley 9/1985, de 4 de diciembre, por la que se regula el Consejo Asesor de R.T.V.E. en el País Vasco o R.T.V.E.-ren Euskadiko Aholku-Batzordea. | 1 | as first published: 27 January 1986 | 2025-12-19 |
| `ley-1986-004/` | Ley 4/1986, de 23 de abril, de Estadística de la Comunidad Autónoma de Euskadi. | 7 | as first published, then each change: 19 June 1986 to 24 November 2023 | 2025-12-19 |
| `ley-1986-006/` | Ley 6/1986, de 27 de mayo, del Consejo de la Juventud de Euskadi-Euskadiko Gazteriaren Kontseilua. | 1 | as first published: 11 June 1986 | 2025-12-19 |
| `ley-1987-001/` | Ley 1/1987, de 27 de marzo, de Elecciones para las Juntas Generales de los Territorios Históricos de Araba, Bizkaia y Gipuzkoa. | 3 | as first published, then each change: 10 April 1987 to 5 May 2026 | 2026-06-01 |
| `ley-1987-008/` | Ley 8/1987, de 20 de noviembre, sobre creación de los Jurados Territoriales de Expropiación Forzosa. | 1 | as first published: 10 December 1987 | 2025-12-19 |
| `ley-1988-001/` | Ley 1/1988, de 5 de febrero, del "Tribunal Vasco de Cuentas Públicas" / "Herri-Kontuen Euskal Epaitegia". | 8 | as first published, then each change: 23 March 1988 to 1 January 2023 | 2025-12-19 |
| `ley-1988-002/` | Ley 2/1988, de 5 de febrero, sobre creación del "Instituto Vasco de la Mujer/Emakumearen Euskal Erakundea". | 4 | as first published, then each change: 24 March 1988 to 18 March 2022 | 2025-12-19 |
| `ley-1988-010/` | Ley 10/1988, de 29 de junio, para la Confluencia de las Ikastolas y la Escuela Pública. | 3 | as first published, then each change: 7 August 1988 to 14 October 2023 | 2025-12-19 |
| `ley-1988-011/` | Ley 11/1988, de 29 de junio, de creación del Instituto Vasco de Educación Física. | 1 | as first published: 7 August 1988 | 2025-12-19 |
| `ley-1988-013/` | Ley 13/1988, de 28 de octubre, de Consejos Escolares de Euskadi. | 5 | as first published, then each change: 13 December 1988 to 14 October 2023 | 2025-12-19 |
| `ley-1988-014/` | Ley 14/1988, de 28 de octubre, de Retribuciones de Altos Cargos. | 4 | as first published, then each change: 24 November 1988 to 1 January 2023 | 2025-12-19 |
| `ley-1989-001/` | Ley 1/1989, de 13 de abril, por la que se modifica la calificación de determinadas infracciones administrativas en materia de caza y pesca fluvial y se elevan las cuantías de las sanciones. | 6 | as first published, then each change: 1 June 1989 to 30 March 2011 | 2025-12-19 |
| `ley-1989-002/` | Ley 2/1989, de 30 de mayo, reguladora del Plan General de Carreteras del País Vasco. | 8 | oldest version available, then each change: 9 June 1989 to 12 December 2018 | 2025-12-19 |
| `ley-1989-003/` | Ley 3/1989, de 30 de mayo, de Armonización, Coordinación y Colaboración Fiscal. | 4 | as first published, then each change: 10 June 1989 to 15 April 2016 | 2025-12-19 |
| `ley-1989-005/` | Ley 5/1989, de 6 de julio, de Protección y Ordenación de la Reserva de la Biosfera de Urdaibai. | 2 | as first published, then each change: 30 July 1989 to 18 November 1997 | 2025-12-19 |
| `ley-1990-001/` | Ley 1/1990, de 6 de abril, por la que se determina la Capitalidad de los Partidos Judiciales de la Comunidad Autónoma del País Vasco. | 2 | as first published, then each change: 15 May 1990 to 3 November 1992 | 2025-12-19 |
| `ley-1990-004/` | Ley 4/1990, de 31 de mayo, de Ordenación del Territorio del País Vasco. | 5 | as first published, then each change: 4 July 1990 to 1 January 2022 | 2025-12-19 |
| `ley-1990-005/` | Ley 5/1990, de 15 de junio, de Elecciones al Parlamento Vasco. | 7 | as first published, then each change: 7 July 1990 to 5 May 2026 | 2026-06-01 |
| `ley-1990-007/` | Ley 7/1990, de 3 de julio, de Patrimonio Cultural Vasco. | 7 | as first published, then each change: 7 August 1990 to 14 July 2022 | 2025-12-19 |
| `ley-1991-004/` | Ley 4/1991, de 8 de noviembre, reguladora del juego en la Comunidad Autónoma del País Vasco. | 3 | as first published, then each change: 26 November 1991 to 1 May 2012 | 2025-12-19 |
| `ley-1992-002/` | Ley 2/1992, de 8 de mayo, de ordenación del personal al servicio del Consejo de Relaciones Laborales. | 1 | as first published: 12 June 1992 | 2025-12-19 |
| `ley-1992-005/` | Ley 5/1992, de 16 de octubre, por la que se complementa la Ley 1/1990, de 6 de abril, de determinación de la capitalidad de los Partidos Judiciales de la Comunidad Autónoma del País Vasco. | 1 | as first published: 3 November 1992 | 2025-12-19 |
| `ley-1992-006/` | Ley 6/1992, de 16 de octubre, del Impuesto sobre el Juego del Bingo y del recargo de la tasa sobre el juego que se desarrolla mediante máquinas o aparatos automáticos aptos para la realización de juegos de azar. | 5 | as first published, then each change: 1 January 1993 to 1 January 2020 | 2025-12-19 |
| `ley-1992-007/` | Ley 7/1992, de 21 de diciembre, que regula determinados aspectos relacionados con Zonas Regables, Planes Comarcales de Mejora y Planes Generales de Transformación. | 1 | as first published: 19 January 1993 | 2025-12-19 |
| `ley-1993-007/` | Ley 7/1993, de 21 de diciembre, de creación de OSALAN - Instituto Vasco de Seguridad y Salud Laborales. | 3 | as first published, then each change: 8 January 1994 to 1 January 2012 | 2025-12-19 |
| `ley-1994-007/` | Ley 7/1994, de 27 de mayo, de la Actividad Comercial. | 6 | as first published, then each change: 3 July 1994 to 10 July 2019 | 2025-12-19 |
| `ley-1994-008/` | Ley 8/1994, de 27 de mayo, de relaciones con las colectividades y centros vascos en el exterior de la Comunidad Autónoma del País Vasco. | 1 | as first published: 3 July 1994 | 2025-12-19 |
| `ley-1994-011/` | Ley 11/1994, de 17 de junio, de Ordenación Farmacéutica de la Comunidad Autónoma del País Vasco. | 3 | as first published, then each change: 4 August 1994 to 16 May 2012 | 2025-12-19 |
| `ley-1994-013/` | Ley 13/1994, de 30 de junio, por la que se regula la Comisión Arbitral. | 1 | as first published: 16 August 1994 | 2025-12-19 |
| `ley-1996-002/` | Ley 2/1996, de 10 de mayo, de Organizaciones Interprofesionales Agroalimentarias del País Vasco. | 1 | as first published: 1 June 1996 | 2025-12-19 |
| `ley-1996-008/` | Ley 8/1996, de 8 de noviembre, de Finanzas de la Comunidad Autónoma de Euskadi. | 6 | as first published, then each change: 1 January 1997 to 1 January 2012 | 2025-12-19 |
| `ley-1997-005/` | Ley 5/1997, de 30 de mayo, reguladora de utilización y control de los créditos destinados a gastos reservados. | 1 | as first published: 25 June 1997 | 2025-12-19 |
| `ley-1997-008/` | Ley 8/1997, de 26 de junio, de Ordenación Sanitaria de Euskadi. | 2 | as first published, then each change: 22 July 1997 to 1 January 2024 | 2025-12-19 |
| `decreto-legislativo-1997-001/` | Decreto Legislativo 1/1997, de 11 de noviembre, por el que se aprueba el Texto Refundido de la Ley de Principios Ordenadores de la Hacienda General del País Vasco. | 18 | oldest version available, then each change: 20 January 1998 to 30 December 2023 | 2024-04-04 |
| `ley-1997-018/` | Ley 18/1997, de 21 de noviembre, de ejercicio de profesiones tituladas y de colegios y consejos profesionales. | 3 | as first published, then each change: 31 December 1997 to 28 October 2014 | 2025-12-19 |
| `ley-1997-019/` | Ley 19/1997, de 21 de noviembre, de creación del Colegio Profesional de Podólogos del País Vasco. | 1 | as first published: 12 December 1997 | 2025-12-19 |
| `ley-1997-020/` | Ley 20/1997, de 4 de diciembre, para la Promoción de la Accesibilidad. | 1 | as first published: 24 April 1998 | 2025-12-19 |
| `ley-1998-006/` | Ley 6/1998, de 13 de marzo, de Pesca Marítima. | 2 | as first published, then each change: 21 April 1998 to 18 June 2015 | 2025-12-19 |
| `ley-1998-009/` | Ley 9/1998, de 3 de abril, para la Integración del Conservatorio de Música de grado medio de Donostia (Donostia-San Sebastián) y del Conservatorio de Música de grado medio "Jesús Guridi" (Vitoria-Gasteiz) en la red pública de Centros Docentes Dependiente de la Administración General de la Comunidad Autónoma del País Vasco. | 1 | as first published: 5 May 1998 | 2025-12-19 |
| `ley-1998-016/` | Ley 16/1998, de 25 de junio, de Cofradías de Pescadores. | 1 | as first published: 30 July 1998 | 2025-12-19 |
| `ley-1998-017/` | Ley 17/1998, de 25 de junio, del Voluntariado. | 1 | as first published: 14 July 1998 | 2025-12-19 |
| `ley-2000-002/` | Ley 2/2000, de 29 de junio, de Transporte Público Urbano e Interurbano de Viajeros en Automóviles de Turismo. | 1 | as first published: 2 August 2000 | 2025-12-19 |
| `ley-2000-003/` | Ley 3/2000, de 29 de junio, de creación del Colegio de Ingenieros en Informática del País Vasco. | 1 | as first published: 3 August 2000 | 2025-12-19 |
| `ley-2000-010/` | Ley 10/2000, de 27 de diciembre, de Carta de Derechos Sociales. | 4 | as first published, then each change: 1 January 2001 to 1 January 2009 | 2025-12-19 |
| `ley-2001-001/` | Ley 1/2001, de 16 de marzo, de creación del Colegio Oficial de Fisioterapeutas del País Vasco. | 1 | as first published: 12 April 2001 | 2025-12-19 |
| `ley-2002-007/` | Ley 7/2002, de 12 de diciembre, de las voluntades anticipadas en el ámbito de la sanidad. | 1 | as first published: 31 December 2002 | 2025-12-19 |
| `ley-2003-002/` | Ley 2/2003, de 7 de mayo, reguladora de las parejas de hecho. | 5 | as first published, then each change: 24 May 2003 to 3 October 2015 | 2025-12-19 |
| `ley-2003-005/` | Ley 5/2003, de 15 de diciembre, de la Autoridad del Transporte de Euskadi. | 2 | as first published, then each change: 25 December 2003 to 24 November 2023 | 2025-12-19 |
| `ley-2003-007/` | Ley 7/2003, de 22 de diciembre, de creación del Colegio de Educadoras y Educadores Sociales del País Vasco. | 1 | as first published: 31 December 2003 | 2025-12-19 |
| `ley-2004-003/` | Ley 3/2004, de 25 de febrero, del Sistema Universitario Vasco. | 5 | as first published, then each change: 1 April 2004 to 5 July 2012 | 2025-12-19 |
| `ley-2004-004/` | Ley 4/2004, de 18 de marzo, de Transporte de Viajeros por Carretera. | 1 | oldest version available: 30 March 2004 | 2025-12-19 |
| `ley-2004-005/` | Ley 5/2004, de 7 de mayo, de Ordenación Vitivinícola. | 2 | as first published, then each change: 25 May 2004 to 1 May 2012 | 2025-12-19 |
| `ley-2004-006/` | Ley 6/2004, de 21 de mayo, de Red Ferroviaria Vasca-Euskal Trenbide Sarea. | 1 | as first published: 2 September 2004 | 2025-12-19 |
| `ley-2004-008/` | Ley 8/2004, de 12 de noviembre, de Industria de la Comunidad Autónoma de Euskadi. | 2 | as first published, then each change: 29 December 2004 to 1 May 2012 | 2025-12-19 |
| `ley-2004-009/` | Ley 9/2004, de 24 de noviembre, de la Comisión Jurídica Asesora de Euskadi. | 1 | as first published: 16 December 2004 | 2025-12-19 |
| `ley-2006-001/` | Ley 1/2006, de 23 de junio, de Aguas. | 10 | as first published, then each change: 19 January 2007 to 22 February 2024 | 2025-12-19 |
| `ley-2006-002/` | Ley 2/2006, de 30 de junio, de Suelo y Urbanismo. | 16 | as first published, then each change: 20 September 2006 to 30 December 2025 | 2026-01-22 |
| `ley-2006-004/` | Ley 4/2006, de 10 de noviembre, de creación del Colegio de Logopedas del País Vasco | 1 | as first published: 24 November 2006 | 2025-12-19 |
| `ley-2006-007/` | Ley 7/2006, de 1 de diciembre, de Museos de Euskadi. | 2 | as first published, then each change: 18 March 2007 to 1 May 2012 | 2025-12-19 |
| `ley-2006-010/` | Ley 10/2006, de 29 de diciembre, de Agricultura y Alimentación Ecológica de Euskadi. | 1 | as first published: 6 January 2007 | 2025-12-19 |
| `ley-2007-003/` | Ley 3/2007, de 20 de abril, de Creación y Regulación del Instituto Vasco Etxepare Euskal Institutua / Basque Institute. | 1 | as first published: 11 May 2007 | 2025-12-19 |
| `ley-2007-007/` | Ley 7/2007, de 22 de junio, de Asociaciones de Euskadi. | 1 | as first published: 13 July 2007 | 2025-12-19 |
| `ley-2007-009/` | Ley 9/2007, de 29 de junio, de creación de Kontsumobide-Instituto Vasco de Consumo. | 1 | as first published: 21 July 2007 | 2025-12-19 |
| `ley-2007-010/` | Ley 10/2007, de 29 de junio, sobre Perros de Asistencia para la Atención a Personas con Discapacidad. | 1 | as first published: 21 July 2007 | 2025-12-19 |
| `ley-2007-011/` | Ley 11/2007, de 26 de octubre, de Bibliotecas de Euskadi. | 1 | as first published: 9 December 2007 | 2025-12-19 |
| `decreto-legislativo-2007-002/` | Decreto Legislativo 2/2007, de 6 de noviembre, de aprobación del Texto Refundido de la Ley del Patrimonio de Euskadi. | 4 | oldest version available, then each change: 23 January 2008 to 1 January 2026 | 2026-01-20 |
| `ley-2007-014/` | Ley 14/2007, de 28 de diciembre, de Carta de Justicia y Solidaridad con los Países Empobrecidos. | 1 | as first published: 10 January 2008 | 2025-12-19 |
| `ley-2008-001/` | Ley 1/2008, de 8 de febrero, de Mediación Familiar. | 2 | as first published, then each change: 19 February 2008 to 1 May 2012 | 2025-12-19 |
| `ley-2008-004/` | Ley 4/2008, de 19 de junio, de Reconocimiento y Reparación a las Víctimas del Terrorismo. | 1 | oldest version available: 2 July 2008 | 2025-12-19 |
| `ley-2008-005/` | Ley 5/2008, de 19 de junio, por la que se crea y regula la Agencia Vasca de Cooperación para el Desarrollo. | 2 | as first published, then each change: 11 July 2008 to 1 March 2024 | 2025-12-19 |
| `ley-2008-010/` | Ley 10/2008, de 10 de octubre, de creación del Colegio Profesional de Terapeutas Ocupacionales del País Vasco. | 1 | as first published: 25 October 2008 | 2025-12-19 |
| `ley-2008-012/` | Ley 12/2008, de 5 de diciembre, de Servicios Sociales. | 2 | as first published, then each change: 25 December 2008 to 1 May 2012 | 2025-12-19 |
| `ley-2008-013/` | Ley 13/2008, de 12 de diciembre, de Apoyo a las Familias. | 1 | as first published: 23 January 2009 | 2025-12-19 |
| `ley-2008-014/` | Ley 14/2008, de 12 de diciembre, de Creación del Colegio Oficial de Dietistas-Nutricionistas del País Vasco. | 1 | as first published: 25 December 2008 | 2025-12-19 |
| `ley-2008-015/` | Ley 15/2008, de 19 de diciembre, de creación de diversos cuerpos docentes de la enseñanza no universitaria de la Comunidad Autónoma del País Vasco. | 1 | as first published: 30 December 2008 | 2025-12-19 |
| `ley-2008-017/` | Ley 17/2008, de 23 de diciembre, de Política Agraria y Alimentaria. | 5 | as first published, then each change: 1 January 2009 to 16 July 2022 | 2025-12-19 |
| `ley-2010-006/` | Ley 6/2010, de 23 de diciembre, de publicidad y comunicación institucional de Euskadi. | 1 | as first published: 1 January 2011 | 2025-12-19 |
| `ley-2011-002/` | Ley 2/2011, de 17 de marzo, de caza. | 5 | as first published, then each change: 30 March 2011 to 4 April 2025 | 2025-12-19 |
| `decreto-legislativo-2011-001/` | Decreto Legislativo 1/2011, de 24 de mayo, por el que se aprueba el texto refundido de las disposiciones legales vigentes en materia de régimen presupuestario de Euskadi y se regula el régimen presupuestario aplicable a las fundaciones y consorcios del sector público de la Comunidad Autónoma de Euskadi. | 4 | as first published, then each change: 29 June 2011 to 21 May 2022 | 2025-12-19 |
| `ley-2012-001/` | Ley 1/2012, de 2 de febrero, de la Autoridad Vasca de la Competencia. | 2 | as first published, then each change: 10 February 2012 to 26 May 2026 | 2026-06-03 |
| `ley-2012-004/` | Ley 4/2012, de 23 de febrero, de Lan Harremanen Kontseilua/Consejo de Relaciones Laborales. | 1 | as first published: 6 March 2012 | 2025-12-19 |
| `ley-2012-005/` | Ley 5/2012, de 23 de febrero, sobre Entidades de Previsión Social Voluntaria. | 2 | as first published, then each change: 7 March 2012 to 4 July 2014 | 2025-12-19 |
| `ley-2012-008/` | Ley 8/2012, de 17 de mayo, del Consejo Económico y Social Vasco/Euskadiko Ekonomia eta Gizarte Arazoetarako Batzordea. | 1 | as first published: 25 May 2012 | 2025-12-19 |
| `ley-2012-011/` | Ley 11/2012, de 14 de junio, de Cajas de Ahorros de la Comunidad Autónoma de Euskadi. | 1 | as first published: 23 June 2012 | 2025-12-19 |
| `ley-2012-012/` | Ley 12/2012, de 21 de junio, contra el Dopaje en el Deporte. | 4 | as first published, then each change: 28 September 2012 to 21 May 2025 | 2025-12-19 |
| `ley-2012-013/` | Ley 13/2012, de 28 de junio, de Unibasq-Agencia de Calidad del Sistema Universitario Vasco. | 1 | as first published: 5 July 2012 | 2025-12-19 |
| `ley-2012-015/` | Ley 15/2012, de 28 de junio, de Ordenación del Sistema de Seguridad Pública de Euskadi. | 7 | as first published, then each change: 7 July 2012 to 7 August 2020 | 2025-12-19 |
| `ley-2012-016/` | Ley 16/2012, de 28 de junio, de Apoyo a las Personas Emprendedoras y a la Pequeña Empresa del País Vasco. | 1 | as first published: 7 July 2012 | 2025-12-19 |
| `ley-2012-017/` | Ley 17/2012, de 28 de junio, de Creación del Colegio Vasco de Periodistas. | 1 | as first published: 7 July 2012 | 2025-12-19 |
| `ley-2013-001/` | Ley 1/2013, de 10 de octubre, de Aprendizaje a lo Largo de la Vida. | 2 | as first published, then each change: 18 October 2013 to 6 July 2018 | 2025-12-19 |
| `ley-2014-001/` | Ley 1/2014, de 26 de junio, Reguladora del Código de Conducta y de los Conflictos de Intereses de los Cargos Públicos. | 1 | as first published: 1 November 2014 | 2025-12-19 |
| `ley-2014-004/` | Ley 4/2014, de 27 de noviembre, de creación del Instituto de la Memoria, la Convivencia y los Derechos Humanos. | 3 | as first published, then each change: 22 December 2014 to 18 October 2023 | 2025-12-19 |
| `ley-2015-003/` | Ley 3/2015, de 18 de junio, de vivienda. | 7 | as first published, then each change: 26 September 2015 to 30 December 2025 | 2026-01-20 |
| `ley-2015-004/` | Ley 4/2015, de 25 de junio, para la prevención y corrección de la contaminación del suelo. | 3 | as first published, then each change: 3 July 2015 to 30 December 2025 | 2026-01-20 |
| `ley-2015-005/` | Ley 5/2015, de 25 de junio, de Derecho Civil Vasco. | 1 | as first published: 3 October 2015 | 2025-12-19 |
| `ley-2015-006/` | Ley 6/2015, de 30 de junio, de medidas adicionales de protección medioambiental para la extracción de hidrocarburos no convencionales y la fractura hidráulica o "fracking". | 5 | as first published, then each change: 10 July 2015 to 21 August 2018 | 2025-12-19 |
| `ley-2015-007/` | Ley 7/2015, de 30 de junio, de relaciones familiares en supuestos de separación o ruptura de los progenitores. | 1 | as first published: 10 October 2015 | 2025-12-19 |
| `ley-2015-008/` | Ley 8/2015, de 15 de octubre, del Estatuto de las Mujeres Agricultoras. | 1 | as first published: 22 October 2015 | 2025-12-19 |
| `ley-2015-010/` | Ley 10/2015, de 23 de diciembre, de Espectáculos Públicos y Actividades Recreativas. | 1 | as first published: 8 January 2016 | 2025-12-19 |
| `ley-2016-001/` | Ley 1/2016, de 7 de abril, de Atención Integral de Adicciones y Drogodependencias. | 4 | as first published, then each change: 14 April 2016 to 13 April 2018 | 2025-12-19 |
| `ley-2016-002/` | Ley 2/2016, de 7 de abril, de Instituciones Locales de Euskadi. | 4 | as first published, then each change: 15 April 2016 to 30 December 2025 | 2026-01-20 |
| `ley-2016-003/` | Ley 3/2016, de 7 de abril, para la inclusión de determinadas cláusulas sociales en la contratación pública. | 1 | as first published: 15 June 2016 | 2025-12-19 |
| `ley-2016-006/` | Ley 6/2016, de 12 de mayo, del Tercer Sector Social de Euskadi. | 2 | as first published, then each change: 20 May 2016 to 1 January 2024 | 2025-12-19 |
| `ley-2016-007/` | Ley 7/2016, de 2 de junio, de Ordenación del Servicio Jurídico del Gobierno Vasco. | 1 | as first published: 8 June 2016 | 2025-12-19 |
| `ley-2016-009/` | Ley 9/2016, de 2 de junio, de Fundaciones del País Vasco. | 1 | as first published: 14 June 2016 | 2025-12-19 |
| `ley-2016-010/` | Ley 10/2016, de 30 de junio, reguladora de la Iniciativa Legislativa Popular. | 1 | as first published: 8 July 2016 | 2025-12-19 |
| `ley-2016-011/` | Ley 11/2016, de 8 de julio, de garantía de los derechos y de la dignidad de las personas en el proceso final de su vida. | 1 | as first published: 14 October 2016 | 2025-12-19 |
| `ley-2016-012/` | Ley 12/2016, de 28 de julio, de reconocimiento y reparación de víctimas de vulneraciones de derechos humanos en el contexto de la violencia de motivación política en la Comunidad Autónoma del País Vasco entre 1978 y 1999. | 8 | as first published, then each change: 11 August 2016 to 1 January 2026 | 2026-01-20 |
| `ley-2016-013/` | Ley 13/2016, de 28 de julio, de Turismo. | 2 | as first published, then each change: 31 August 2016 to 30 December 2025 | 2026-01-20 |
| `decreto-legislativo-2017-001/` | Decreto Legislativo 1/2017, de 27 de abril, por el que se aprueba el texto refundido de la Ley de Gestión de Emergencias. | 2 | oldest version available, then each change: 6 May 2017 to 8 December 2023 | 2025-12-19 |
| `decreto-legislativo-2017-002/` | Decreto Legislativo 2/2017, de 19 de octubre, por el que se aprueba el texto refundido de la Ley de Control Económico y Contabilidad de la Comunidad Autónoma de Euskadi. | 4 | as first published, then each change: 14 November 2017 to 1 January 2024 | 2025-12-19 |
| `ley-2018-002/` | Ley 2/2018, de 28 de junio, de Puertos y Transporte Marítimo del País Vasco. | 1 | as first published: 5 October 2018 | 2025-12-20 |
| `ley-2018-004/` | Ley 4/2018, de 28 de junio, de Formación Profesional del País Vasco. | 1 | as first published: 6 July 2018 | 2025-12-20 |
| `ley-2019-004/` | Ley 4/2019, de 21 de febrero, de sostenibilidad energética de la Comunidad Autónoma Vasca. | 3 | as first published, then each change: 1 March 2019 to 22 February 2024 | 2025-12-20 |
| `ley-2019-006/` | Ley 6/2019, de 9 de mayo, de Patrimonio Cultural Vasco. | 2 | oldest version available, then each change: 21 May 2019 to 4 January 2024 | 2025-12-20 |
| `ley-2019-010/` | Ley 10/2019, de 27 de junio, de ordenación territorial de grandes establecimientos comerciales. | 1 | as first published: 10 July 2019 | 2025-12-20 |
| `ley-2019-011/` | Ley 11/2019, de 20 de diciembre, de Cooperativas de Euskadi. | 4 | as first published, then each change: 29 January 2020 to 15 January 2025 | 2026-02-06 |
| `decreto-legislativo-2020-001/` | Decreto Legislativo 1/2020, de 22 de julio, por el que se aprueba el texto refundido de la Ley de Policía del País Vasco. | 2 | as first published, then each change: 7 August 2020 to 22 March 2021 | 2025-12-20 |
| `ley-2021-003/` | Ley 3/2021, de 30 de septiembre, de creación de Aukerak, Agencia Vasca de Reinserción Social. | 1 | as first published: 7 October 2021 | 2025-12-20 |
| `ley-2021-004/` | Ley 4/2021, de 7 de octubre, de metodología de distribución de recursos y de determinación de las aportaciones de las diputaciones forales a la financiación de los presupuestos de la Comunidad Autónoma del País Vasco aplicable al periodo 2022-2026. | 1 | as first published: 1 January 2022 | 2025-12-20 |
| `ley-2021-007/` | Ley 7/2021, de 11 de noviembre, de los cuerpos y de las escalas de la Administración de la Comunidad Autónoma de Euskadi. | 2 | as first published, then each change: 23 November 2021 to 27 December 2022 | 2025-12-20 |
| `ley-2021-009/` | Ley 9/2021, de 25 de noviembre, de conservación del patrimonio natural de Euskadi. | 2 | as first published, then each change: 10 April 2022 to 22 February 2024 | 2025-12-20 |
| `ley-2021-010/` | Ley 10/2021, de 9 de diciembre, de Administración Ambiental de Euskadi. | 4 | as first published, then each change: 1 January 2022 to 1 January 2026 | 2026-02-09 |
| `ley-2022-002/` | Ley 2/2022, de 10 de marzo, de Juventud. | 2 | as first published, then each change: 26 March 2022 to 19 June 2026 | 2026-06-29 |
| `ley-2022-003/` | Ley 3/2022, de 12 de mayo, del Sector Público Vasco. | 1 | as first published: 21 May 2022 | 2025-12-20 |
| `ley-2022-004/` | Ley 4/2022, de 19 de mayo, del Recurso de Casación Civil Vasco. | 1 | as first published: 21 June 2022 | 2025-12-20 |
| `ley-2022-005/` | Ley 5/2022, de 23 de junio, de Gestión Documental Integral y Patrimonio Documental de la Comunidad Autónoma del País Vasco. | 1 | as first published: 14 July 2022 | 2025-12-20 |
| `ley-2022-006/` | Ley 6/2022, de 30 de junio, del Procedimiento de Elaboración de las Disposiciones de Carácter General. | 1 | as first published: 16 July 2022 | 2025-12-20 |
| `ley-2022-007/` | Ley 7/2022, de 30 de junio, de Desarrollo Rural. | 1 | as first published: 16 July 2022 | 2025-12-20 |
| `ley-2022-008/` | Ley 8/2022, de 30 de junio, sobre acceso y ejercicio de profesiones de la actividad física y del deporte en la Comunidad Autónoma del País Vasco. | 1 | as first published: 20 July 2022 | 2025-12-20 |
| `ley-2022-009/` | Ley 9/2022, de 30 de junio, de protección de los animales domésticos. | 1 | as first published: 18 August 2022 | 2025-12-20 |
| `ley-2022-011/` | Ley 11/2022, de 1 de diciembre, de Empleo Público Vasco. | 2 | as first published, then each change: 27 December 2022 to 7 July 2026 | 2026-07-14 |
| `ley-2022-012/` | Ley 12/2022, de 15 de diciembre, del transporte por cable. | 1 | as first published: 29 December 2022 | 2025-12-20 |
| `ley-2022-014/` | Ley 14/2022, de 22 de diciembre, del Sistema Vasco de Garantía de Ingresos y para la Inclusión. | 5 | oldest version available, then each change: 29 March 2023 to 1 January 2026 | 2026-01-20 |
| `ley-2023-001/` | Ley 1/2023, de 16 de marzo, de la potestad sancionadora de las Administraciones Públicas Vascas. | 1 | as first published: 27 June 2023 | 2025-12-20 |
| `decreto-legislativo-2023-001/` | Decreto Legislativo 1/2023, de 16 de marzo, por el que se aprueba el texto refundido de la Ley para la Igualdad de Mujeres y Hombres y Vidas Libres de Violencia Machista contra las Mujeres. | 1 | as first published: 28 March 2023 | 2025-12-20 |
| `ley-2023-002/` | Ley 2/2023, de 30 de marzo, de la actividad física y del deporte del País Vasco. | 1 | as first published: 19 April 2023 | 2025-12-20 |
| `ley-2023-004/` | Ley 4/2023, de 27 de abril, del Estatuto de las personas consumidoras y usuarias. | 1 | as first published: 11 May 2023 | 2025-12-20 |
| `ley-2023-008/` | Ley 8/2023, de 29 de junio, de lugares o centros de culto y diversidad religiosa en la Comunidad Autónoma del País Vasco. | 1 | as first published: 8 August 2023 | 2025-12-20 |
| `decreto-legislativo-2023-002/` | Decreto Legislativo 2/2023, de 21 de septiembre, por el que se aprueba el texto refundido de la Ley de la Escuela Pública Vasca. | 1 | as first published: 14 October 2023 | 2025-12-20 |
| `decreto-legislativo-2023-003/` | Decreto Legislativo 3/2023, de 21 de septiembre, por el que se aprueba el texto refundido de la Ley sobre Régimen Jurídico del Instituto Vasco de Administración Pública. | 1 | as first published: 14 October 2023 | 2025-12-20 |
| `decreto-legislativo-2023-004/` | Decreto Legislativo 4/2023, de 21 de septiembre, por el que se aprueba el texto refundido de la Ley de Cuerpos Docentes de la Enseñanza no Universitaria de la Comunidad Autónoma del País Vasco. | 1 | as first published: 14 October 2023 | 2025-12-20 |
| `decreto-legislativo-2023-005/` | Decreto Legislativo 5/2023, de 21 de septiembre, por el que se aprueba el texto refundido de la Ley sobre el Himno Oficial de Euskadi. | 1 | as first published: 14 October 2023 | 2025-12-20 |
| `decreto-legislativo-2023-006/` | Decreto Legislativo 6/2023, de 21 de septiembre, por el que se aprueba el texto refundido de la Ley de Sede de las Instituciones de la Comunidad Autónoma del País Vasco. | 1 | oldest version available: 14 October 2023 | 2025-12-20 |
| `ley-2023-009/` | Ley 9/2023, de 28 de septiembre, de Memoria Histórica y Democrática de Euskadi. | 1 | as first published: 18 October 2023 | 2025-12-20 |
| `ley-2023-010/` | Ley 10/2023, de 9 de noviembre, del Plan Vasco de Estadística 2023-2026 y de tercera modificación de la Ley de Estadística de la Comunidad Autónoma de Euskadi. | 1 | as first published: 24 November 2023 | 2025-12-20 |
| `ley-2023-011/` | Ley 11/2023, de 9 de noviembre, de movilidad sostenible de Euskadi. | 1 | as first published: 24 November 2023 | 2025-12-20 |
| `ley-2023-012/` | Ley 12/2023, de 23 de noviembre, de los servicios de prevención y extinción de incendios y salvamento. | 1 | as first published: 8 December 2023 | 2025-12-20 |
| `ley-2023-013/` | Ley 13/2023, de 30 de noviembre, de Salud Pública de Euskadi. | 1 | as first published: 1 January 2024 | 2025-12-20 |
| `ley-2023-015/` | Ley 15/2023, de 21 de diciembre, de Empleo. | 4 | as first published, then each change: 30 December 2023 to 1 January 2026 | 2026-01-20 |
| `ley-2023-016/` | Ley 16/2023, de 21 de diciembre, de la Autoridad Vasca de Protección de Datos. | 1 | as first published: 5 January 2024 | 2025-12-20 |
| `ley-2023-017/` | Ley 17/2023, de 21 de diciembre, de Educación de la Comunidad Autónoma del País Vasco. | 1 | as first published: 4 February 2024 | 2025-12-20 |
| `ley-2023-020/` | Ley 20/2023, de 21 de diciembre, Reguladora del Régimen de Subvenciones. | 2 | as first published, then each change: 30 December 2023 to 1 January 2025 | 2026-03-04 |
| `ley-2024-001/` | Ley 1/2024, de 8 de febrero, de Transición Energética y Cambio Climático. | 2 | as first published, then each change: 22 February 2024 to 1 January 2025 | 2025-12-20 |
| `ley-2024-002/` | Ley 2/2024, de 15 de febrero, de Infancia y Adolescencia. | 1 | as first published: 29 August 2024 | 2026-10-29 |
| `ley-2024-003/` | Ley 3/2024, de 15 de febrero, de Cooperación y Solidaridad. | 2 | as first published, then each change: 1 March 2024 to 1 January 2026 | 2026-01-20 |
| `ley-2024-004/` | Ley 4/2024, de 15 de febrero, de no discriminación por motivos de identidad de género y de reconocimiento de los derechos de las personas trans. | 1 | as first published: 1 March 2024 | 2025-12-20 |
| `decreto-legislativo-2025-001/` | Decreto Legislativo 1/2025, de 20 de marzo, por el que se aprueba el Texto Refundido de la Ley de Tasas y Precios Públicos de la Administración de la Comunidad Autónoma del País Vasco. | 2 | as first published, then each change: 5 April 2025 to 1 January 2026 | 2026-01-21 |
| `ley-2025-006/` | Ley 6/2025, de 11 de diciembre, de Medidas Urgentes en materia de Vivienda, Suelo y Urbanismo. | 1 | as first published: 30 December 2025 | 2026-01-30 |
| `boe-a-2026-2625/` | Resolución de 9 de enero de 2026, de la Dirección de Tráfico, del Departamento de Seguridad, por la que se establecen medidas especiales de regulación de tráfico durante el año 2026 en la Comunidad Autónoma del País Vasco. | 1 | as first published: 17 February 2026 | 2026-02-05 |
| `ley-2026-003/` | Ley 3/2026, de 14 de mayo, de Transparencia de Euskadi. | 1 | as first published: 26 May 2026 | 2026-06-04 |
| `ley-1980-001/` | Ley 1/1980, de 23 de mayo, de Sede de las Instituciones de la Comunidad Autónoma del País Vasco. | 2 | as first published, then each change: 23 November 1980 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 6/2023, de 21 de septiembre (BOE-A-2023-23221) | 2025-12-19 |
| `ley-1983-008/` | Ley 8/1983, de 14 de abril, sobre el Himno Oficial de Euskadi. | 2 | as first published, then each change: 11 May 1983 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 5/2023, de 21 de septiembre (BOE-A-2023-23220) | 2025-12-19 |
| `ley-1983-016/` | Ley 16/1983, de 27 de julio, sobre Régimen Jurídico del Instituto Vasco de Administración Pública. | 4 | as first published, then each change: 26 August 1983 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 3/2023, de 21 de septiembre (BOE-A-2023-23218) | 2025-12-19 |
| `ley-1986-008/` | Ley 8/1986, de 26 de junio, de Iniciativa Legislativa Popular. | 2 | as first published, then each change: 10 August 1986 to 8 July 2016; **repealed** 8 July 2016 by Ley 10/2016, de 30 de junio (BOE-A-2016-6996) | 2025-12-19 |
| `ley-1989-006/` | Ley 6/1989, de 6 de julio, de la Función Pública Vasca. | 21 | as first published, then each change: 29 July 1989 to 27 December 2022; **repealed** 27 December 2022 by Ley 11/2022, de 1 de diciembre (BOE-A-2023-353) | 2025-12-19 |
| `ley-1992-003/` | Ley 3/1992, de 1 de julio, del Derecho Civil Foral del País Vasco. | 3 | as first published, then each change: 7 November 1992 to 3 October 2015; **repealed** 3 October 2015 by Ley 5/2015, de 25 de junio (BOE-A-2015-8273) | 2025-12-19 |
| `ley-1992-004/` | Ley 4/1992, de 17 de julio, de Policía del País Vasco. | 7 | as first published, then each change: 12 August 1992 to 7 August 2020; **repealed** 7 August 2020 by Decreto Legislativo 1/2020, de 22 de julio (BOE-A-2020-9740) | 2025-12-19 |
| `ley-1993-001/` | Ley 1/1993, de 19 de febrero, de la Escuela Pública Vasca. | 6 | oldest version available, then each change: 26 February 1993 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 2/2023, de 21 de septiembre (BOE-A-2023-23217) | 2026-08-21 |
| `ley-1993-002/` | Ley 2/1993, de 19 de febrero, de Cuerpos Docentes de la Enseñanza no Universitaria de la Comunidad Autónoma del País Vasco. | 4 | as first published, then each change: 26 February 1993 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 4/2023, de 21 de septiembre (BOE-A-2023-23219) | 2025-12-19 |
| `ley-1993-004/` | Ley 4/1993, de 24 de junio, de Cooperativas de Euskadi. | 7 | as first published, then each change: 18 August 1993 to 29 January 2020; **repealed** 29 January 2020 by Ley 11/2019, de 20 de diciembre (BOE-A-2020-615) | 2025-12-19 |
| `ley-1993-006/` | Ley 6/1993, de 29 de octubre, de Protección de los Animales. | 3 | as first published, then each change: 16 November 1993 to 18 August 2022; **repealed** 18 August 2022 by Ley 9/2022, de 30 de junio (BOE-A-2022-14086) | 2025-12-19 |
| `ley-1997-004/` | Ley 4/1997, de 30 de mayo, de reconocimiento de la Universidad "Mondragon Unibertsitatea". | 2 | as first published, then each change: 20 June 1997 to 14 October 2023; **repealed** 14 October 2023 by Decreto Legislativo 7/2023, de 21 de septiembre (BOE-A-2023-23222) | 2025-12-19 |
| `ley-1998-002/` | Ley 2/1998, de 20 de febrero, de la potestad sancionadora de las Administraciones Públicas de la Comunidad Autónoma del País Vasco. | 2 | as first published, then each change: 12 June 1998 to 27 June 2023; **repealed** 27 June 2023 by Ley 1/2023, de 16 de marzo (BOE-A-2023-9167) | 2025-12-19 |
| `ley-1998-010/` | Ley 10/1998, de 8 de abril, de Desarrollo Rural. | 2 | as first published, then each change: 5 May 1998 to 16 July 2022; **repealed** 16 July 2022 by Ley 7/2022, de 30 de junio (BOE-A-2022-12589) | 2025-12-19 |
| `ley-1998-014/` | Ley 14/1998, de 11 de junio, del Deporte del País Vasco. | 8 | as first published, then each change: 15 July 1998 to 19 April 2023; **repealed** 19 April 2023 by Ley 2/2023, de 30 de marzo (BOE-A-2023-10639) | 2025-12-19 |
| `ley-2003-006/` | Ley 6/2003, de 22 de diciembre, de Estatuto de las Personas Consumidoras y Usuarias. | 5 | as first published, then each change: 31 December 2003 to 11 May 2023; **repealed** 11 May 2023 by Ley 4/2023, de 27 de abril (BOE-A-2023-13537) | 2025-12-19 |
| `ley-2004-001/` | Ley 1/2004, de 25 de febrero, de Ordenación de los Cuerpos y Escalas de la Administración General de la Comunidad Autónoma de Euskadi y sus Organismos Autónomos. | 3 | as first published, then each change: 6 March 2004 to 23 November 2021; **repealed** 23 November 2021 by Ley 7/2021, de 11 de noviembre (BOE-A-2021-20732) | 2025-12-19 |
| `ley-2004-002/` | Ley 2/2004, de 25 de febrero, de Ficheros de Datos de Carácter Personal de Titularidad Pública y de Creación de la Agencia Vasca de Protección de Datos. | 2 | as first published, then each change: 24 March 2004 to 5 January 2024; **repealed** 5 January 2024 by Ley 16/2023, de 21 de diciembre (BOE-A-2024-900) | 2025-12-19 |
| `ley-2005-003/` | Ley 3/2005, de 18 de febrero, de Atención y Protección a la Infancia y la Adolescencia. | 3 | as first published, then each change: 30 April 2005 to 29 August 2024; **repealed** 29 August 2024 by Ley 2/2024, de 15 de febrero (BOE-A-2024-4784) | 2025-12-19 |
| `ley-2005-004/` | Ley 4/2005, de 18 de febrero, para la Igualdad de Mujeres y Hombres. | 5 | as first published, then each change: 3 March 2005 to 28 March 2023; **repealed** 28 March 2023 by Decreto Legislativo 1/2023, de 16 de marzo (BOE-A-2023-9168) | 2025-12-19 |
| `ley-2007-001/` | Ley 1/2007, de 22 de febrero, de Cooperación para el Desarrollo. | 2 | as first published, then each change: 9 March 2007 to 1 March 2024; **repealed** 1 March 2024 by Ley 3/2024, de 15 de febrero (BOE-A-2024-4866) | 2025-12-19 |
| `decreto-legislativo-2007-001/` | Decreto Legislativo 1/2007, de 11 de septiembre, de aprobación del texto refundido de la Ley de Tasas y Precios Públicos de la Administración de la Comunidad Autónoma del País Vasco. | 24 | oldest version available, then each change: 28 December 2007 to 5 April 2025; **repealed** 5 April 2025 by Decreto Legislativo 1/2025, de 20 de marzo (BOE-A-2025-8489) | 2025-04-30 |
| `ley-2008-018/` | Ley 18/2008, de 23 de diciembre, para la Garantía de Ingresos y para la Inclusión Social. | 3 | as first published, then each change: 1 January 2009 to 29 March 2023; **repealed** 29 March 2023 by Ley 14/2022, de 22 de diciembre (BOE-A-2023-1405) | 2025-12-19 |
| `ley-2011-003/` | Ley 3/2011, de 13 de octubre, sobre Lanbide-Servicio Vasco de Empleo. | 3 | as first published, then each change: 3 November 2011 to 29 June 2024; **repealed** 29 June 2024 by Ley 15/2023, de 21 de diciembre (BOE-A-2024-899) | 2025-12-19 |
| `ley-2012-014/` | Ley 14/2012, de 28 de junio, de no discriminación por motivos de identidad de género y de reconocimiento de los derechos de las personas transexuales. | 3 | as first published, then each change: 6 October 2012 to 1 March 2024; **repealed** 1 March 2024 by Ley 4/2024, de 15 de febrero (BOE-A-2024-4867) | 2025-12-19 |
| `decreto-legislativo-2014-001/` | Decreto Legislativo 1/2014, de 15 de abril, por el que se aprueba el texto refundido de la Ley de Conservación de la Naturaleza del País Vasco. | 2 | as first published, then each change: 20 May 2014 to 10 April 2022; **repealed** 10 April 2022 by Ley 9/2021, de 25 de noviembre (BOE-A-2021-20914) | 2025-12-19 |

## Source

The consolidated legislation of the Agencia Estatal Boletín Oficial del Estado (BOE), through its open-data API, <https://www.boe.es/datosabiertos/api/legislacion-consolidada>. For each consolidated norm it gives every block of the text (article, disposition, annex, heading) with every version of that block, the day each version took effect (fecha_vigencia) and the norm that made it (id_norma). Each version here is the whole text as it stood on one of those days. The last column above is the BOE's own last-update date for the consolidated text.

## Dates

- Each commit is dated at **noon, Europe/Madrid, on the day the change took effect**: the fecha_vigencia the BOE gives the new block versions.
- A day on which the BOE records a new block version that changes no words is not a version here.
- Block versions with no in-force date (the BOE's 99999999, a date not yet fixed) are left out.
- An act's first commit is its first publication when the BOE's earliest text is the act as enacted; otherwise it is the oldest version the BOE holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 bis; `da-01.md` the Disposición adicional primera, `dt-` transitional, `dd-` repealing and `df-` final dispositions (`-unica` for "única"); `preambulo.md` the preamble, `firma.md` the signature, `anexo-*.md` the annexes. The book, title, chapter and section headings sit at the top of the file of the article that follows them. One paragraph per line; a table one line per row, cells separated by ` | `.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the BOE's own text of that day, rebuilt from the source XML by a separate reader, and every file's text appears in it.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the norm that changed the text (a law, a decree-law, a ruling of the Constitutional Court), named by its title and BOE identifier, with an e-mail address that cannot exist (`<boe id>@boe.es.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. Only the texts published in the official journals are authentic. The history starts with the oldest text the BOE consolidates for each norm. Only the norms listed above are included; norms the BOE does not consolidate are not.
