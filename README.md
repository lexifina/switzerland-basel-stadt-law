# Basel-Stadt: law history in git

The law of the canton of Basel-Stadt (Kanton Basel-Stadt, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-bs/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

574 acts with 1575 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 446 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-100/` | Verfassung des Kantons Basel-Stadt (SG 111.100) | 11 | oldest version available, then each consolidated version: 1 July 2012 to 3 November 2025 |
| `119-500-giza/` | Gesetz über die internationale Zusammenarbeit zwecks Armutsbekämpfung und Stärkung der nachhaltigen Entwicklung (SG 119.500) | 1 | as enacted, 1 January 2026 |
| `121-100-burg/` | Bürgerrechtsgesetz (SG 121.100) | 5 | oldest version available, then each consolidated version: 1 July 2012 to 1 July 2026 |
| `122-200-nag/` | Gesetz über Niederlassung und Aufenthalt (SG 122.200) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2020 |
| `122-300/` | Gesetz über den Vollzug der Zwangsmassnahmen im Ausländerrecht (SG 122.300) | 1 | as enacted, 2 May 2010 |
| `122-500-integrationsgesetz/` | Gesetz über die Integration der Migrationsbevölkerung (SG 122.500) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 December 2014 |
| `131-100-irg/` | Gesetz betreffend Initiative und Referendum (SG 131.100) | 2 | oldest version available, then each consolidated version: 3 June 2012 to 1 January 2021 |
| `132-100-wahlgesetz/` | Gesetz über Wahlen und Abstimmungen (SG 132.100) | 9 | oldest version available, then each consolidated version: 1 January 2012 to 1 August 2023 |
| `138-100/` | Gesetz betreffend den Austritt in Behörden, die Beschränkung der Stimmgebung bei Wahlen und die Ausschliessung der Wählbarkeit von Verwandten zu Mitgliedern von Behörden (SG 138.100) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2013 |
| `138-200/` | Gesetz betreffend das Verfahren bei Unvereinbarkeit von öffentlichen Stellungen (SG 138.200) | 1 | one version (the oldest available), 1 January 2007 |
| `140-100-kantonales-gleichstellungsgesetz-kglg/` | Kantonales Gleichstellungsgesetz zu Geschlecht und sexueller Orientierung (SG 140.100) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 15 June 2025 |
| `140-500-behindertenrechtegesetz-brg/` | Gesetz über die Rechte von Menschen mit Behinderungen (SG 140.500) | 1 | as enacted, 1 January 2021 |
| `151-100/` | Gesetz betreffend Ausstattung der neuen Gesamtausgabe der Basler Gesetzessammlung mit negativer Rechtskraft (SG 151.100) | 1 | as enacted, 21 August 1960 |
| `151-200-publikationsgesetz/` | Gesetz über Publikationen im Kantonsblatt und über die Gesetzessammlung des Kantons Basel-Stadt (SG 151.200) | 2 | as enacted, then each consolidated version: 1 April 2017 to 1 January 2019 |
| `152-900/` | Gesetz betreffend die Beauftragte/den Beauftragten für das Beschwerdewesen (Ombudsfrau / Ombudsmann) des Kantons Basel-Stadt (SG 152.900) | 2 | oldest version available, then each consolidated version: 28 April 2013 to 1 April 2017 |
| `153-100-organisationsgesetz-og/` | Gesetz betreffend die Organisation des Regierungsrates und der Verwaltung des Kantons Basel-Stadt (SG 153.100) | 3 | oldest version available, then each consolidated version: 1 April 2012 to 1 January 2021 |
| `153-260-informations-und-datenschutzgesetz-idg/` | Gesetz über die Information und den Datenschutz (SG 153.260) | 8 | as enacted, then each consolidated version: 1 January 2012 to 16 January 2025 |
| `153-300-behordenportalgesetz/` | Gesetz über ein zentrales elektronisches Behördenportal (SG 153.300) | 1 | as enacted, 26 February 2017 |
| `153-600-archivgesetz/` | Gesetz über das Archivwesen (SG 153.600) | 1 | one version (the oldest available), 1 January 2012 |
| `153-800/` | Gesetz über die Verwaltungsgebühren (SG 153.800) | 1 | one version (the oldest available), 27 June 1993 |
| `154-100-gerichtsorganisationsgesetz-gog/` | Gesetz betreffend die Organisation der Gerichte und der Staatsanwaltschaft (SG 154.100) | 8 | oldest version available, then each consolidated version: 3 February 2011 to 15 June 2025 |
| `154-200-sozialversicherungsgerichtsgesetz-svgg/` | Gesetz über das Sozialversicherungsgericht des Kantons Basel-Stadt und über das Schiedsgericht in Sozialversicherungssachen (SG 154.200) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2016 |
| `154-800/` | Gesetz über die Gerichtsgebühren (SG 154.800) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 5 July 2018 |
| `161-100-haftungsgesetz-hg/` | Gesetz über die Haftung des Staates und seines Personals (SG 161.100) | 1 | one version (the oldest available), 13 July 2006 |
| `162-100/` | Personalgesetz (SG 162.100) | 7 | oldest version available, then each consolidated version: 1 January 2012 to 15 June 2025 |
| `164-100-lg/` | Lohngesetz (SG 164.100) | 12 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2027 |
| `165-100/` | Gesetz betreffend die Versicherung der Mitarbeiterinnen und Mitarbeiter des Kantons Basel-Stadt bei Unfall und Krankheit (SG 165.100) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2017 |
| `166-100-pensionskassengesetz-pkg/` | Gesetz betreffend die Pensionskasse Basel-Stadt (SG 166.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2016 |
| `170-100/` | Gemeindegesetz (SG 170.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 7 December 2014 |
| `170-600-filag/` | Finanz- und Lastenausgleichgesetz (SG 170.600) | 3 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2021 |
| `171-300/` | Gesetz betreffend Verschmelzung der Gemeinde Kleinhüningen mit der Stadt Basel (SG 171.300) | 1 | as enacted, 30 November 1907 |
| `171-700/` | Gesetz betreffend die Ausscheidung der Aktiven der Einwohnergemeinde der Stadt Basel (SG 171.700) | 1 | as enacted, 25 April 1968 |
| `190-100-kirchengesetz/` | Gesetz betreffend die Staatsoberaufsicht über die öffentlich-rechtlichen Kirchen und die Israelitische Gemeinde sowie über die Verwendung von Staats- und Gemeindemitteln zu Kirchenzwecken (SG 190.100) | 2 | as enacted, then each consolidated version: 26 June 1998 to 26 January 2014 |
| `211-100/` | Gesetz betreffend die Einführung des Schweizerischen Zivilgesetzbuches (SG 211.100) | 8 | oldest version available, then each consolidated version: 1 January 2012 to 1 April 2024 |
| `212-400-kesg/` | Kindes- und Erwachsenenschutzgesetz (SG 212.400) | 3 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `212-850-eg-bg-kke/` | Einführungsgesetz zum Bundesgesetz über internationale Kindesentführung und die Haager Übereinkommen zum Schutz von Kindern und Erwachsenen (SG 212.850) | 1 | as enacted, 29 December 2009 |
| `214-300-kgeoig/` | Geoinformationsgesetz (SG 214.300) | 2 | as enacted, then each consolidated version: 1 September 2012 to 1 January 2025 |
| `214-610/` | Gesetz betreffend die Einführung von weiteren Bewilligungsgründen für den Erwerb von Grundstücken durch Personen im Ausland (SG 214.610) | 1 | one version (the oldest available), 1 October 1997 |
| `215-400-schlichtungsstellengesetz/` | Gesetz über die Staatliche Schlichtungsstelle für Mietstreitigkeiten (SG 215.400) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 6 November 2016 |
| `230-100/` | Gesetz betreffend Einführung des Bundesgesetzes über Schuldbetreibung und Konkurs (SG 230.100) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 13 June 2024 |
| `230-900/` | Gesetz betreffend das Gantwesen (SG 230.900) | 2 | oldest version available, then each consolidated version: 26 June 2005 to 1 January 2013 |
| `253-100-ustg/` | Übertretungsstrafgesetz (SG 253.100) | 10 | oldest version available, then each consolidated version: 1 July 2011 to 1 September 2021 |
| `257-900-eg-ohg/` | Einführungsgesetz zum Bundesgesetz über die Hilfe an Opfer von Straftaten (SG 257.900) | 1 | one version (the oldest available), 1 January 2011 |
| `258-100-begnadigungsgesetz/` | Gesetz über die Begnadigung (SG 258.100) | 1 | one version (the oldest available), 26 May 2013 |
| `258-200-justizvollzugsgesetz-jvg/` | Gesetz über den Justizvollzug (SG 258.200) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2020 |
| `258-400-jugendstrafvollzugsgesetz-jstvg/` | Gesetz über den Vollzug von jugendstrafrechtlichen Sanktionen (SG 258.400) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2021 |
| `270-100-vrpg/` | Gesetz über die Verfassungs- und Verwaltungsrechtspflege (SG 270.100) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `291-100/` | Advokaturgesetz (SG 291.100) | 3 | oldest version available, then each consolidated version: 29 November 2009 to 1 July 2020 |
| `292-100-notariatsgesetz-notg/` | Notariatsgesetz des Kantons Basel-Stadt (SG 292.100) | 4 | oldest version available, then each consolidated version: 29 November 2009 to 1 August 2026 |
| `300-100-gesg/` | Gesundheitsgesetz (SG 300.100) | 11 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `300-600-uzbg/` | Gesetz über das Universitäre Zentrum für Zahnmedizin Basel (SG 300.600) | 1 | as enacted, 1 January 2016 |
| `322-100-alkohol-und-drogengesetz/` | Gesetz betreffend Massnahmen gegen den Alkohol- und Medikamentenmissbrauch sowie gegen den Drogenkonsum und betreffend Einführung des revidierten Bundesgesetzes über die Betäubungsmittel vom 20. März 1975 (SG 322.100) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2016 |
| `331-100-offentliche-spitaler-gesetz-ospg/` | Gesetz über die öffentlichen Spitäler des Kantons Basel-Stadt (SG 331.100) | 1 | as enacted, 1 January 2012 |
| `365-100-hundegesetz/` | Gesetz betreffend das Halten von Hunden (SG 365.100) | 3 | as enacted, then each consolidated version: 1 February 2007 to 1 April 2025 |
| `371-100/` | Sportgesetz (SG 371.100) | 3 | as enacted, then each consolidated version: 3 July 2011 to 1 January 2022 |
| `390-100-bestg/` | Bestattungsgesetz (SG 390.100) | 3 | oldest version available, then each consolidated version: 1 February 2012 to 1 April 2021 |
| `410-100/` | Schulgesetz (SG 410.100) | 5 | oldest version available, then each consolidated version: 10 August 2020 to 10 August 2026 |
| `415-100-kinder-und-jugendgesetz-kjg/` | Gesetz betreffend Förder- und Hilfeleistungen für Kinder und Jugendliche (SG 415.100) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 March 2024 |
| `420-200/` | Kantonales Gesetz über die Berufsbildung (SG 420.200) | 5 | oldest version available, then each consolidated version: 29 December 2009 to 1 July 2020 |
| `421-100/` | Gesetz betreffend die Allgemeine Gewerbeschule Basel (AGS Basel) und die Schule für Gestaltung Basel (SfG Basel) (SG 421.100) | 1 | one version (the oldest available), 1 January 2013 |
| `423-100/` | Gesetz betreffend die Berufsfachschule Basel (BFS Basel) (SG 423.100) | 1 | one version (the oldest available), 1 January 2013 |
| `440-400-universitatsgutsgesetz/` | Gesetz über das Universitätsgut (SG 440.400) | 2 | as enacted, then each consolidated version: 1 January 2001 to 26 April 2015 |
| `451-100-museumsgesetz/` | Gesetz über die Museen des Kantons Basel-Stadt (SG 451.100) | 3 | oldest version available, then each consolidated version: 10 April 2005 to 1 February 2025 |
| `453-200-statg/` | Gesetz über die öffentliche Statistik (SG 453.200) | 1 | as enacted, 1 July 2015 |
| `491-100/` | Gesetz betreffend Ausbildungsbeiträge (SG 491.100) | 3 | oldest version available, then each consolidated version: 8 August 2004 to 26 January 2014 |
| `494-300/` | Kulturfördergesetz (SG 494.300) | 5 | as enacted, then each consolidated version: 1 January 2010 to 30 May 2022 |
| `497-100/` | Gesetz über den Denkmalschutz (SG 497.100) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2020 |
| `510-100-polizeigesetz-polg/` | Gesetz betreffend die Kantonspolizei des Kantons Basel-Stadt (SG 510.100) | 9 | oldest version available, then each consolidated version: 1 January 2013 to 1 March 2023 |
| `561-100-eg-bgs/` | Einführungsgesetz zum Bundesgesetz über Geldspiele (SG 561.100) | 2 | oldest version available, then each consolidated version: 1 July 1977 to 1 January 2021 |
| `562-300/` | Gesetz über die Basler Herbstmesse (SG 562.300) | 2 | as enacted, then each consolidated version: 30 May 2012 to 1 January 2014 |
| `563-100-gastgewerbegesetz/` | Gesetz über das Gastgewerbe (SG 563.100) | 4 | oldest version available, then each consolidated version: 1 February 2012 to 25 August 2022 |
| `563-200-taxigesetz/` | Gesetz betreffend das Erbringen von Taxidienstleistungen (SG 563.200) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 July 2020 |
| `569-100-ftg/` | Gesetz betreffend öffentliche Filmvorführungen und Abgabe von elektronischen Trägermedien (SG 569.100) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 July 2020 |
| `576-100-zivil-und-kulturguterschutzgesetz-zkg/` | Gesetz über den Zivilschutz und den Kulturgüterschutz (SG 576.100) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 September 2023 |
| `590-100-feuerwehrgesetz-fwg/` | Gesetz betreffend die Feuerwehr des Kantons Basel-Stadt (SG 590.100) | 1 | as enacted, 1 January 2013 |
| `610-100-finanzhaushaltgesetz-fhg/` | Gesetz über den kantonalen Finanzhaushalt (SG 610.100) | 6 | oldest version available, then each consolidated version: 25 July 2010 to 12 March 2026 |
| `610-200-fvkg/` | Finanz- und Verwaltungskontrollgesetz (SG 610.200) | 6 | oldest version available, then each consolidated version: 1 April 2012 to 1 January 2025 |
| `610-500-stbg/` | Staatsbeitragsgesetz (SG 610.500) | 3 | oldest version available, then each consolidated version: 1 January 1998 to 18 February 2021 |
| `640-100-steuergesetz-stg/` | Gesetz über die direkten Steuern (SG 640.100) | 19 | oldest version available, then each consolidated version: 10 November 2011 to 1 January 2026 |
| `650-100-handanderungssteuergesetz/` | Gesetz über die Handänderungssteuer (SG 650.100) | 2 | oldest version available, then each consolidated version: 24 October 2010 to 1 July 2014 |
| `650-400/` | Gesetz betreffend die Erhebung einer Gasttaxe (SG 650.400) | 2 | oldest version available, then each consolidated version: 29 November 2009 to 1 January 2018 |
| `650-500/` | Gesetz über die Besteuerung der Motorfahrzeuge (SG 650.500) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `695-100/` | Gebäudeversicherungsgesetz (SG 695.100) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2020 |
| `717-100/` | Gesetz über die Ermittlung von Grundstückwerten (SG 717.100) | 1 | one version (the oldest available), 1 January 2009 |
| `724-100-norg/` | Gesetz über die Nutzung des öffentlichen Raumes (SG 724.100) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `727-500/` | Gesetz über Strassenreinigungsbeiträge (SG 727.500) | 1 | one version (the oldest available), 1 January 1994 |
| `730-100-bpg/` | Bau- und Planungsgesetz (SG 730.100) | 14 | oldest version available, then each consolidated version: 28 October 2012 to 18 August 2026 |
| `740-100-enteignungsgesetz/` | Gesetz über Enteignung und Impropriation (SG 740.100) | 1 | one version (the oldest available), 1 January 2011 |
| `771-300/` | Gesetz betreffend Einführung des Bundesgesetzes über Nutzbarmachung der Wasserkräfte (SG 771.300) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2016 |
| `771-500-wassernutzungsgesetz/` | Gesetz über die Nutzung von öffentlichem Fluss- und Grundwasser (SG 771.500) | 1 | as enacted, 29 January 1984 |
| `772-100-eng/` | Energiegesetz (SG 772.100) | 7 | oldest version available, then each consolidated version: 1 April 2012 to 1 July 2024 |
| `772-300-iwb-gesetz/` | Gesetz über die Industriellen Werke Basel (SG 772.300) | 9 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2025 |
| `780-100-usg-bs/` | Umweltschutzgesetz Basel-Stadt (SG 780.100) | 13 | oldest version available, then each consolidated version: 1 July 2011 to 1 January 2026 |
| `780-400/` | Gesetz betreffend den Schutz der Bevölkerung vor Atomkraftwerken (SG 780.400) | 1 | one version (the oldest available), 1 August 1988 |
| `783-400/` | Gesetz über Grundwasserschutzzonen (SG 783.400) | 1 | one version (the oldest available), 1 January 2001 |
| `789-100/` | Gesetz über den Natur- und Landschaftsschutz (SG 789.100) | 3 | as enacted, then each consolidated version: 1 July 1995 to 1 July 2020 |
| `789-700-bschg/` | Baumschutzgesetz (SG 789.700) | 2 | oldest version available, then each consolidated version: 29 November 2009 to 1 July 2020 |
| `790-100-brkg/` | Gesetz betreffend die Baurekurskommission (SG 790.100) | 2 | oldest version available, then each consolidated version: 28 October 2007 to 1 July 2016 |
| `811-100-rlg/` | Gesetz über öffentliche Ruhetage und Ladenöffnung (SG 811.100) | 4 | oldest version available, then each consolidated version: 1 July 2013 to 1 July 2020 |
| `812-100-arbeitsgesetz/` | Einführungsgesetz zum Bundesgesetz über die Arbeit in Industrie, Gewerbe und Handel (SG 812.100) | 1 | one version (the oldest available), 1 January 2009 |
| `812-200-mindestlohngesetz-milog/` | Gesetz über den kantonalen Mindestlohn (SG 812.200) | 1 | as enacted, 1 July 2022 |
| `813-300/` | Gesetz betreffend das ständige staatliche Einigungsamt (SG 813.300) | 2 | oldest version available, then each consolidated version: 29 November 2009 to 1 July 2016 |
| `815-100-tagesbetreuungsgesetz-tbg/` | Gesetz betreffend Tagesbetreuung von Kindern (SG 815.100) | 7 | oldest version available, then each consolidated version: 1 July 2013 to 1 January 2025 |
| `819-400-arbeitsbeschaffungsreservengesetz/` | Gesetz betreffend die Gewährung von Steuervergütungen auf Arbeitsbeschaffungsreserven (SG 819.400) | 1 | one version (the oldest available), 1 January 2009 |
| `819-410/` | Gesetz über die steuerbegünstigten Arbeitsbeschaffungsreserven (SG 819.410) | 1 | one version (the oldest available), 29 December 2009 |
| `820-100-familienzulagengesetz-eg-famzg/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen (SG 820.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `832-200/` | Einführungsgesetz zum Bundesgesetz über die Alters- und Hinterlassenenversicherung (SG 832.200) | 1 | one version (the oldest available), 4 February 2010 |
| `832-500/` | Einführungsgesetz zum Bundesgesetz über die Invalidenversicherung für eine IV-Stelle Basel-Stadt (SG 832.500) | 1 | one version (the oldest available), 1 January 2012 |
| `832-700-eg-elg/` | Gesetz über die Einführung des Bundesgesetzes über die Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung sowie über die Ausrichtung von kantonalen Beihilfen (SG 832.700) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 September 2025 |
| `834-400-gkv/` | Gesetz über die Krankenversicherung im Kanton Basel-Stadt (SG 834.400) | 2 | oldest version available, then each consolidated version: 30 June 2013 to 26 January 2014 |
| `835-200/` | Gesetz betreffend den Fonds zur Bekämpfung der Arbeitslosigkeit (SG 835.200) | 1 | one version (the oldest available), 30 December 2012 |
| `835-500-alhg/` | Gesetz betreffend kantonale Arbeitslosenhilfe (SG 835.500) | 1 | as enacted, 1 January 2005 |
| `861-500-wohnraumfordergesetz-wrfg/` | Gesetz über die Wohnraumförderung (SG 861.500) | 5 | as enacted, then each consolidated version: 1 July 2014 to 17 February 2025 |
| `861-600-wohnstiftungsgesetz-wsg/` | Gesetz über die Stiftung für preisgünstigen Wohnraum Basel-Stadt (SG 861.600) | 1 | as enacted, 1 December 2021 |
| `869-700-bhg/` | Gesetz über die Behindertenhilfe (SG 869.700) | 1 | as enacted, 1 January 2017 |
| `890-100/` | Sozialhilfegesetz (SG 890.100) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2021 |
| `890-500-mietbeitragsgesetz-mbg/` | Gesetz über die Ausrichtung von Mietbeiträgen (SG 890.500) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2025 |
| `890-700-harmonisierungsgesetz-sozialleistungen-sohag/` | Gesetz über die Harmonisierung und Koordination von bedarfsabhängigen Sozialleistungen (SG 890.700) | 5 | oldest version available, then each consolidated version: 26 February 2012 to 1 July 2025 |
| `910-200-stafog/` | Standortförderungsgesetz (SG 910.200) | 5 | oldest version available, then each consolidated version: 30 December 2012 to 30 June 2025 |
| `911-600-wag-bs/` | Waldgesetz Basel-Stadt (SG 911.600) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 July 2020 |
| `911-900/` | Gesetz über Freizeitgärten (SG 911.900) | 1 | as enacted, 1 June 2013 |
| `912-200-wjg/` | Wildtier- und Jagdgesetz (SG 912.200) | 2 | as enacted, then each consolidated version: 4 December 1876 to 1 April 2024 |
| `912-500/` | Gesetz über die Fischerei im Kanton Basel-Stadt (SG 912.500) | 2 | as enacted, then each consolidated version: 1 January 2002 to 1 July 2020 |
| `915-200/` | Gesetz über die Basler Kantonalbank (SG 915.200) | 3 | as enacted, then each consolidated version: 1 January 1995 to 11 July 2024 |
| `951-100/` | Gesetz über den öffentlichen Verkehr (SG 951.100) | 2 | oldest version available, then each consolidated version: 4 December 2012 to 9 July 2015 |
| `952-700/` | Gesetz gegen den Bau von öffentlichen Autoparkgaragen in der Innerstadt (SG 952.700) | 1 | as enacted, 25 June 1990 |
| `953-100-bvb-og/` | Organisationsgesetz der Basler Verkehrs-Betriebe (SG 953.100) | 2 | as enacted, then each consolidated version: 1 January 2006 to 6 June 2016 |
| `955-200/` | Gesetz über die Rheinschiffahrtsgerichte (SG 955.200) | 2 | oldest version available, then each consolidated version: 26 February 1984 to 1 July 2016 |
| `119-510-viza/` | Verordnung über die internationale Zusammenarbeit zwecks Armutsbekämpfung und Stärkung der nachhaltigen Entwicklung (SG 119.510) | 1 | as enacted, 14 May 2026 |
| `121-110-burv/` | Verordnung zum Bürgerrechtsgesetz (SG 121.110) | 7 | oldest version available, then each consolidated version: 1 July 2012 to 1 July 2026 |
| `122-210-niederlassungs-und-aufenthaltsverordnung-nav/` | Verordnung über Niederlassung und Aufenthalt (SG 122.210) | 1 | as enacted, 1 July 2017 |
| `122-510-integrationsverordnung-intv/` | Verordnung zum Gesetz über die Integration der Migrationsbevölkerung (SG 122.510) | 3 | oldest version available, then each consolidated version: 30 June 2013 to 15 June 2025 |
| `122-700/` | Verordnung über die Gebühren für die Bewilligung der Beschäftigung ausländischer Arbeitskräfte (SG 122.700) | 3 | as enacted, then each consolidated version: 23 November 2008 to 9 July 2020 |
| `123-200/` | Verordnung über den Vollzug des Bundesgesetzes zur Wahrung der inneren Sicherheit (SG 123.200) | 2 | as enacted, then each consolidated version: 1 October 2010 to 1 July 2016 |
| `123-410/` | Verordnung betreffend die Umsetzung des Konkordats über Massnahmen gegen Gewalt anlässlich von Sportveranstaltungen (SG 123.410) | 1 | as enacted, 1 January 2010 |
| `132-110-wahlverordnung/` | Verordnung zum Gesetz über Wahlen und Abstimmungen (SG 132.110) | 8 | oldest version available, then each consolidated version: 12 July 2011 to 11 August 2025 |
| `132-150/` | Verordnung über den Testbetrieb für die elektronische Stimmabgabe (SG 132.150) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 June 2023 |
| `133-300-vernehmlassungsverordnung/` | Verordnung über das Vernehmlassungsverfahren (SG 133.300) | 3 | as enacted, then each consolidated version: 18 February 2007 to 23 October 2025 |
| `140-110-glv/` | Gleichstellungsverordnung (SG 140.110) | 1 | as enacted, 15 June 2025 |
| `140-510-behindertenrechteverordnung-brv/` | Verordnung zum Gesetz über die Rechte von Menschen mit Behinderungen (SG 140.510) | 1 | as enacted, 1 January 2021 |
| `151-210-publikationsverordnung-publv/` | Verordnung zum Gesetz über Publikationen im Kantonsblatt und über die Gesetzessammlung des Kantons Basel-Stadt (SG 151.210) | 3 | as enacted, then each consolidated version: 1 January 2019 to 15 June 2025 |
| `152-150/` | Reglement zum Schutz der persönlichen Integrität der Grossratsmitglieder des Kantons Basel-Stadt (SG 152.150) | 1 | as enacted, 1 February 2025 |
| `152-250/` | Reglement über die Teilnahme an Abstimmungen in Abwesenheit (SG 152.250) | 2 | oldest version available, then each consolidated version: 1 February 2025 to 1 September 2026 |
| `152-330/` | Ausgabenreglement für die Grossratskommissionen (SG 152.330) | 1 | as enacted, 8 September 2025 |
| `152-400/` | Reglement über Organisation und Aufgaben des Parlamentsdienstes (SG 152.400) | 2 | as enacted, then each consolidated version: 1 July 2004 to 1 August 2023 |
| `152-500/` | Reglement betreffend Akkreditierung der Medienschaffenden und Zutritt zum Grossen Rat (SG 152.500) | 3 | as enacted, then each consolidated version: 11 December 2005 to 1 September 2021 |
| `153-110/` | Verordnung betreffend die Zuständigkeiten (SG 153.110) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2020 |
| `153-150/` | Verordnung betreffend Organisation und Kompetenzen der Departemente und übrigen Verwaltungseinheiten (SG 153.150) | 1 | as enacted, 1 July 1977 |
| `153-200-kko-vo/` | Verordnung über die Kantonale Krisenorganisation (SG 153.200) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 April 2015 |
| `153-270-informations-und-datenschutzverordnung-idv/` | Verordnung über die Information und den Datenschutz (SG 153.270) | 4 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `153-275-drohnenverordnung/` | Verordnung über den Einsatz von unbemannten Luftfahrzeugen bei der Kantonspolizei als Pilotversuch (SG 153.275) | 2 | as enacted, then each consolidated version: 15 May 2024 to 16 May 2026 |
| `153-310-datenmarktverordnung-dmv/` | Verordnung über den Datenmarkt (SG 153.310) | 4 | as enacted, then each consolidated version: 1 January 2012 to 8 July 2021 |
| `153-320-isv/` | Verordnung über die Informationssicherheit (SG 153.320) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 18 December 2016 |
| `153-340-voagov/` | Verordnung über die Einbindung des Authentifizierungsdienstes der Schweizer Behörden AGOV in das zentrale elektronische Behördenportal (SG 153.340) | 1 | as enacted, 15 June 2024 |
| `153-350-it-governance-verordnung-itgv/` | Verordnung über die IT-Governance der kantonalen Verwaltung (SG 153.350) | 1 | as enacted, 1 March 2026 |
| `153-500/` | Verordnung über die Mitwirkung der Quartierbevölkerung (SG 153.500) | 1 | one version (the oldest available), 1 January 2012 |
| `153-610-registratur-und-archivierungsverordnung/` | Verordnung über die Registraturen und das Archivieren (SG 153.610) | 1 | one version (the oldest available), 1 January 2012 |
| `153-700-bwpv/` | Verordnung betreffend die zentrale elektronische Bewilligungsplattform (SG 153.700) | 2 | as enacted, then each consolidated version: 21 April 2011 to 18 December 2016 |
| `153-810/` | Verordnung zum Gesetz über die Verwaltungsgebühren (SG 153.810) | 1 | one version (the oldest available), 30 April 2006 |
| `154-112/` | Personalreglement der Gerichte (SG 154.112) | 5 | as enacted, then each consolidated version: 12 October 2017 to 18 September 2025 |
| `154-118-archivierungsreglement/` | Reglement zur Aufbewahrung und Archivierung von Unterlagen der Gerichte Basel-Stadt (SG 154.118) | 1 | as enacted, 12 August 2021 |
| `154-120/` | Reglement über das Dolmetscherwesen an den Gerichten (SG 154.120) | 4 | as enacted, then each consolidated version: 12 January 2017 to 19 April 2021 |
| `154-123/` | Reglement über das von den Präsidentinnen und Präsidenten, nebenamtlichen Richterinnen und Richtern, Gerichtsschreiberinnen und Gerichtsschreibern sowie den Mitarbeitenden der Gerichte abzulegende Handgelübde (SG 154.123) | 1 | as enacted, 1 July 2016 |
| `154-125-finanzreglement/` | Reglement über das Finanz- und Rechnungswesen, das Inkasso- und das Nachzahlungsverfahren der Gerichte (SG 154.125) | 2 | as enacted, then each consolidated version: 28 February 2019 to 26 April 2022 |
| `154-128-informatikreglement/` | Reglement über das Informatikmanagement an den Gerichten (SG 154.128) | 1 | as enacted, 21 January 2021 |
| `154-130/` | Verordnung betreffend das Arbeitsgericht (SG 154.130) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2016 |
| `154-150/` | Organisationsreglement des Appellationsgerichts (SG 154.150) | 3 | as enacted, then each consolidated version: 14 March 2017 to 27 September 2021 |
| `154-160/` | Organisationsreglement des Gerichts für fürsorgerische Unterbringungen (SG 154.160) | 1 | as enacted, 13 September 2018 |
| `154-170/` | Organisationsreglement des Zivilgerichts (SG 154.170) | 1 | as enacted, 16 June 2017 |
| `154-180/` | Organisationsreglement des Strafgerichts (SG 154.180) | 5 | as enacted, then each consolidated version: 5 June 2017 to 6 July 2026 |
| `154-190/` | Organisationsreglement des Jugendgerichts (SG 154.190) | 1 | as enacted, 13 September 2018 |
| `154-250/` | Reglement des Sozialversicherungsgerichts und des Schiedsgerichts in Sozialversicherungssachen (SG 154.250) | 2 | as enacted, then each consolidated version: 31 July 2016 to 3 June 2024 |
| `154-300/` | Entschädigungsreglement der Gerichte Basel-Stadt (SG 154.300) | 2 | oldest version available, then each consolidated version: 1 July 2013 to 1 September 2019 |
| `154-810-gerichtsgebuhrenreglement-ggr/` | Reglement über die Gerichtsgebühren (SG 154.810) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 3 June 2021 |
| `154-980/` | Verordnung betreffend die Verfahrenskosten für die Strafverfolgungsbehörden (SG 154.980) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 July 2016 |
| `160-100-human-resources-management-verordnung/` | Verordnung über die Personaldienste des Kantons Basel-Stadt (SG 160.100) | 1 | one version (the oldest available), 1 May 2008 |
| `162-110-vpg/` | Verordnung zum Personalgesetz (SG 162.110) | 5 | oldest version available, then each consolidated version: 29 November 2009 to 1 January 2025 |
| `162-130/` | Verordnung betreffend den Wohnsitz von Beamten und Angestellten (SG 162.130) | 1 | as enacted, 4 February 1969 |
| `162-200-arbeitszeitverordnung-azv/` | Verordnung zur Arbeitszeit der Mitarbeiterinnen und Mitarbeiter des Kantons Basel-Stadt (SG 162.200) | 6 | oldest version available, then each consolidated version: 1 January 2012 to 1 September 2026 |
| `162-320-verordnung-betreffend-vorzeitige-pensionierung-vvp/` | Verordnung betreffend vorzeitige Pensionierung von Mitarbeiterinnen und Mitarbeitern des Kantons Basel-Stadt (SG 162.320) | 3 | as enacted, then each consolidated version: 1 May 2006 to 1 January 2021 |
| `162-410-ferien-und-urlaubsverordnung-fuv/` | Verordnung betreffend Ferien und Urlaub der Mitarbeiterinnen und Mitarbeiter des Kantons Basel-Stadt (SG 162.410) | 8 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `162-420-smuv/` | Verordnung über den Schwangerschafts- und Mutterschaftsurlaub (SG 162.420) | 4 | oldest version available, then each consolidated version: 10 July 2011 to 1 January 2025 |
| `162-500/` | Verordnung über den Schutz vor sexueller Belästigung am Arbeitsplatz (SG 162.500) | 1 | one version (the oldest available), 1 July 2000 |
| `162-600-whistleblowing-verordnung/` | Verordnung betreffend Meldung von Missständen (SG 162.600) | 2 | as enacted, then each consolidated version: 1 October 2013 to 13 September 2015 |
| `162-880/` | Verordnung über dienstrechtliche Bestimmungen zur Einführung des Bundesgesetzes über die verdeckte Ermittlung (SG 162.880) | 1 | as enacted, 1 January 2005 |
| `162-890/` | Personalverordnung für die Mitarbeiterinnen und Mitarbeiter der Justizvollzugsanstalt Bostadel (SG 162.890) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 June 2021 |
| `163-200/` | Verordnung betreffend Dienstwohnungen (SG 163.200) | 1 | one version (the oldest available), 1 January 2009 |
| `163-400/` | Verordnung betreffend Verpflegung von Mitarbeiterinnen und Mitarbeitern des Kantons Basel-Stadt (SG 163.400) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `163-900-parkplatz-reglement/` | Reglement betreffend Parkieren von Motorfahrzeugen der Mitarbeiterinnen und Mitarbeiter auf Staatsarealen (SG 163.900) | 2 | oldest version available, then each consolidated version: 1 July 2007 to 1 February 2016 |
| `164-150-einreihungsverordnung-evo/` | Verordnung über die Einreihung von Stellen sowie die Einstufung von Mitarbeitenden des Kantons Basel-Stadt (SG 164.150) | 4 | oldest version available, then each consolidated version: 12 August 2012 to 1 January 2025 |
| `164-160/` | Verordnung über die Beschleunigung und die Verzögerung des Stufenaufstiegs gemäss § 10 des Lohngesetzes (SG 164.160) | 1 | as enacted, 20 September 2009 |
| `164-170-ad-personam-verordnung/` | Verordnung betreffend ad personam-Einreihung und ad personam-Einstufung (SG 164.170) | 1 | as enacted, 20 September 2009 |
| `164-180-bkv/` | Verordnung betreffend Wahl und Organisation der Begutachtungskommission (SG 164.180) | 2 | oldest version available, then each consolidated version: 1 July 2009 to 1 July 2021 |
| `164-200-anerkennungspramien-verordnung/` | Verordnung über die Ausrichtung von Anerkennungsprämien an die Mitarbeiterinnen und Mitarbeiter des Kantons Basel-Stadt (SG 164.200) | 2 | oldest version available, then each consolidated version: 1 July 2007 to 1 January 2017 |
| `164-250-dienstaltersgeschenkverordnung-dagv/` | Verordnung über das Dienstaltersgeschenk gemäss § 23 Lohngesetz (SG 164.250) | 1 | as enacted, 1 January 2017 |
| `164-340/` | Verordnung über die Ausrichtung von Unterhaltszulagen an die Mitarbeiterinnen und Mitarbeiter des Kantons Basel-Stadt (SG 164.340) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `164-360/` | Verordnung betreffend Anwendbarkeit des Lohngesetzes auf nicht definitiv Beschäftigte oder nur nebenamtlich im Staatsdienst tätige Mitarbeiterinnen und Mitarbeiter (SG 164.360) | 1 | as enacted, 23 July 1995 |
| `164-410-zulagenverordnung/` | Verordnung betreffend Zulagen gemäss § 15a Lohngesetz (SG 164.410) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2024 |
| `164-420-spesenverordnung/` | Verordnung über die Ausrichtung von Spesen und Entschädigungen an die Mitarbeitenden des Kantons Basel-Stadt (SG 164.420) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 26 June 2025 |
| `164-430-lnv/` | Verordnung betreffend Lohnnebenleistungen (SG 164.430) | 1 | as enacted, 26 June 2025 |
| `164-440-stellvertretungsverordnung/` | Verordnung betreffend Entschädigung der Stellvertretung bei Abwesenheit von Mitarbeitern und Mitarbeiterinnen des Kantons Basel-Stadt (SG 164.440) | 1 | one version (the oldest available), 1 March 1998 |
| `164-520/` | Verordnung betreffend Festlegung der Löhne von Lehrpersonen als Aushilfen sowie für Stellvertretungen (SG 164.520) | 2 | oldest version available, then each consolidated version: 1 August 2003 to 1 August 2015 |
| `164-540/` | Verordnung betreffend Mischpensen (SG 164.540) | 1 | one version (the oldest available), 9 August 2010 |
| `164-560/` | Verordnung betreffend die Entschädigung für Lehraufträge am Kantonalen Lehrerseminar (SG 164.560) | 1 | one version (the oldest available), 1 January 1974 |
| `164-680/` | Verordnung betreffend die Entschädigung für Lehraufträge am Institut für Spezielle Pädagogik und Psychologie (ISP) (SG 164.680) | 1 | as enacted, 12 December 1972 |
| `164-700/` | Verordnung betreffend die Entschädigung für Lehraufträge am Turnlehrerkurs der Universität Basel (SG 164.700) | 1 | as enacted, 16 January 1973 |
| `164-720/` | Verordnung betreffend die Entschädigung für die Trainingsleiter am Hochschulsport der Universität Basel (SG 164.720) | 1 | as enacted, 16 January 1973 |
| `166-500/` | Verordnung über die Zusammensetzung und die Wahl der Mitglieder der Vorsorgekommission des Kantons (Bereich Staat) (SG 166.500) | 1 | as enacted, 5 October 2014 |
| `169-200/` | Verordnung über die Sozialpartnerschaftliche Zusammenarbeit in der Kantonalen Verwaltung Basel-Stadt (SG 169.200) | 1 | as enacted, 1 July 2009 |
| `169-300-personalausschussverordnung/` | Verordnung betreffend Personalausschüsse in den Departementen und Betrieben des Kantons Basel-Stadt (SG 169.300) | 1 | as enacted, 9 August 2009 |
| `169-600/` | Verordnung betreffend das Ideen-Management in der öffentlichen Verwaltung Basel-Stadt (SG 169.600) | 1 | as enacted, 1 June 2005 |
| `170-110/` | Verordnung über die Gemeindeaufsicht (SG 170.110) | 1 | as enacted, 1 January 2009 |
| `170-610-filav/` | Verordnung zum Finanz- und Lastenausgleichgesetz (SG 170.610) | 1 | as enacted, 1 January 2008 |
| `190-110/` | Verordnung zum Kirchengesetz (SG 190.110) | 2 | as enacted, then each consolidated version: 5 February 1995 to 24 March 2022 |
| `211-110/` | Verordnung zum Einführungsgesetz zum Schweizerischen Zivilgesetzbuch (SG 211.110) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 May 2025 |
| `212-100/` | Kantonale Zivilstandsverordnung (SG 212.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 8 September 2022 |
| `212-191/` | Verordnung über die elektronische Überwachung zum Schutz gewaltbetroffener Personen (SG 212.191) | 1 | as enacted, 1 January 2022 |
| `212-200-alimentenbevorschussungsverordnung-abvv/` | Verordnung über das Inkasso und die Bevorschussung von Unterhaltsbeiträgen (SG 212.200) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `212-250-kinder-und-jugendheimverordnung-kjhvo/` | Verordnung über die Aufnahme, Betreuung und Förderung von Kindern und Jugendlichen in Heimen (SG 212.250) | 6 | oldest version available, then each consolidated version: 25 March 2012 to 24 March 2022 |
| `212-260-pflegefamilienverordnung-pfvo/` | Verordnung über die Aufnahme, Betreuung und Förderung von Kindern und Jugendlichen in Familienpflege (SG 212.260) | 1 | as enacted, 1 January 2017 |
| `212-410-vokesg/` | Verordnung zum kantonalen Kindes- und Erwachsenenschutzgesetz (SG 212.410) | 5 | as enacted, then each consolidated version: 1 January 2013 to 1 September 2019 |
| `212-470-kinderbetreuungsbeitragsverordnung-kbbv/` | Verordnung über die Beiträge der Kinder, Jugendlichen und Eltern an die Kosten der Unterbringung von Kindern und Jugendlichen in Heimen und in Pflegefamilien (SG 212.470) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2017 |
| `212-500/` | Verordnung über die Ausbildung der mit Kindesanhörungen und Kindesvertretung beauftragten Personen (SG 212.500) | 1 | one version (the oldest available), 1 January 2013 |
| `212-600/` | Verordnung betreffend Einführung des Bundesgesetzes über Voraussetzungen und Verfahren bei Sterilisationen (SG 212.600) | 1 | one version (the oldest available), 1 January 2013 |
| `212-800/` | Verordnung zur Einführung des Bundesgesetzes zum Haager Adoptionsübereinkommen (SG 212.800) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `212-860-vo-hakes/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über internationale Kindesentführung und die Haager Übereinkommen zum Schutz von Kindern und Erwachsenen (SG 212.860) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2018 |
| `214-200-fundsachenverordnung/` | Verordnung über die Behandlung von Fundsachen (SG 214.200) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 30 October 2016 |
| `214-305-kgeoiv/` | Geoinformationsverordnung (SG 214.305) | 6 | as enacted, then each consolidated version: 1 September 2012 to 12 February 2026 |
| `214-307-korebkv/` | Kantonale Verordnung über den Kataster der öffentlich-rechtlichen Eigentumsbeschränkungen (SG 214.307) | 2 | as enacted, then each consolidated version: 1 January 2019 to 12 February 2026 |
| `214-310-vogb/` | Verordnung über das Grundbuch (SG 214.310) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 28 May 2022 |
| `214-320-voav/` | Verordnung über die amtliche Vermessung (SG 214.320) | 8 | oldest version available, then each consolidated version: 1 January 2009 to 1 February 2024 |
| `214-600/` | Kantonale Verordnung betreffend die Bewilligungspflicht für den Erwerb von Grundstücken durch Personen im Ausland (SG 214.600) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2016 |
| `214-710/` | Verordnung betreffend Einführung des Bundesgesetzes über das bäuerliche Bodenrecht (SG 214.710) | 1 | one version (the oldest available), 1 January 2009 |
| `215-210/` | Verordnung zum Bundesgesetz über den Konsumkredit und zur Bundesverordnung zum Konsumkreditgesetz (SG 215.210) | 1 | one version (the oldest available), 1 January 2009 |
| `215-450/` | Verordnung über die Räumung von Wohnräumen im Rahmen des Exmissionsverfahrens (SG 215.450) | 2 | as enacted, then each consolidated version: 1 January 2012 to 1 July 2016 |
| `215-500/` | Verordnung zum Bundesgesetz über die landwirtschaftliche Pacht (SG 215.500) | 1 | one version (the oldest available), 3 December 2009 |
| `257-110/` | Verordnung über die Durchführung des polizeilichen Ermittlungsverfahrens bei Vergehen und Übertretungen (SG 257.110) | 9 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `257-113/` | Verordnung über die Zuständigkeiten zur Erhebung von bundesrechtlichen Ordnungsbussen (SG 257.113) | 1 | as enacted, 1 January 2020 |
| `257-115-kantonale-ordnungsbussenverordnung-kobv/` | Verordnung über das kantonale Ordnungsbussenverfahren (SG 257.115) | 6 | oldest version available, then each consolidated version: 1 July 2012 to 1 March 2026 |
| `257-118-bettelverordnung/` | Verordnung betreffend Betteln an neuralgischen und besonders sensiblen Örtlichkeiten (SG 257.118) | 1 | as enacted, 21 November 2024 |
| `257-120/` | Verordnung über die Zusammensetzung, Organisation und Befugnisse der Staatsanwaltschaft (SG 257.120) | 4 | as enacted, then each consolidated version: 27 November 2011 to 29 August 2024 |
| `257-135/` | Verordnung über dauernd bestellte und amtliche Sachverständige im Strafverfahren (SG 257.135) | 1 | as enacted, 1 January 2011 |
| `257-140/` | Verordnung über das Informatiksystem der Staatsanwaltschaft (SG 257.140) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 May 2023 |
| `257-815-viclas-verordnung/` | Verordnung betreffend die Einführung der Interkantonalen Vereinbarung über die computergestützte Zusammenarbeit der Kantone bei der Aufklärung von Gewaltdelikten (SG 257.815) | 1 | as enacted, 1 January 2011 |
| `258-210-justizvollzugsverordnung-jvv/` | Verordnung über den Justizvollzug (SG 258.210) | 5 | as enacted, then each consolidated version: 16 February 2014 to 23 April 2026 |
| `258-450/` | Verordnung über die finanzielle Beteiligung von verurteilten Personen und Eltern an jugendstrafrechtlichen Sanktionen (SG 258.450) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2017 |
| `291-400-honorarreglement-hor/` | Reglement über das Honorar und die Entschädigung der berufsmässigen Vertretung im Gerichtsverfahren (SG 291.400) | 3 | as enacted, then each consolidated version: 1 January 2011 to 23 May 2024 |
| `291-900/` | Reglement über das Anwaltsexamen (SG 291.900) | 2 | oldest version available, then each consolidated version: 2 October 2008 to 16 November 2020 |
| `292-110-notariatsverordnung-notv/` | Verordnung zum Notariatsgesetz des Kantons Basel-Stadt (SG 292.110) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2026 |
| `292-400/` | Verordnung über den Notariatstarif (SG 292.400) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2016 |
| `300-150-vvtabpg/` | Vollziehungsverordnung zum Bundesgesetz über Tabakprodukte und elektronische Zigaretten (SG 300.150) | 1 | as enacted, 5 June 2025 |
| `310-120-bewilligungsverordnung/` | Verordnung über die Fachpersonen und Betriebe im Gesundheitswesen (SG 310.120) | 11 | as enacted, then each consolidated version: 1 January 2012 to 22 August 2024 |
| `310-125-pflegeausbildungsforderverordnung-pafv/` | Kantonale Verordnung über die Förderung der Ausbildung im Bereich der Pflege (SG 310.125) | 1 | as enacted, 1 August 2024 |
| `310-170/` | Verordnung über die Gebühren im Gesundheitswesen (SG 310.170) | 4 | as enacted, then each consolidated version: 27 October 2013 to 1 March 2025 |
| `310-420-vzh/` | Verordnung über die Zulassung und Höchstzahlen von ambulanten Leistungserbringern (SG 310.420) | 1 | as enacted, 1 July 2025 |
| `310-800/` | Verordnung betreffend Ausrichtung von Inkonvenienzentschädigungen für Geburtshilfe und Wochenbettbetreuung (SG 310.800) | 4 | as enacted, then each consolidated version: 1 January 2012 to 1 July 2021 |
| `321-200-vvepg/` | Vollziehungsverordnung zur eidgenössischen Epidemiengesetzgebung (SG 321.200) | 1 | as enacted, 31 January 2019 |
| `328-210-zahnpflegeverordnung/` | Verordnung betreffend die soziale Zahnpflege (SG 328.210) | 1 | as enacted, 1 January 2012 |
| `329-110-pflegebeitragsverordnung/` | Verordnung betreffend Beiträge an die unentgeltliche Pflege und Betreuung von dauernd pflegebedürftigen Personen zu Hause (SG 329.110) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 September 2018 |
| `339-220-gebuhrenverordnung-sanitat/` | Verordnung über die von der Sanität Basel zu erhebenden Gebühren (SG 339.220) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2018 |
| `340-100/` | Heilmittelverordnung (SG 340.100) | 6 | oldest version available, then each consolidated version: 27 October 2013 to 30 April 2026 |
| `340-500-betaubungsmittelverordnung/` | Kantonale Verordnung betreffend Betäubungsmittel (SG 340.500) | 2 | as enacted, then each consolidated version: 16 September 2004 to 1 July 2016 |
| `340-800-chemikalienverordnung/` | Verordnung über Chemikalien (SG 340.800) | 4 | as enacted, then each consolidated version: 24 December 2006 to 13 December 2018 |
| `351-100/` | Vollziehungsverordnung zum Bundesgesetz über Lebensmittel und Gebrauchsgegenstände (SG 351.100) | 2 | as enacted, then each consolidated version: 13 July 2008 to 25 October 2018 |
| `351-310/` | Verordnung betreffend Gebühren des Kantonalen Laboratoriums im administrativen Bereich (SG 351.310) | 2 | oldest version available, then each consolidated version: 24 December 2006 to 13 December 2018 |
| `361-200-gebuhrenverordnung-veterinaramt/` | Verordnung betreffend die Gebühren und Vergütungen des Kantonalen Veterinäramtes (SG 361.200) | 4 | as enacted, then each consolidated version: 12 August 2007 to 1 January 2025 |
| `361-300/` | Verordnung über die Bekämpfung von Tierseuchen (SG 361.300) | 1 | as enacted, 30 December 2011 |
| `365-110-hundeverordnung/` | Verordnung betreffend das Halten von Hunden (SG 365.110) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 April 2025 |
| `365-500-tierschutzverordnung/` | Verordnung über den Tierschutz (SG 365.500) | 3 | as enacted, then each consolidated version: 12 February 2012 to 1 April 2024 |
| `365-540/` | Reglement betreffend das Halten gefährlicher Tiere (SG 365.540) | 1 | as enacted, 12 December 1993 |
| `369-200/` | Reglement für den Betrieb einer Tierkörpersammelstelle (TKS) (SG 369.200) | 1 | as enacted, 17 May 2012 |
| `390-110-bestv/` | Bestattungsverordnung (SG 390.110) | 5 | oldest version available, then each consolidated version: 29 January 2012 to 1 April 2021 |
| `390-115-bestattungsreglement-bestr/` | Reglement über das Bestattungs- und Friedhofwesen (SG 390.115) | 1 | as enacted, 17 April 2023 |
| `390-170-grabmv/` | Grabmalverordnung (SG 390.170) | 1 | as enacted, 1 April 2021 |
| `390-500/` | Verordnung über Gebühren im Bestattungswesen (SG 390.500) | 5 | oldest version available, then each consolidated version: 29 January 2012 to 1 April 2021 |
| `410-120-schulerinnen-und-schulerverordnung/` | Verordnung über die Rechte und Pflichten der Schülerinnen und Schüler (SG 410.120) | 1 | as enacted, 18 August 2014 |
| `410-130-absenzen-und-disziplinarverordnung/` | Verordnung über den Schulbesuch, die Absenzen, Dispensationen und Disziplinarmassnahmen (SG 410.130) | 4 | as enacted, then each consolidated version: 18 August 2014 to 12 August 2024 |
| `410-140-verordnung-kooperation-erziehungsberechtigte/` | Verordnung über die Kooperation zwischen der Schule und den Erziehungsberechtigten (SG 410.140) | 1 | as enacted, 18 August 2014 |
| `410-150-ubergangsverordnung-schulharmonisierung/` | Übergangsverordnung betreffend den Übergang von der bisherigen Schullaufbahn zur neuen harmonisierten Schullaufbahn (SG 410.150) | 4 | as enacted, then each consolidated version: 5 February 2012 to 1 January 2018 |
| `410-600/` | Verordnung betreffend Verwaltung und Verwendung des Schulfonds der Primarschule Kleinbasel (SG 410.600) | 1 | one version (the oldest available), 15 August 2011 |
| `410-700-schullaufbahnverordnung-slv/` | Verordnung über die Beurteilung und die Schullaufbahnentscheide der Schülerinnen und Schüler der Volksschule und der weiterführenden Schulen (SG 410.700) | 16 | as enacted, then each consolidated version: 12 August 2013 to 31 July 2026 |
| `410-910-verordnung-auswartige-schulanlasse/` | Verordnung über die auswärtigen Schulanlässe der Schulen des Kantons Basel-Stadt (SG 410.910) | 2 | as enacted, then each consolidated version: 18 August 2014 to 10 August 2026 |
| `411-100/` | Verordnung über die Staatliche Schulsynode des Kantons Basel-Stadt (SG 411.100) | 1 | one version (the oldest available), 20 May 2010 |
| `411-150/` | Verordnung betreffend die Tätigkeit der Schulräte der Volksschulen (SG 411.150) | 3 | oldest version available, then each consolidated version: 12 August 2013 to 12 August 2024 |
| `411-200/` | Verordnung über die Schulkommissionen der weiterführenden Schulen (SG 411.200) | 2 | oldest version available, then each consolidated version: 1 July 2001 to 14 August 2017 |
| `411-300/` | Verordnung über die Volksschulleitung (SG 411.300) | 4 | as enacted, then each consolidated version: 13 August 2012 to 11 August 2025 |
| `411-350/` | Verordnung für die Schulleitungen der Volksschulen (SG 411.350) | 5 | as enacted, then each consolidated version: 13 August 2012 to 26 December 2019 |
| `411-360/` | Verordnung für die Schulleitungen der weiterführenden Schulen (SG 411.360) | 4 | as enacted, then each consolidated version: 13 August 2012 to 23 November 2017 |
| `411-500/` | Verordnung betreffend die Pflichtlektionenzahl und die Lektionenzuteilung der Lehrpersonen an den vom Kanton geführten Schulen (SG 411.500) | 3 | oldest version available, then each consolidated version: 1 August 2013 to 1 January 2016 |
| `411-520-ubertrittsverordnung/` | Verordnung betreffend den Übertritt von Lehrkräften an die Orientierungsschule und an die Weiterbildungsschule (SG 411.520) | 1 | one version (the oldest available), 1 July 2000 |
| `411-600/` | Verordnung betreffend Ferien und Urlaub, die ausserordentliche Entlastung und die Stellvertretung von Lehrpersonen an den vom Kanton geführten Schulen (SG 411.600) | 1 | one version (the oldest available), 10 August 2009 |
| `412-400-fdv/` | Verordnung über die frühe Deutschförderung (SG 412.400) | 3 | as enacted, then each consolidated version: 5 May 2016 to 1 March 2024 |
| `412-600-tfv/` | Verordnung über die Tagesstrukturen und die Ferienangebote (SG 412.600) | 4 | as enacted, then each consolidated version: 1 August 2011 to 12 August 2024 |
| `412-750-sonderpadagogikverordnung-spv/` | Verordnung über die Schulung und Förderung von Schülerinnen und Schülern mit besonderem Bildungsbedarf (SG 412.750) | 8 | oldest version available, then each consolidated version: 23 June 2013 to 10 August 2026 |
| `413-630-abschlussverordnung-fms/` | Verordnung über die Abschlüsse an der Fachmaturitätsschule Basel-Stadt (SG 413.630) | 10 | oldest version available, then each consolidated version: 12 August 2013 to 10 August 2026 |
| `413-820-maturitatsprufungsverordnung-mpv/` | Verordnung betreffend die Maturitätsprüfungen im Kanton Basel-Stadt (SG 413.820) | 6 | oldest version available, then each consolidated version: 12 August 2013 to 16 August 2027 |
| `413-825/` | Reglement für die Maturaarbeit an den Gymnasien im Kanton Basel-Stadt (SG 413.825) | 3 | oldest version available, then each consolidated version: 15 August 2011 to 12 August 2024 |
| `414-200/` | Verordnung über die Abgabe von Lehrmitteln und Verbrauchsmaterialien (SG 414.200) | 1 | one version (the oldest available), 10 August 2009 |
| `414-710-gebuhrenverordnung-pds/` | Verordnung betreffend die Gebühren der Pädagogischen Dokumentationsstelle des Kantons Basel-Stadt (SG 414.710) | 1 | one version (the oldest available), 1 August 2008 |
| `415-150-kinder-und-jugendkommissionsverordnung-kjkv/` | Verordnung über die Aufgaben und die Zusammensetzung der Kinder- und Jugendkommission (SG 415.150) | 1 | as enacted, 8 March 2015 |
| `415-700/` | Verordnung für den Schulpsychologischen Dienst (SG 415.700) | 1 | one version (the oldest available), 1 January 2011 |
| `419-100/` | Schulgeldverordnung (SG 419.100) | 1 | as enacted, 1 January 2010 |
| `419-300-gebuhrenverordnung-berufsbildung/` | Verordnung über Studien-, Kurs- und Verwaltungsgebühren in der kantonalen Berufsbildung (SG 419.300) | 3 | as enacted, then each consolidated version: 1 January 2013 to 1 August 2018 |
| `419-902-raka/` | Reglement des Schweizerischen Roten Kreuzes (SRK) über die Anerkennung kantonaler Ausbildungsabschlüsse (SG 419.902) | 1 | as enacted, 1 July 1999 |
| `419-903/` | Verordnung der SDK über die Anerkennung von ausländischen Ausbildungsabschlüssen (SG 419.903) | 1 | as enacted, 1 January 1998 |
| `419-904/` | Reglement des SRK über die Anerkennung von ausländischen Ausbildungsabschlüssen (SG 419.904) | 1 | as enacted, 1 January 1998 |
| `419-905/` | Reglement der GDK für die interkantonale Prüfung von Osteopathinnen und Osteopathen in der Schweiz (SG 419.905) | 2 | as enacted, then each consolidated version: 1 January 2007 to 14 June 2018 |
| `419-910-mar/` | Verordnung des Bundesrates / Reglement der EDK über die Anerkennung von gymnasialen Maturitätsausweisen (SG 419.910) | 2 | as enacted, then each consolidated version: 1 August 1995 to 1 August 2007 |
| `420-210-berufsbildungsverordnung/` | Verordnung über den Vollzug des Kantonalen Gesetzes über die Berufsbildung (SG 420.210) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 19 March 2020 |
| `421-760-verordnung-ags-lzb/` | Verordnung für den Lehrgang «Link zum Beruf» an der Allgemeinen Gewerbeschule Basel (SG 421.760) | 1 | as enacted, 9 August 2010 |
| `421-770/` | Verordnung betreffend den Ausbildungsgang Gestalter oder Gestalterin an der Schule für Gestaltung (SG 421.770) | 1 | one version (the oldest available), 3 December 2009 |
| `423-200/` | Verordnung über den Lehrgang «Frühe sprachliche Förderung – Schwerpunkt frühe Sprachbildung» (SG 423.200) | 2 | as enacted, then each consolidated version: 10 August 2009 to 10 August 2026 |
| `424-100-berufsmaturitatsverordnung/` | Verordnung über die Berufsmaturität (SG 424.100) | 5 | as enacted, then each consolidated version: 9 August 2010 to 31 July 2026 |
| `424-500-passerelleverordnung/` | Verordnung betreffend den Passerelle-Lehrgang und die Ergänzungsprüfungen für die Zulassung von Inhabenden eines eidgenössischen Berufsmaturitätszeugnisses oder eines gesamtschweizerisch anerkannten Fachmaturitätszeugnisses zu den universitären Hochschulen (SG 424.500) | 4 | oldest version available, then each consolidated version: 12 January 2014 to 12 August 2024 |
| `424-510/` | Kursgeldverordnung für den Passerellen-Lehrgang (SG 424.510) | 1 | as enacted, 15 August 2005 |
| `427-100-bzg/` | Verordnung über das Bildungszentrum Gesundheit Basel-Stadt (SG 427.100) | 4 | oldest version available, then each consolidated version: 12 August 2013 to 4 April 2024 |
| `427-800/` | Reglement über die Ausbildung und Lehrabschlussprüfung für gelernte Matrosen und Matrosinnen der Binnenschifffahrt (SG 427.800) | 1 | as enacted, 1 August 2000 |
| `427-920/` | Verordnung über den Bildungsgang Pflege HF am Bildungszentrum Gesundheit Basel-Stadt (SG 427.920) | 1 | as enacted, 12 August 2013 |
| `427-930/` | Verordnung über den Bildungsgang zur diplomierten Fachfrau für medizinisch technische Radiologie HF / zum diplomierten Fachmann für medizinisch technische Radiologie HF (SG 427.930) | 1 | as enacted, 1 September 2008 |
| `427-940/` | Verordnung über den Bildungsgang zur diplomierten Biomedizinischen Analytikerin HF / zum diplomierten Biomedizinischen Analytiker HF (SG 427.940) | 1 | as enacted, 1 September 2008 |
| `427-950/` | Verordnung über den Bildungsgang Kindererziehung HF zur diplomierten Kindererzieherin HF / zum diplomierten Kindererzieher HF (SG 427.950) | 1 | as enacted, 18 August 2014 |
| `439-140-prufungsentschadigungsverordnung/` | Verordnung betreffend die Entschädigungen für die Mitwirkung an Aufnahme- und Abschlussprüfungen (SG 439.140) | 3 | as enacted, then each consolidated version: 24 February 2008 to 13 July 2017 |
| `440-450/` | Verordnung betreffend die Unveräusserlichkeit des Universitätsgutes (SG 440.450) | 3 | as enacted, then each consolidated version: 1 January 2001 to 24 May 2015 |
| `451-110-museumsverordnung/` | Verordnung zum Gesetz über die Museen des Kantons Basel-Stadt (SG 451.110) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 February 2025 |
| `451-500/` | Verordnung betreffend das Museum Kleines Klingental (SG 451.500) | 1 | as enacted, 1 September 2013 |
| `452-300/` | Verordnung betreffend die Erhebung von Gebühren durch das Staatsarchiv (SG 452.300) | 1 | as enacted, 28 November 2004 |
| `453-100-vgwr-bs/` | Verordnung über das kantonale Gebäude- und Wohnungsregister und das kantonale Gebäudemodell (SG 453.100) | 3 | as enacted, then each consolidated version: 1 January 2009 to 2 September 2021 |
| `453-210-statistikverordnung/` | Verordnung über die öffentliche Statistik (SG 453.210) | 3 | as enacted, then each consolidated version: 1 July 2015 to 2 September 2021 |
| `453-500-gebuhrenverordnung/` | Verordnung über die Erhebung von Gebühren der zentralen Statistikstelle (SG 453.500) | 1 | as enacted, 1 July 2015 |
| `460-200/` | Verordnung über die Maturitätskurse für Berufstätige (SG 460.200) | 2 | oldest version available, then each consolidated version: 1 August 2011 to 16 August 2027 |
| `460-210/` | Verordnung über die Gebühren im Bereich der Maturitätskurse für Berufstätige (SG 460.210) | 1 | as enacted, 9 August 2010 |
| `460-220/` | Verordnung über die Abschlussprüfungen der Maturitätskurse für Berufstätige (SG 460.220) | 3 | as enacted, then each consolidated version: 1 January 2008 to 16 August 2027 |
| `491-110-vvausbbg/` | Vollziehungsverordnung zum Gesetz betreffend Ausbildungsbeiträge (SG 491.110) | 2 | as enacted, then each consolidated version: 26 February 2012 to 1 June 2022 |
| `491-400/` | Verordnung für die Verwaltung und Verwendung des Stipendienfonds der Basler Schulen (SG 491.400) | 2 | as enacted, then each consolidated version: 29 March 2009 to 16 February 2023 |
| `491-800/` | Reglement über die Verwendung des Kredites zur Ausbildung und Betreuung von Studentinnen und Studenten sowie anderen Nachwuchskräften aus Entwicklungsländern (SG 491.800) | 2 | as enacted, then each consolidated version: 1 January 1962 to 30 September 2021 |
| `494-330-verordnung-kulturvermittlung/` | Verordnung zur Förderung der Kulturvermittlung im Kanton Basel-Stadt (SG 494.330) | 1 | as enacted, 1 January 2021 |
| `494-340/` | Verordnung über die Programm- und Strukturförderung Orchester (SG 494.340) | 1 | as enacted, 1 September 2022 |
| `494-350/` | Verordnung für die Verleihung des Kulturpreises des Kantons Basel-Stadt (SG 494.350) | 3 | as enacted, then each consolidated version: 1 July 2010 to 19 April 2018 |
| `494-700/` | Verordnung über die Verwendung der Jugendkulturpauschale (SG 494.700) | 1 | as enacted, 1 January 2016 |
| `494-800/` | Verordnung über die Verwendung des Kunstkredits (SG 494.800) | 2 | oldest version available, then each consolidated version: 3 December 2009 to 1 January 2014 |
| `497-110-denkmalpflegeverordnung-dpv/` | Verordnung betreffend die Denkmalpflege (SG 497.110) | 4 | oldest version available, then each consolidated version: 20 June 2010 to 1 July 2020 |
| `497-120-av/` | Archäologieverordnung (SG 497.120) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `510-110-polizeiverordnung-polv/` | Verordnung betreffend die Kantonspolizei des Kantons Basel-Stadt (SG 510.110) | 10 | oldest version available, then each consolidated version: 22 May 2011 to 19 June 2025 |
| `510-150-vsms-bs/` | Kantonale Verordnung über Massnahmen zur Unterstützung der Sicherheit von Minderheiten mit besonderen Schutzbedürfnissen (SG 510.150) | 1 | as enacted, 1 September 2025 |
| `510-170-kogesv/` | Verordnung betreffend die Kommission für Gewaltschutz (SG 510.170) | 1 | as enacted, 19 June 2025 |
| `510-430/` | Pilotversuchsverordnung über die Qualitätssicherung des kantonalen Bedrohungsmanagements (SG 510.430) | 2 | as enacted, then each consolidated version: 1 September 2023 to 1 January 2026 |
| `519-400-gvo/` | Verordnung über die Beglaubigungsgebühren sowie die Gebühren auf dem Gebiet der Einwohnerkontrolle und des Ausländerrechts (SG 519.400) | 4 | oldest version available, then each consolidated version: 4 November 2012 to 1 July 2024 |
| `519-800/` | Verordnung über die Gebühren des Instituts für Rechtsmedizin (SG 519.800) | 2 | as enacted, then each consolidated version: 22 October 2006 to 25 January 2015 |
| `561-105-vo-eg-bgs/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Geldspiele (SG 561.105) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 April 2022 |
| `561-120-swisslos-fonds-verordnung/` | Verordnung über die Verwendung von Geldern aus dem Swisslos-Fonds (SG 561.120) | 5 | oldest version available, then each consolidated version: 21 October 2012 to 22 January 2026 |
| `561-121-swisslos-sportfonds-verordnung/` | Verordnung über die Swisslos-Sportfonds-Kommission und die Verwendung der Mittel aus dem Swisslos-Sportfonds (SG 561.121) | 2 | as enacted, then each consolidated version: 11 November 2012 to 1 January 2021 |
| `562-320/` | Verordnung betreffend Messen und Märkte in der Stadt Basel (SG 562.320) | 5 | oldest version available, then each consolidated version: 1 January 2014 to 5 October 2023 |
| `562-350/` | Gebührenverordnung betreffend Messen und Märkte in der Stadt Basel (SG 562.350) | 2 | as enacted, then each consolidated version: 29 March 2015 to 5 October 2023 |
| `562-360/` | Reglement über die Stammbeschickung an der Basler Herbstmesse und am Weihnachtsmarkt (SG 562.360) | 1 | as enacted, 29 April 2010 |
| `562-400/` | Verordnung über die Einführung des Bundesgesetzes über das Gewerbe der Reisenden (SG 562.400) | 1 | as enacted, 16 January 2011 |
| `562-530-trodel-und-pfandleihverordnung-tpv/` | Verordnung zum Trödel- und Pfandleihgewerbe (SG 562.530) | 2 | as enacted, then each consolidated version: 1 July 2011 to 1 July 2020 |
| `563-110/` | Verordnung zum Gastgewerbegesetz (SG 563.110) | 2 | oldest version available, then each consolidated version: 29 January 2012 to 6 February 2020 |
| `563-130/` | Verordnung zum Bundesgesetz über die gebrannten Wasser (SG 563.130) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 19 January 2023 |
| `563-150/` | Reglement über den Fähigkeitsausweis und über die Durchführung der Wirtefachprüfung (Prüfungsreglement) (SG 563.150) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 27 February 2020 |
| `563-170-gebvggg/` | Gebührenverordnung zum Gastgewerbegesetz (SG 563.170) | 2 | oldest version available, then each consolidated version: 29 January 2012 to 1 January 2025 |
| `563-210-taxiverordnung/` | Verordnung zum Taxigesetz (SG 563.210) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 May 2017 |
| `563-250-taxiprufungsreglement/` | Prüfungsreglement zum Taxigesetz (SG 563.250) | 2 | oldest version available, then each consolidated version: 23 January 2011 to 1 May 2017 |
| `563-280-taxitarifverordnung/` | Tarifverordnung zum Taxigesetz (SG 563.280) | 3 | oldest version available, then each consolidated version: 1 March 2009 to 13 July 2023 |
| `563-500-personenbeforderungsverordnung-pbv/` | Verordnung über die Bewilligung für die regelmässige und gewerbsmässige Personenbeförderung (SG 563.500) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 25 May 2014 |
| `568-200-waffenverordnung/` | Verordnung über den Vollzug der eidgenössischen Waffengesetzgebung (SG 568.200) | 1 | as enacted, 1 January 1999 |
| `568-400-kantonale-sprengstoffverordnung/` | Verordnung über explosionsgefährliche Stoffe (SG 568.400) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2020 |
| `569-110/` | Verordnung zum Gesetz betreffend öffentliche Filmvorführungen und Abgabe von elektronischen Trägermedien (SG 569.110) | 1 | as enacted, 1 January 2013 |
| `569-500/` | Plakatverordnung (SG 569.500) | 3 | oldest version available, then each consolidated version: 6 February 2011 to 15 June 2025 |
| `571-300/` | Verordnung über die Disziplinarstrafgewalt in der Militärverwaltung (SG 571.300) | 2 | as enacted, then each consolidated version: 1 January 2009 to 6 February 2025 |
| `575-100/` | Verordnung über die Wehrpflichtersatzabgabe (SG 575.100) | 2 | as enacted, then each consolidated version: 1 January 2004 to 1 July 2016 |
| `576-150-vzs/` | Verordnung über den Zivilschutz (SG 576.150) | 2 | as enacted, then each consolidated version: 1 September 2023 to 1 January 2026 |
| `576-170-gebvzk/` | Gebührenverordnung für den Zivil- und Kulturgüterschutz (SG 576.170) | 1 | as enacted, 1 September 2023 |
| `576-180-kgv/` | Verordnung über den Kulturgüterschutz (SG 576.180) | 1 | as enacted, 1 September 2023 |
| `590-110-feuerwehrverordnung-fwv/` | Verordnung zum Gesetz betreffend die Feuerwehr des Kantons Basel-Stadt (SG 590.110) | 3 | as enacted, then each consolidated version: 1 January 2013 to 21 December 2017 |
| `590-200-fwgev/` | Verordnung über die von der Feuerwehr zu erhebenden Gebühren (SG 590.200) | 4 | as enacted, then each consolidated version: 8 September 2013 to 1 September 2026 |
| `610-110-finanzhaushaltverordnung/` | Verordnung zum Gesetz über den kantonalen Finanzhaushalt (SG 610.110) | 10 | oldest version available, then each consolidated version: 1 July 2007 to 1 January 2026 |
| `610-150-inkassoverordnung-inkav/` | Verordnung über das zentrale Forderungsinkasso (SG 610.150) | 1 | as enacted, 1 January 2013 |
| `640-110-steuerverordnung-stv/` | Verordnung zum Gesetz über die direkten Steuern (SG 640.110) | 13 | oldest version available, then each consolidated version: 29 September 2011 to 1 September 2025 |
| `650-410-gasttaxenverordnung/` | Verordnung zum Gesetz betreffend die Erhebung einer Gasttaxe (SG 650.410) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 March 2025 |
| `650-510/` | Verordnung zum Gesetz über die Besteuerung der Motorfahrzeuge (SG 650.510) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `660-100-dbstv/` | Verordnung über den Vollzug der direkten Bundessteuer (SG 660.100) | 2 | oldest version available, then each consolidated version: 1 January 2001 to 1 May 2024 |
| `660-200/` | Verordnung über den Vollzug der Eidgenössischen Verrechnungssteuer im Kanton Basel-Stadt (SG 660.200) | 1 | one version (the oldest available), 24 June 2001 |
| `685-320-dreispitzv/` | Verordnung über Bauten auf dem Dreispitz-Areal (SG 685.320) | 2 | oldest version available, then each consolidated version: 23 September 2012 to 21 December 2017 |
| `685-340/` | Betriebsreglement für die öffentlichen Materiallagerplätze Basel-Dreispitz (Dreispitz-Verwaltung) (SG 685.340) | 1 | one version (the oldest available), 1 January 2009 |
| `685-360/` | Kanalisationsreglement für die Dreispitzverwaltung Basel (SG 685.360) | 1 | one version (the oldest available), 1 January 2009 |
| `695-110/` | Verordnung zum Gebäudeversicherungsgesetz (SG 695.110) | 1 | one version (the oldest available), 1 January 2010 |
| `695-500/` | Beitragsreglement der Gebäudeversicherung (SG 695.500) | 2 | oldest version available, then each consolidated version: 1 January 2002 to 15 June 2023 |
| `695-600/` | Prämienermässigungsreglement der Gebäudeversicherung (SG 695.600) | 1 | one version (the oldest available), 1 January 1991 |
| `717-110/` | Verordnung betreffend den Vollzug des Gesetzes über die Ermittlung von Grundstückwerten vom 20. Juni 1968 und über die zu erhebenden Gebühren (SG 717.110) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 June 2017 |
| `721-700/` | Verordnung betreffend den Vollzug des Bundesgesetzes über die Nationalstrassen vom 8. März 1960 (SG 721.700) | 1 | as enacted, 1 January 2009 |
| `724-110-norv/` | Verordnung zum Gesetz über die Nutzung des öffentlichen Raumes (SG 724.110) | 4 | as enacted, then each consolidated version: 26 February 2017 to 1 January 2021 |
| `724-140-allmendverordnung/` | Verordnung über die Inanspruchnahme der Allmend (SG 724.140) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 26 February 2017 |
| `724-500/` | Verordnung über die Strassenprostitution (SG 724.500) | 2 | as enacted, then each consolidated version: 25 May 2008 to 1 July 2020 |
| `724-910-gebv-norg/` | Gebührenverordnung zum Gesetz über die Nutzung des öffentlichen Raumes (SG 724.910) | 3 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `727-510/` | Verordnung zum Gesetz über Strassenreinigungsbeiträge (SG 727.510) | 1 | as enacted, 1 January 1994 |
| `730-120-baugebuhrenverordnung-baugebv/` | Verordnung über die Gebühren der Baubewilligungsbehörden (SG 730.120) | 3 | oldest version available, then each consolidated version: 14 December 2006 to 2 May 2024 |
| `730-210-kfwv/` | Kantonale Verordnung über Fuss- und Wanderwege (SG 730.210) | 1 | as enacted, 11 July 2019 |
| `730-310-parkplatzverordnung-ppv/` | Verordnung über die Erstellung von Parkplätzen für Personenwagen (SG 730.310) | 3 | oldest version available, then each consolidated version: 20 June 2010 to 1 August 2022 |
| `730-320-veloparkplatzverordnung-veloppv/` | Verordnung über die Erstellung von Abstellplätzen für Velos und Mofas (SG 730.320) | 1 | as enacted, 29 January 2017 |
| `730-700/` | Verordnung über Beiträge an die Kosten der Beseitigung von Sprayereien an privaten Liegenschaften (SG 730.700) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 14 July 2022 |
| `735-200/` | Verordnung über den Brandschutz (SG 735.200) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 26 December 2024 |
| `735-250/` | Reglement betreffend Reinigungsintervalle für Feuerungsanlagen (SG 735.250) | 1 | as enacted, 17 February 2002 |
| `735-400/` | Verordnung über die Gebühren der Feuerpolizei (SG 735.400) | 2 | oldest version available, then each consolidated version: 14 December 2006 to 1 July 2016 |
| `739-500/` | Verordnung betreffend die Ausleihe von Bauakten (SG 739.500) | 1 | one version (the oldest available), 21 May 2006 |
| `740-110/` | Verordnung zum Enteignungsgesetz (SG 740.110) | 1 | one version (the oldest available), 1 January 2009 |
| `740-500/` | Verordnung betreffend die Entschädigung der Expropriationskommission (SG 740.500) | 1 | one version (the oldest available), 1 September 1991 |
| `740-800/` | Verordnung betreffend den Vollzug des eidgenössischen Enteignungsrechts (SG 740.800) | 1 | as enacted, 2 April 1975 |
| `771-310/` | Verordnung zum Gesetz betreffend Einführung des Bundesgesetzes über Nutzbarmachung der Wasserkräfte (SG 771.310) | 1 | one version (the oldest available), 1 October 2010 |
| `771-510-wassernutzungsverordnung/` | Verordnung zum Gesetz über die Nutzung von öffentlichem Fluss- und Grundwasser (SG 771.510) | 1 | one version (the oldest available), 1 January 2009 |
| `771-920/` | Verordnung betreffend die Wässerungsverhältnisse am Riehenteich (SG 771.920) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2020 |
| `772-110-energieverordnung-env/` | Verordnung zum Energiegesetz (SG 772.110) | 7 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `772-140/` | Verordnung zur Lenkungsabgabe und zum Strompreis-Bonus (SG 772.140) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 October 2017 |
| `772-180-veeg/` | Verordnung betreffend Entschädigungen und Beiträge aufgrund der Einstellung der Gasversorgung (SG 772.180) | 1 | as enacted, 1 November 2023 |
| `772-301/` | Verordnung zur Einführung des neuen IWB-Gesetzes (SG 772.301) | 1 | as enacted, 1 January 2010 |
| `772-310/` | Verordnung betreffend Organisation der Energie- und Trinkwasserversorgung (SG 772.310) | 1 | one version (the oldest available), 1 January 2010 |
| `772-350/` | Verordnung betreffend die von den IWB Industrielle Werke Basel zu entrichtende Konzessionsgebühr (SG 772.350) | 3 | as enacted, then each consolidated version: 30 December 2010 to 1 March 2018 |
| `772-580/` | Verordnung betreffend Ausführung des Bundesgesetzes über Rohrleitungsanlagen (SG 772.580) | 1 | one version (the oldest available), 1 January 2009 |
| `780-200-uvpv-bs/` | Verordnung über die Umweltverträglichkeitsprüfung im Kanton Basel-Stadt (SG 780.200) | 1 | one version (the oldest available), 1 January 2001 |
| `780-300-mobilitatsfondsverordnung/` | Verordnung über den Mobilitätsfonds (SG 780.300) | 4 | as enacted, then each consolidated version: 23 December 2012 to 1 November 2025 |
| `780-350-vuv/` | Verordnung über umweltfreundliche Verkehrsmittel (SG 780.350) | 2 | as enacted, then each consolidated version: 10 November 2013 to 1 January 2021 |
| `780-360-verordnung-ladeinfrastruktur/` | Verordnung über die Förderung der Ladeinfrastruktur für Elektroautos (SG 780.360) | 1 | as enacted, 1 July 2024 |
| `780-750/` | Verordnung über die Gebühren des Amtes für Umwelt und Energie (SG 780.750) | 1 | as enacted, 1 January 2026 |
| `780-900/` | Verordnung über die Gebühren des Kantonalen Laboratoriums im Bereich der Umweltschutzgesetzgebung (SG 780.900) | 2 | oldest version available, then each consolidated version: 14 March 2004 to 13 December 2018 |
| `781-200-lhv/` | Verordnung über die Lufthygiene (SG 781.200) | 2 | as enacted, then each consolidated version: 1 January 1993 to 1 January 2026 |
| `781-220-massnahmenverordnung/` | Verordnung über die Verschärfung von Emissionsbegrenzungen für stationäre Anlagen (SG 781.220) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 April 2026 |
| `781-500-smog-verordnung/` | Verordnung zur kurzfristigen Bekämpfung übermässiger Luftschadstoff-Immissionen infolge austauscharmer Wetterlagen (SG 781.500) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `782-100-lsv-bs/` | Lärmschutzverordnung Basel-Stadt (SG 782.100) | 1 | one version (the oldest available), 22 April 2007 |
| `782-420/` | Verordnung betreffend Strassenmusik und Strassenkunst (SG 782.420) | 3 | as enacted, then each consolidated version: 1 March 2012 to 1 July 2020 |
| `783-200/` | Kantonale Gewässerschutzverordnung (SG 783.200) | 3 | oldest version available, then each consolidated version: 9 April 2010 to 1 July 2020 |
| `783-410-grundwasserverordnung/` | Verordnung über Grundwasserschutzzonen und Gewässerschutzbereiche (SG 783.410) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2019 |
| `784-300/` | Verordnung über die Gebühren der Abteilung Stadtentwässerung im Tiefbauamt (SG 784.300) | 1 | as enacted, 1 January 2009 |
| `786-100/` | Abfallverordnung (SG 786.100) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `786-150-asv/` | Verordnung über Abfallsammlungen in der Stadt Basel (SG 786.150) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `787-100-bosv/` | Bodenschutzverordnung Basel-Stadt (SG 787.100) | 1 | one version (the oldest available), 1 January 2009 |
| `788-150-vvnissg/` | Vollziehungsverordnung zum Bundesgesetz über den Schutz vor Gefährdungen durch nichtionisierende Strahlung und Schall (SG 788.150) | 1 | as enacted, 9 July 2026 |
| `789-110/` | Verordnung über den Natur- und Landschaftsschutz (SG 789.110) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2019 |
| `789-600/` | Verordnung über die Förderung der Biodiversität und Landschaftsqualität im Landwirtschaftsgebiet (SG 789.600) | 1 | as enacted, 1 April 2015 |
| `789-710-bsv/` | Baumschutzverordnung (SG 789.710) | 1 | as enacted, 31 December 2000 |
| `790-150/` | Verordnung betreffend die Sachverständigen der Baurekurskommission (SG 790.150) | 3 | oldest version available, then each consolidated version: 1 July 2007 to 28 May 2022 |
| `810-140-gebuhrenverordnung-awa/` | Verordnung über die vom Amt für Wirtschaft und Arbeit zu erhebenden Gebühren (SG 810.140) | 2 | oldest version available, then each consolidated version: 1 January 2004 to 1 February 2021 |
| `811-110/` | Verordnung zum Gesetz über öffentliche Ruhetage und Ladenöffnung (SG 811.110) | 3 | as enacted, then each consolidated version: 29 June 2008 to 21 December 2023 |
| `812-210-milov/` | Verordnung über den kantonalen Mindestlohn (SG 812.210) | 1 | as enacted, 1 July 2022 |
| `812-350-taxi-arv/` | Verordnung betreffend Arbeits- und Ruhezeit der Taxifahrerinnen und Taxifahrer im Kanton Basel-Stadt (SG 812.350) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2018 |
| `812-500/` | Verordnung betreffend den Vollzug des Bundesgesetzes über die Heimarbeit vom 20. März 1981 (SG 812.500) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2020 |
| `812-600/` | Verordnung über die Organisation der Bekämpfung der Schwarzarbeit im Kanton Basel-Stadt (SG 812.600) | 1 | as enacted, 1 January 2008 |
| `812-810/` | Verordnung zum Bundesgesetz über die Sicherheit von technischen Einrichtungen und Geräten (SG 812.810) | 1 | one version (the oldest available), 1 January 2009 |
| `812-900/` | Verordnung zum Bundesgesetz über die in die Schweiz entsandten Arbeitnehmerinnen und Arbeitnehmer (SG 812.900) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 28 March 2019 |
| `813-310/` | Vollziehungsverordnung zum Gesetz betreffend das ständige staatliche Einigungsamt vom 9. November 1911 (SG 813.310) | 1 | one version (the oldest available), 3 December 2009 |
| `813-400/` | Verordnung über das Verfahren vor dem Einigungsamt als vertraglichem Schiedsgericht (SG 813.400) | 1 | one version (the oldest available), 1 January 2009 |
| `815-110-kindertagesstatten-und-tagesfamilienverordnung-ktv/` | Verordnung über die Betreuung von Kindern in Kindertagesstätten und Tagesfamilien (SG 815.110) | 8 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2024 |
| `815-120-tagesbetreuungsbeitragsverordnung-tbv/` | Verordnung über die Betreuungsbeiträge in Kindertagesstätten und Tagesfamilien und die Leistungen an Eltern (SG 815.120) | 3 | as enacted, then each consolidated version: 1 January 2022 to 1 August 2024 |
| `815-150-spielgruppenbeitragsverordnung-sbv/` | Verordnung betreffend ergänzende Beiträge für die frühkindliche Förderung in Spielgruppen mit Deutschförderung (SG 815.150) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2024 |
| `819-179-covid-19-verordnung-hartefallprogramm-2022/` | Verordnung betreffend Härtefallprogramm für Unternehmen im Zusammenhang mit der Covid-19-Pandemie im Jahr 2022 (SG 819.179) | 1 | as enacted, 1 March 2022 |
| `819-510/` | Verordnung über die Arbeitsvermittlung und den Personalverleih (SG 819.510) | 1 | as enacted, 9 July 2012 |
| `819-600/` | Verordnung über die Meldepflicht der Arbeitgeber bei bevorstehenden Entlassungen (SG 819.600) | 1 | as enacted, 1 April 1979 |
| `819-610/` | Verordnung über die Kontrolle und Finanzierung der Stellenmeldepflicht (SG 819.610) | 1 | as enacted, 1 March 2026 |
| `819-850/` | Reglement betreffend Gewährung von Bürgschaften (SG 819.850) | 1 | as enacted, 2 March 1976 |
| `819-870-covid-19-burgschaftsverordnung/` | Verordnung betreffend Gewährung von Bürgschaften im Zusammenhang mit der COVID-19-Pandemie (SG 819.870) | 2 | as enacted, then each consolidated version: 25 March 2020 to 16 December 2020 |
| `819-872-covid-19-start-up-burgschaftsverordnung-2/` | Verordnung 2 betreffend Gewährung von kantonalen Start-up-Bürgschaften infolge COVID-19-Pandemie (SG 819.872) | 1 | as enacted, 1 December 2020 |
| `819-879-covid-19-verordnung-hartefallprogramm/` | Verordnung betreffend Härtefallprogramm für Unternehmen im Zusammenhang mit der Covid-19-Pandemie (SG 819.879) | 6 | oldest version available, then each consolidated version: 1 November 2020 to 21 April 2021 |
| `819-879-001-covid-19-verordnung-unterstutzungsprogramm-gastronomie-und-hotellerie/` | Verordnung betreffend Unterstützungsprogramm für Gastronomie und Hotellerie im Zusammenhang mit der Covid-19-Pandemie (SG 819.879.001) | 1 | as enacted, 1 January 2022 |
| `831-290/` | Verordnung über die Erhebung von Verwaltungskostenbeiträgen durch die Kantonale Ausgleichskasse/AHV (SG 831.290) | 1 | as enacted, 1 January 1984 |
| `831-300/` | Verordnung über die Erhebung von Sondergebühren durch die Kantonale Ausgleichskasse/AHV (SG 831.300) | 1 | as enacted, 1 January 1983 |
| `832-710-velg/` | Verordnung betreffend Ergänzungsleistungen und kantonale Beihilfen zur Alters-, Hinterlassenen- und Invalidenversicherung (SG 832.710) | 10 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `832-720-kbv/` | Verordnung über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (SG 832.720) | 7 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `834-410-kvo/` | Verordnung über die Krankenversicherung im Kanton Basel-Stadt (SG 834.410) | 19 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2027 |
| `834-800/` | Verordnung zum Bundesgesetz über die Unfallversicherung (UVG) (SG 834.800) | 1 | one version (the oldest available), 1 January 2009 |
| `835-150/` | Verordnung betreffend Zuständigkeit und Organisation beim Vollzug der Arbeitslosenversicherung im Kanton Basel-Stadt (SG 835.150) | 3 | as enacted, then each consolidated version: 24 April 2012 to 17 February 2016 |
| `835-210/` | Verordnung zum Gesetz betreffend den Fonds zur Bekämpfung der Arbeitslosigkeit (SG 835.210) | 1 | one version (the oldest available), 1 January 2009 |
| `835-350/` | Reglement der Öffentlichen Arbeitslosenkasse Basel-Stadt (SG 835.350) | 3 | as enacted, then each consolidated version: 1 January 1985 to 1 October 2025 |
| `835-510-alhv/` | Verordnung betreffend kantonale Arbeitslosenhilfe (SG 835.510) | 1 | one version (the oldest available), 1 January 2009 |
| `861-250/` | Verordnung betreffend den Wohnflächenanteil (SG 861.250) | 3 | oldest version available, then each consolidated version: 11 July 2004 to 1 January 2019 |
| `861-520-wohnraumforderungsverordnung-wrfv/` | Verordnung über die Wohnraumförderung (SG 861.520) | 6 | as enacted, then each consolidated version: 1 July 2014 to 2 July 2026 |
| `861-540-wohnraumschutzverordnung-wrschv/` | Verordnung über den Schutz von Wohnraum (SG 861.540) | 3 | as enacted, then each consolidated version: 28 May 2022 to 1 November 2025 |
| `861-625-mietreglement-mr/` | Mietreglement der Stiftung für preisgünstigen Wohnraum Basel-Stadt (SG 861.625) | 1 | as enacted, 2 October 2025 |
| `869-710-bhv/` | Verordnung über die Behindertenhilfe (SG 869.710) | 4 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2025 |
| `890-510-mietbeitragsverordnung-mbvo/` | Verordnung zum Gesetz über die Ausrichtung von Mietbeiträgen (SG 890.510) | 5 | as enacted, then each consolidated version: 1 January 2009 to 1 July 2025 |
| `890-710-sohav/` | Verordnung über die Harmonisierung und Koordination von bedarfsabhängigen Sozialleistungen (SG 890.710) | 6 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2021 |
| `910-210-stafov/` | Verordnung zum Standortförderungsgesetz (SG 910.210) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 April 2026 |
| `910-230/` | Verordnung zum Stadtbelebungsfonds (SG 910.230) | 2 | as enacted, then each consolidated version: 1 January 2021 to 31 August 2023 |
| `910-300/` | Verordnung betreffend den Vollzug des Bundesgesetzes über die wirtschaftliche Landesversorgung (LVG) (SG 910.300) | 1 | one version (the oldest available), 3 December 2009 |
| `910-400/` | Verordnung zum Bundesgesetz über das Messwesen (SG 910.400) | 1 | as enacted, 1 February 2021 |
| `911-400/` | Verordnung betreffend den kantonalen Pflanzenschutzdienst (SG 911.400) | 1 | one version (the oldest available), 3 December 2009 |
| `911-610-wav-bs/` | Verordnung zum Waldgesetz Basel-Stadt (SG 911.610) | 5 | oldest version available, then each consolidated version: 1 September 2011 to 1 January 2025 |
| `912-510-fischereiverordnung/` | Verordnung über die Fischerei im Kanton Basel-Stadt (SG 912.510) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `914-210-ev-ivob/` | Einführungsverordnung zur Interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (SG 914.210) | 1 | as enacted, 1 February 2024 |
| `951-110-ov-verordnung/` | Verordnung zum Gesetz über den öffentlichen Verkehr (SG 951.110) | 1 | as enacted, 1 July 2011 |
| `952-200-strassenverkehrsverordnung-stvo/` | Verordnung über den Strassenverkehr (SG 952.200) | 8 | oldest version available, then each consolidated version: 1 August 2012 to 1 July 2025 |
| `952-250/` | Reglement über die Versteigerung von Kontrollschildern im Internet (SG 952.250) | 1 | as enacted, 1 July 2007 |
| `952-260/` | Reglement über Wunschkontrollschilder (SG 952.260) | 1 | as enacted, 1 August 2010 |
| `952-300-zufahrtsverordnung/` | Verordnung betreffend die ausnahmsweise Zufahrt in die Innenstadt (SG 952.300) | 9 | as enacted, then each consolidated version: 1 January 2014 to 3 November 2026 |
| `952-560-parkraumbewirtschaftungsverordnung-prbv/` | Verordnung über die Parkraumbewirtschaftung (SG 952.560) | 8 | as enacted, then each consolidated version: 1 August 2012 to 1 January 2025 |
| `952-600-parkgaragenverordnung/` | Verordnung über den Betrieb der Parkgaragen Elisabethen, Steinen, City, Storchen und St. Jakob sowie des Parkplatzes St. Jakob (SG 952.600) | 2 | oldest version available, then each consolidated version: 1 July 2007 to 21 October 2017 |
| `955-100-kleinschifffahrtsverordnung/` | Vollziehungsverordnung zum Bundesgesetz über die Binnenschifffahrt (SG 955.100) | 3 | as enacted, then each consolidated version: 1 January 2009 to 1 July 2020 |
| `bab-153-115/` | Reglement über die Entschädigung der Mitglieder des Bürgerrats (SG BaB 153.115) | 1 | as enacted, 1 January 2026 |
| `bab-153-200/` | Reglement für die Institutionen und die Zentralen Dienste (SG BaB 153.200) | 4 | oldest version available, then each consolidated version: 11 March 2007 to 10 February 2022 |
| `bab-153-300/` | Reglement für die Einbürgerungskommission (SG BaB 153.300) | 3 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2026 |
| `bab-153-400/` | Reglement über die Verwendung von Tonaufzeichnungsgeräten durch die Zentralen Dienste (SG BaB 153.400) | 2 | as enacted, then each consolidated version: 26 October 2014 to 7 February 2019 |
| `bab-153-840/` | Gebührenreglement der Zentralen Dienste (SG BaB 153.840) | 6 | as enacted, then each consolidated version: 1 July 2012 to 1 January 2024 |
| `bab-155-100-zunftordnung/` | Reglement über die Organisation der E. Zünfte der Stadt Basel (SG BaB 155.100) | 2 | oldest version available, then each consolidated version: 28 April 1991 to 1 January 2022 |
| `bab-155-200-vorstadtordnung/` | Reglement über die Organisation der Vorstadtgesellschaften Grossbasels (SG BaB 155.200) | 4 | as enacted, then each consolidated version: 1 July 1990 to 1 January 2022 |
| `bab-155-300-ordnung-fur-die-drei-e-gesellschaften/` | Reglement über die Organisation der Drei E. Gesellschaften Kleinbasels (SG BaB 155.300) | 3 | oldest version available, then each consolidated version: 5 November 2000 to 1 January 2022 |
| `bab-155-400-korporationsordnung/` | Reglement über die Organisation der Bürgerkorporation Kleinhüningen (SG BaB 155.400) | 3 | as enacted, then each consolidated version: 1 July 1990 to 1 January 2022 |
| `bab-155-700-verwaltungsordnung/` | Reglement über die Verwaltung der Korporationsvermögen (SG BaB 155.700) | 2 | oldest version available, then each consolidated version: 22 January 1998 to 1 January 2022 |
| `bab-162-110/` | Reglement zur Anstellungsordnung (SG BaB 162.110) | 9 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2023 |
| `bab-164-110/` | Reglement zur Lohnordnung (SG BaB 164.110) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `bab-169-400/` | Reglement für den Personalausschuss Bürgerspital Basel (SG BaB 169.400) | 2 | as enacted, then each consolidated version: 22 April 2012 to 19 July 2018 |
| `bab-169-550/` | Reglement für die sozialpartnerschaftliche Begutachtungskommission (SG BaB 169.550) | 1 | as enacted, 1 January 2026 |
| `bab-169-600/` | Reglement betreffend das Vorschlagswesen in der Bürgergemeinde der Stadt Basel (SG BaB 169.600) | 1 | as enacted, 20 December 1992 |
| `bab-172-300/` | Reglement für die Christoph Merian Stiftung (SG BaB 172.300) | 4 | oldest version available, then each consolidated version: 11 March 2007 to 1 January 2025 |
| `bab-212-100/` | Reglement über die Stiftungsaufsicht des Bürgerrats über die der Bürgergemeinde der Stadt Basel zugeordneten selbständigen Stiftungen (SG BaB 212.100) | 1 | as enacted, 5 January 2014 |
| `beb-121-150/` | Reglement über die Erhebung von Gebühren im Einbürgerungsverfahren (SG BeB 121.150) | 1 | one version (the oldest available), 1 July 2012 |
| `bee-132-110/` | Reglement über die Öffnungszeiten der Wahllokale (SG BeE 132.110) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 2 September 2019 |
| `bee-153-210-organisationsreglement/` | Reglement über die Organisation des Gemeinderats und der Gemeindeverwaltung Bettingen (SG BeE 153.210) | 2 | as enacted, then each consolidated version: 8 February 2021 to 1 July 2023 |
| `bee-153-500-mitwirkungsreglement/` | Reglement über die Mitwirkung von Jugendlichen (SG BeE 153.500) | 2 | as enacted, then each consolidated version: 26 February 2012 to 1 November 2018 |
| `bee-153-840-verwaltungsgebuhrenreglement/` | Reglement betreffend die Erhebung von Verwaltungsgebühren (SG BeE 153.840) | 3 | as enacted, then each consolidated version: 10 October 2010 to 26 December 2024 |
| `bee-328-610/` | Reglement betreffend die Zahnpflege bei Kindern (Zahnpflegereglement) (SG BeE 328.610) | 3 | as enacted, then each consolidated version: 1 January 1995 to 8 March 2018 |
| `bee-370-700-gartenbad-reglement/` | Reglement für das Gartenbad Bettingen (SG BeE 370.700) | 5 | as enacted, then each consolidated version: 1 May 2012 to 2 May 2022 |
| `bee-411-630-ermassigungsreglement-musik-bettingen-ermbe/` | Reglement betreffend die Ermässigung der Elterntarife für den ausserschulischen Musikunterricht (SG BeE 411.630) | 1 | as enacted, 1 January 2025 |
| `bee-610-100-finanzreglement/` | Finanzreglement über das Rechnungswesen der Einwohnergemeinde Bettingen (SG BeE 610.100) | 2 | as enacted, then each consolidated version: 1 January 2002 to 1 January 2019 |
| `bee-660-100/` | Reglement Vorfinanzierung / Fonds Landerwerbe in Zone NÖI (Nutzung im Öffentlichen Interesse) (SG BeE 660.100) | 1 | as enacted, 20 April 2010 |
| `bee-680-200/` | Reglement betreffend die ausserschulische Nutzung der Schulanlagen Bettingen (SG BeE 680.200) | 3 | as enacted, then each consolidated version: 1 July 2019 to 1 July 2021 |
| `bee-730-500-fondsreglement-mehrwertabgabe/` | Reglement betreffend die Verwendung des Ertrages aus Mehrwertabgaben (SG BeE 730.500) | 2 | as enacted, then each consolidated version: 25 April 2006 to 1 May 2023 |
| `bee-750-110-strassen-und-kanalisationsreglement/` | Reglement betreffend die Strassen- und Kanalisationsbeiträge sowie Gebühren für die Ableitung von Abwasser in Bettingen (SG BeE 750.110) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 October 2020 |
| `bee-786-150/` | Gebührenreglement für die Entsorgung von Hauskehricht und Sperrgut (SG BeE 786.150) | 1 | one version (the oldest available), 1 July 2009 |
| `bee-789-310-forderung-der-biodiversitat-reglement/` | Reglement zur Ordnung über den Natur- und Landschaftsschutz und die Förderung der Biodiversität und Landschaftsqualität (SG BeE 789.310) | 5 | as enacted, then each consolidated version: 7 January 2007 to 1 May 2023 |
| `bee-970-170/` | Gebührenreglement für das Kommunikationsnetz (K-Netz) der Gemeinde Bettingen (SG BeE 970.170) | 1 | as enacted, 1 October 2002 |
| `rib-121-150/` | Reglement über die Erhebung von Gebühren im Einbürgerungsverfahren (SG RiB 121.150) | 4 | oldest version available, then each consolidated version: 1 July 2012 to 1 January 2026 |
| `rie-132-110-reglement-politische-rechte-rpr/` | Reglement der politischen Rechte in der Einwohnergemeinde Riehen (SG RiE 132.110) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 March 2025 |
| `rie-153-100-organisationsreglement-ogr/` | Reglement über die Organisation des Gemeinderats und der Gemeindeverwaltung (SG RiE 153.100) | 6 | as enacted, then each consolidated version: 1 April 2003 to 1 January 2024 |
| `rie-153-170-reglement-gfs/` | Reglement über den Gemeindeführungsstab Riehen (SG RiE 153.170) | 2 | as enacted, then each consolidated version: 11 June 2020 to 6 June 2024 |
| `rie-153-300-informationssicherheitsreglement/` | Reglement über die Informationssicherheit der Gemeinde Riehen (SG RiE 153.300) | 1 | as enacted, 1 August 2021 |
| `rie-153-500/` | Reglement über die Mitwirkung der Quartierbevölkerung der Gemeinde Riehen (SG RiE 153.500) | 2 | as enacted, then each consolidated version: 19 September 2010 to 1 January 2025 |
| `rie-153-840-gebuhrenreglement-einwohnerdienste/` | Reglement betreffend die Erhebung von Gebühren der Einwohnerdienste der Gemeinde Riehen (SG RiE 153.840) | 2 | as enacted, then each consolidated version: 13 November 1994 to 1 January 2025 |
| `rie-153-900/` | Reglement betreffend die Benützung der Dokumentationsstelle Riehen (Benützungsreglement Dokumentationsstelle) (SG RiE 153.900) | 2 | as enacted, then each consolidated version: 18 January 2007 to 12 January 2014 |
| `rie-162-110/` | Personalreglement (SG RiE 162.110) | 12 | oldest version available, then each consolidated version: 27 June 2013 to 1 August 2026 |
| `rie-164-110-lohnreglement/` | Reglement über das Gehalt der Mitarbeiterinnen und Mitarbeiter der Gemeinde Riehen (SG RiE 164.110) | 12 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `rie-164-420/` | Spesenreglement der Gemeindeverwaltung Riehen (SG RiE 164.420) | 5 | as enacted, then each consolidated version: 16 December 2007 to 1 January 2026 |
| `rie-253-150-reglement-wildtierschutz-riehen/` | Reglement betreffend zusätzliche Schutzmassnahmen für Wildtiere (SG RiE 253.150) | 1 | as enacted, 1 April 2024 |
| `rie-328-610-zahnpflegereglement/` | Reglement betreffend die Zahnpflege bei Kindern (SG RiE 328.610) | 2 | oldest version available, then each consolidated version: 1 January 2002 to 31 October 2013 |
| `rie-350-100/` | Reglement betreffend die Vergabe von Beiträgen im Bereich Gesundheit und Soziales (SG RiE 350.100) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `rie-370-700-naturbadreglement/` | Reglement für die Benützung des Naturbads der Gemeinde Riehen (SG RiE 370.700) | 1 | as enacted, 23 February 2014 |
| `rie-390-890-bestattungsreglement/` | Reglement über die Bestattungen in der Gemeinde Riehen (SG RiE 390.890) | 4 | as enacted, then each consolidated version: 18 May 1997 to 1 April 2025 |
| `rie-411-610-schulreglement/` | Reglement für die Schulen der Gemeinden Bettingen und Riehen (SG RiE 411.610) | 14 | oldest version available, then each consolidated version: 19 July 2012 to 1 August 2026 |
| `rie-411-630-reglement-ermassigung-elterntarif-musik-reemu/` | Reglement betreffend die Ermässigung der Elterntarife für den ausserschulischen Musikunterricht in Riehen (SG RiE 411.630) | 1 | as enacted, 1 January 2024 |
| `rie-416-300/` | Reglement betreffend Ausrichtung eines Sportpreises (SG RiE 416.300) | 4 | as enacted, then each consolidated version: 1 June 1997 to 1 January 2026 |
| `rie-416-400/` | Reglement für die Fachkommission zur Förderung von Aktivitäten im Bereich Sport der Gemeinde Riehen (SG RiE 416.400) | 3 | as enacted, then each consolidated version: 1 January 2004 to 1 January 2026 |
| `rie-440-100/` | Reglement für die Gemeindebibliothek Riehen (SG RiE 440.100) | 4 | as enacted, then each consolidated version: 4 March 1999 to 1 January 2026 |
| `rie-451-200/` | Reglement für die Museen im Wettsteinhaus der Gemeinde Riehen (SG RiE 451.200) | 3 | as enacted, then each consolidated version: 15 October 1995 to 1 January 2026 |
| `rie-494-300-reglement-bildende-kunst/` | Reglement betreffend die Förderung der Bildenden Kunst durch die Gemeinde Riehen (SG RiE 494.300) | 6 | as enacted, then each consolidated version: 20 May 2010 to 1 January 2026 |
| `rie-494-400/` | Reglement betreffend Ausrichtung eines Kulturpreises (SG RiE 494.400) | 4 | as enacted, then each consolidated version: 15 January 1995 to 1 January 2026 |
| `rie-640-110-steuerreglement/` | Reglement zur Steuerordnung der Gemeinde Riehen (SG RiE 640.110) | 1 | one version (the oldest available), 30 March 2008 |
| `rie-681-200/` | Reglement betreffend die Nutzung des Bürgersaals (SG RiE 681.200) | 1 | as enacted, 1 June 2017 |
| `rie-681-500/` | Reglement betreffend die ausserschulische Nutzung der Schulanlagen (SG RiE 681.500) | 2 | as enacted, then each consolidated version: 1 July 2017 to 1 August 2019 |
| `rie-681-700-sportplatzreglement/` | Reglement für die Benützung der Sportanlage Grendelmatte (SG RiE 681.700) | 1 | as enacted, 2 February 2014 |
| `rie-724-150-allmendreglement/` | Reglement über die Inanspruchnahme der Allmend (SG RiE 724.150) | 3 | as enacted, then each consolidated version: 1 May 2004 to 1 January 2018 |
| `rie-725-110/` | Reglement über die Parkraumbewirtschaftung (SG RiE 725.110) | 4 | as enacted, then each consolidated version: 18 November 2013 to 11 June 2015 |
| `rie-727-200/` | Reglement über die Strassenreinigung in der Gemeinde Riehen (SG RiE 727.200) | 2 | as enacted, then each consolidated version: 3 June 1981 to 17 November 2013 |
| `rie-730-350-obk-reglement/` | Reglement über die Organisation der Ortsbildkommission (SG RiE 730.350) | 1 | as enacted, 20 February 2023 |
| `rie-730-710/` | Reglement über die Reinigung privater Liegenschaften bei Verschmierungen (SG RiE 730.710) | 2 | as enacted, then each consolidated version: 1 January 2013 to 12 May 2025 |
| `rie-750-110-strassen-und-kanalisationsreglement/` | Reglement betreffend Strassen- und Kanalisationsbeiträge sowie Gebühren für die Ableitung von Abwasser (SG RiE 750.110) | 3 | oldest version available, then each consolidated version: 25 March 2010 to 12 March 2018 |
| `rie-782-420/` | Reglement betreffend Strassenmusik und Strassenkunst in Riehen (SG RiE 782.420) | 1 | as enacted, 1 January 2026 |
| `rie-786-150/` | Gebührenreglement für die Abfuhr und Vernichtung von Hauskehricht und Sperrgut (SG RiE 786.150) | 1 | one version (the oldest available), 1 July 2009 |
| `rie-786-180-reglement-mehrweggeschirr/` | Reglement über die Verwendung von Mehrweggeschirr (SG RiE 786.180) | 1 | as enacted, 1 January 2024 |
| `rie-789-100/` | Reglement für die Naturschutzkommission des Gemeinderates Riehen (SG RiE 789.100) | 1 | as enacted, 18 April 1991 |
| `rie-789-150/` | Reglement für die Kommission Lokale Agenda 2030 für nachhaltige Entwicklung (SG RiE 789.150) | 1 | as enacted, 26 September 2024 |
| `rie-789-300-beitragsreglement-landwirtschaft/` | Reglement über die Förderung der Biodiversität und Landschaftsqualität im Landwirtschaftsgebiet (SG RiE 789.300) | 2 | as enacted, then each consolidated version: 1 January 2006 to 18 April 2022 |
| `rie-834-700/` | Reglement des Sozialhilfe- und Gesundheitsfonds der Gemeinde Riehen (SG RiE 834.700) | 2 | as enacted, then each consolidated version: 11 December 2011 to 1 January 2017 |
| `rie-890-110/` | Sozialhilfereglement (SG RiE 890.110) | 1 | as enacted, 1 January 2005 |
| `rie-890-700/` | Reglement für den Hilfsfonds der Gemeinde Riehen vom 21. Juli 1965 (SG RiE 890.700) | 1 | as enacted, 4 November 1984 |
| `rie-890-710/` | Reglement über Verwendung und Verwaltung des Jubiläumsfonds Riehen (SG RiE 890.710) | 1 | as enacted, 26 February 1925 |
| `rie-912-210/` | Reglement über die Jagdpassgebühren (SG RiE 912.210) | 1 | as enacted, 26 September 1993 |
| `rie-912-510-fischereireglement/` | Reglement über die Fischerei in der Gemeinde Riehen (SG RiE 912.510) | 2 | as enacted, then each consolidated version: 17 April 1994 to 7 March 2019 |
| `rie-980-110/` | Reglement für die Vergabekommission Entwicklungszusammenarbeit (SG RiE 980.110) | 1 | as enacted, 31 January 2022 |

## Source

The SG (systematic collection) of the canton, published by the canton at <https://www.gesetzessammlung.bs.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CG). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CG), with an e-mail address that cannot exist (`<act key>@www.gesetzessammlung.bs.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
