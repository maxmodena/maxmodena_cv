Massimiliano Modena
============

----

-------------------         ----------------------------------
Via delle Acacie 1,                      maxmodena@hotmail.com
20090, Cesano Boscone       
Milano                                       +39.349.16.35.304
-------------------         ----------------------------------

----

>  Senior Consultant @BInnovation || 
>  Project Coordinator || 
>  BI Specialist & DWH Architect || 
>  Mulesoft Developer & Architect || 
>  Talend Cloud Developer & Admin ||
>  FullStack Javascript Architect ||
>  Boomi Associate & Professional Linux Administrator certified

**Business Intelligence**\
Mi occupo principalmente dello sviluppo e gestione di progetti di BI sia per la parte di reportistica (principalmente SAP BO 4.2; Qlikview 11.2 e 12, saltuariamente PowerBI e MicroStrategy), sia per la progettazione di Datawarehouse e Sistemi di Integrazione in ambiente Oracle, SqlServer o Vertica, sia per l'installazione e configurazione di Qlikview Server/Publisher 11.2 . 
Possiedo ottime capacità di individuazione, analisi e risoluzione delle criticità tecniche ed architetturali, ed ottime conoscenze dei principali RDBMS Sql (Oracle11g-21c/SqlServer/DuckDB) e NoSql (MongoDB); 

Utilizzo le piattaforme di integrazione SSIS, Semarchy xDI, Talend Cloud, Mulesoft Anypoint Platform e Boomi; ho avuto anche l'occasione di valutare ed esplorare Alterix Designer. Oltre a queste utilizziamo una nostra piattaforma di integrazione e schedulazione di tipo ELT che effettua le trasformazioni personalizzandole su Oracle o SqlServer in PL/SQL o T-SQL massimizzando le prestazioni ottenibili. Sono Boomi Administrator certificato sia come Associated Administrator che Professional Linux Operational Administrator.

Utilizzo correntemente Git/GitHub per il versioning delle implementazioni dei progetti gestiti in prima persona, e TFS qualora già utilizzato dai clienti.

**Full Stack Web Architect**\
Ho esperienza più che decennale di progettazione architetturale ed implementazione di web applications su framework ExtJS con diversi back-end. Ho utilizzato negli anni diversi linguaggi, tra cui php, jsp, c# e javascript insieme a diversi db, anche documentali, tra cui Oracle, SqlServer, SqlLite e MongoDB. Utilizzo attualmente una struttura full stack javascript con backend Nodejs, anche in architettura a microservizi.
Interesse corrente: utilizzo del framework gRPC per la comunicazione tra microservizi nodejs in architettura basata su API Gateway ed autenticazione/autorizzazioni con token JWT.

**DevOps**\
Ho buone conoscenze di virtualizzazione di nodi Linux o Windows, ed esperienza di progettazione di Docker Containers gestiti con Docker-Compose e di Cluster Kubernetes su più nodi virtuali Linux. Ho progettato un cluster Microk8s in HA su nodi virtuali Ubuntu, con configurazione di  MongoDB in Sharding/ReplicaSet sul cluster k8s, utilizzato per l'implementazione e configurazione di applicazioni su pod in autoscaling composti internamente da container multipli. 
Utilizzo correntemente db Oracle19c e 23c rilasciati su Docker. 
Ho implementato alcune pipelines di CI/CD (per apps containerizzate) con GitHub Actions ed ArgoCD, ed una pipeline di CD relativa ad attività plsql/oracle su Jenkins per il rilascio automatico in ambiente di sviluppo/integrazione tramite webhook.

**Focus tecnologico attuale**\
Sto analizzando le seguenti tecnologie per integrare le mie competenze in questi ambiti:
- utilizzo di Ducklake (Data Lakehouse ad alte prestazioni, alternativo ad Iceberg, con catalogo su db postgres e dati su filesystem o bucket S3/minio)
- utilizzo del server gizmosql per l'accesso a Ducklake con connettività ad alta efficienza Arrow Flight Sql
- utilizzo di Apache Spark tramite pyspark, con o senza tabelle Apache Iceberg
- analisi delle pipelines di integrazione in dbt
- analisi dell'ambiente Snowflake 
----



Educazione
----------

1990-1998   
:   **Corso di Laurea in Ingegneria Elettronica – indirizzo Microelettronica**; Politecnico di Milano – Facolta’ di Ingegneria


1985-1990
:   **Diploma di Maturita’ scientifica**; Liceo Scientifico G.B.Vico – 20094 Corsico –Milano


Esperienza Lavorativa
---------------------

2018-2025 (in corso)  
:   **Senior Consultant & Project coordinator @Binnovation**

:   A seguito della confluenza di Softquattro in Binnovation collaboro da Marzo 2018 con quest'ultima come Consulente Senior in ambito BI.
Ho continuato a seguire principalmente il cliente in ambito GDO che seguivo già in Softquattro, gestendo le attività legate all' AM e quelle legate ai progetti di evolutiva lungo tutta la filiera, dalla preparazione delle offerte all'analisi funzionale e tecnica fino alle implementazioni ed ai rilasci finali. 

    * Per la gestione dei ticket di AM ho sviluppato una webapp full stack javascript, e per l'acquisizione del flusso degli scontrini in arrivo dai punti vendita ho progettato un set di webservice su Nodejs , con l'utilizzo di un buffer MongoDB per la traduzione dei dati da documenti JSON ed il trasporto sul DWH Oracle finale. 
    * Negli ultimi anni ho implementato un sistema di gestione del codice sorgente basato su git/github, ho introdotto l'utilizzo di container docker ed ho proposto l'utilizzo di cluster kubernetes per la gestione dei webservices degli scontrini.
    * Ho avviato la migrazione dell'interfaccia web del sistema di integrazione ELT custom DWMS, da una piattaforma Jsp ad una fullstack javascript ExtJs/nodejs
    * Sto esplorando nuove tecnologie da introdurre per ottimizzare la fase di acquisizione e trasformazione dei dati alimentanti il Datawarehouse

:   In Binnovation ho seguito anche attività relative ad altri clienti nei seguenti ambiti

    * cliente in ambito retail, per la gestione del datawarehouse e delle attività collegate,basate su un ambiente SqlServer e SSIS 
    * cliente in ambito GDO, per la gestione del datawarehouse dello scontrinato, implementato su db Vertica con sistema di integrazione dati basato su piattaforma Stambia Data Integration (poi nel frattempo diventata Semarchy XDi)
    * cliente in ambito assicurativo per la gestione del repository di alimentazione di QlikSense, basato su un datawarehouse in modello DataVault 2 e datamart dimensionali, con integrazione dati tramite SSIS e TFS

2006-2018
:   **Senior Analyst & Project Coordinator @Softquattro**

:   Ho lavorato in Softquattro da Settembre 2005 a Febbraio 2018, dapprima come Consulente BI junior e successivamente come Consulente/Analista Senior in ambito BusinessIntelligence. 

    *   Dal 2005 al 2008 ho seguito le attività di gestione di un DWH presso un cliente in ambito oil&gas, introducendo nel frattempo le prime tecnologie AJAX in diverse webapp ad uso interno. 
    *   Dal 2009 in poi ho iniziato a seguire un cliente in ambito GDO occupandomi dell'evoluzione del DWH della supply chain e del DWH di controllo commerciale, ed introducendo l'ambiente di datamart di interfaccia verso Hyperion Planning e il sistema di reportistica basato su Business Objects (da v.XI a v.4.0). Inoltre ho implementato per lo stesso cliente una webapp per la gestione dei fogli cassa di fine giorno, e la webapp per la festione Fatture, tuttora utilizzate, basate su framework ExtJS su application server JSP e business logic in pl/sql. 
:   Nel corso degli anni ho seguito anche altri clienti, principalmente nell'ambito automotive, retail e banking, per attività legate principalmente all'implementazione di reportistica basata di QlikView con piattaforme di integrazione dati implementata con l'utilizzo di SqlServer Integration Services (SSIS).
:   Nel corso del tempo ho aumentato le mie competenze occupandomi anche della gestione diretta del cliente rivestendo il ruolo di coordinatore progetti/PM per le attività di preparazione delle offerte, analisi tecniche e funzionali collegate e coordinamento di eventuali risorse allocate su tali progetti o sulle attività di AM.

2000-2005
:   **Analyst Programmer @PIC Servizi per l'informatica**

:   Ho lavorato in PIC da Ottobre 2000 ad Agosto 2005, prima come programmatore junior e successivamente come Analista Programmatore, allocato su diversi clienti principalmente in ambiti telecom, energy, e bancario, occupandomi di attività di sviluppo software utilizzando linguaggi C/C++/PLSql su applicazioni client-server prima e web poi (in C# ed ASP.NET)

Esperienza Tecnica
------------------

Database
:   Buone capacità di configurazione ed utilizzo dei seguenti database

    * **Oracle**: dalla versione 9.2 in poi, anche su container Docker o Oracle Cloud Infrastructure
    * **SqlServer**: dalla versione 2005 in poi
    * **MongoDB**: dalla versione 3.6 in poi, anche in versione cloud Atlas

:   Utilizzo corrente di **SqlLite** (v.3) come repository embedded per le web applications

:   Cononscenza ed utilizzo del db **Vertica** (da v.9 in poi) e **MySql** 

:   Conoscenza ed utilizzo del db analitico embedded DuckDB e del Data Lakehouse ducklake basato su Duckdb.

Sistemi di integrazione dati
:   Buona conoscenza dei seguenti sistemi di integrazione dati

    *	**SSIS** (Microsoft TSQL) - Utilizzo della piattaforma SSIS 2005-2016 per la costruzione di sistemi ETL.
    *	**Stambia - Semarchy XDi** (Java – Javascript): Utilizzo di Stambia Developer per la progettazione di flussi ELT di integrazione dati, configurazione e schedulazione dei flussi con Stambia Analytics.
    *   **Mulesoft Anypoint Platform**: utilizzo della piattaforma di integrazione **API** tramite **Anypoint Studio**
    *   **Boomi**: utilizzo della piattaforma di integrazione **Boomi**, compresa l'installazione e l'amministrazione di Atom o Molecules locali in ambiente Linux.
    *   **Talend Cloud** – Utilizzo di Talend Studio per la progettazione di flussi ETL di integrazione dati con pubblicazione cloud su Talend Management Console

:   Utilizzo di

    *   **Alterix** - Utilizzo di Alterix Designer per la progettazione di semplici flussi ETL di integrazione dati
    *   **dbt** - Utilizzo di Data Build Tool Core per la definizione di semplici pipeline di trasformazione dati in abbinamento a DuckDB

Piattaforme di reportistica ed analisi dei dati
:   Conoscenza avanzata della piattaforma **Qlikview**.

    *   **QlikView Client**:  progettazione scripting ETL e front-end applicazioni su piattaforma v11.20 RS2 e precedenti. 
    *   **QlikView Server/Publisher**: gestione e configurazione dell’application server , schedulazione dei task di pubblicazione dei documenti/applicazioni v.11.20 RS2 e precedenti.
    *   **Certificato QlikView 11 System Administrator**

:   Ottima conoscenza della piattaforma **SAP Business Objects**

    *   B.O. XI r.2 
    *   B.O. XI 3.1
    *   B.O. 4.2 
con utilizzo degli strumenti **Webi**, LiveOffice, Lumira, Desktop Intelligence, InfoView, **Designer**, **Information Design Tool** .

:   Conoscenza della piattaforma **BI Report Desktop** e delle tecniche di collegamento, tramite BI Connector e driver ODBC, a db nosql MongoDB

:   Conoscenza delle piattaforme **Microstrategy** e **PowerBI**


Linguaggi di Programmazione
:   **PL/SQL**: Ottima conoscenza ambiente Oracle (da v.9.2 – 10g – 11g – 12c, in poi) con capacità avanzata di analisi ed ottimizzazione computazionale delle query. 

:   **T-SQL**: Ottima conoscenza piattaforma SqlServer (da v.2008r2 in poi).

:   **Javascript**: Ottima conoscenza del linguaggio, utilizzato sia in backend su **NodeJs** che in frontend come **Vanilla Javascript** o tramite il framework **ExtJs** per la progettazione di web applications

:   **Python**: Utilizzo nelle pipeline di integrazione dati in abbinamento a dbt e DuckDB

:   **Java & JSP**: Utilizzo connettori jsp/beans come elemento di raccordo nelle webapp legacy tra client javascript e business logic in pl/sql su piattaforma Apache Tomcat

:   Nel corso della mia carriera lavorativa ho utilizzato anche questi linguaggi 

    * PHP
    * HTML, CSS
    * ASP 2.0 e ASP.NET
    * Visual Basic 6
    * Visual Basic for Applications
    * C (K&R)
    * C++
    * C# (.NET)
    * Korn shell script
    * MS VisualC++ (MFC)


Ambienti di sviluppo
:   Lavoro correntemente utilizzando ambienti Unix, Windows (desktop o server) e Linux

:   Ho acquisito competenze di gestione e configurazione di server Windows (da 2008r2 in poi) e del relativo Hyper-V Manager per la creazione e deployment dell’infrastruttura di virtualizzazione, con relativa configurazione di una infrastruttura di servizi di dominio Active Directory utilizzando Windows Server 2003 e 2008r2, gestendo in prima persona l'ambiente di virtualizzazione utilizzato per lo sviluppo centralizzato delle attività relative ad alcuni clienti utilizzando VM multiuser in RDP con i vari tool di sviluppo software

:   Ho conoscenze degli ambienti di virtualizzazione VMWare ESXi e Proxmox VE

Progettazione Datawarehouse e Data Lakehouse
:   Ottima conoscenza delle metodologie di progettazione e dimensionamento di un datawarehouse su piattaforma Oracle o SqlServer, con esperienza pluriennale in ambito GDO, Retail, Assicurativo, Banking e Servizi Finanziari

:   Ho esperienza di progettazione di Datawarehouse con l'utilizzo dei modelli

    * Modello Dimensionale a **Star Schema** o **Snowflake**
    * **Data Vault 2.0**
   

Infrastrutture e metodologie DevOps
:   Ho maturato competenze di tipo **DevOps** effettuando la progettazione di un ambiente basato su

    *   Installazione, configurazione ed implementazione di container **Docker**, anche tramite **docker-compose**
    *   Installazione e configurazione di un cluster **Kubernetes** **MicroK8s** su server linux Ubuntu
    *   Installazione e configurazione di pipeline **ArgoCD** per Kubernetes
    *   Installazione e configurazione di sistemi di monitoraggio k8s/Docker basati su **Portainer**       
    *   Installazione, configurazione ed utilizzo di **pipeline di Continuous Delivery** con **Jenkins**
    *   Utilizzo correntemente **Git** collegato ad un repository centrale su **GitHub**
    *   Ho esperienza di utilizzo di **TFS** su ambienti dei clienti come tool di source control management

Altre competenze
:   Possiedo una conoscenza avanzata della tecnologia AJAX (Rich Web Applications) e dei Framework ExtJs v.3.4., v.4.2 e successivi, ed Ext.NET (ExtJs v4.2 su piattaforma .NET 4), con la creazione di un framework javascript personalizzato da usare a se stante o insieme ad ExtJs.
:   Possiedo una conoscenza avanzata del runtime system NodeJs che utilizzo correntemente, della libreria React e della tecnologia basata su Microservices con utilizzo di container Docker. 

:   Nel corso degli anni ho acquisito competenze sui Framework .NET 1.1, 2.0, Crystal Report 10, Crystal Report XI, Crystal Enterprise 10, e del protocollo SMTP. 

:   Utilizzo correntemente gli strumenti Office: Word, Excel, Access, Outlook, Visio ed la piattaforma Google Apps (Gmail, Calendar, Meet, Drive) quale strumento lavorativo di collaborazione.


[ref]: https://github.com/githubuser/superlongprojectname

Corsi e Certificazioni
--------------------------

Binnovation
:   
* 10/2024 - Talend Data Integration / Integration Administration / Cloud Administration 
* 07/2024 - Boomi Administrator 2 - Linux: **Certified Boomi Professional Linux Operational Administrator**
* 06/2024 - Boomi Associate Administration: **Certified Boomi Associate Administrator**
* 02/2024 - Anypoint Platform Development: Production-Ready Integrations - c/o  Salesforce (in inglese)
* 01/2024 - Anypoint Platform Development: Production-Ready Development Practices - c/o  Salesforce (in inglese)
* 12/2023 - Anypoint Platform Development: API Design with RAML - c/o  Salesforce (in inglese)
* 11/2023 - Anypoint Platform Development: DataWeave - c/o  Salesforce (in inglese)
* 08/2023 - Introduzione agli aspetti avanzati di PowerBI
* 03/2023 - Anypoint Platform Development: Fundamentals - c/o  Salesforce (in inglese)
* 12/2022 - gRPC MasterClass Build Modern API and Microservices in Nodejs
* 09/2022 - Microsoft Educator Center - Introduzione al controllo della versione con Git
* 04/2022 - corso 'Certified Kubernetes Application Developer'
* 03/2022 - Mongodb University - M220JS MongoDB for JavaScript Developers
* 03/2022 - Mongodb University - M103 Basic Cluster Administration
* 02/2022 - Mongodb University - M100 MongoDB for SQL Pros
* 01/2022 - Mongodb University - M001 MongoDB Basics
* 06/2021 - Talend data integration course beginner to expert 
* 09/2020 - Stambia Developer & Analytics 
* 04/2020 - Microstrategy - Corso 11.411 Project Architecting
* 08/2019 - Microstrategy - Corso 11.121 Overview of Enterprise Mobility
* 06/2019 - Microstrategy - Corso 11.115 Basics od Project and Object Design
* 06/2019 - Microstrategy - Corso 11.141 Introduction to Documents
* 06/2019 - Microstrategy - Corso 11.112 Introduction to Analytics reporting
* 06/2019 - Microstrategy - Corso 10.111 Overview of Enterprise Analytics
* 04/2019 - Introduzione ad Oracle Data Integrator 

Softquattro
:   
* 04/2018 - Corso introduttivo a SAP LiveOffice e Lumira – c/o Sap Italia 
* 01/2018 - Corso Create Reports with Qlik NPrinting 17 - presso Qlik Education
* 09/2016 - Corso MOC 20463D - Implementing a Data Warehouse with Microsoft Sql Server 2014 – c/o Cegeka
* 08/2015 - Corso introduttivo a Cognos Report Studio v.10 
* 10/2014 - Corso Fondamenti di Project Management – c/o PMProgetti (classroom su 3 incontri)
* 07/2014 - **QlikView 11 System Administrator** (Certification  #QV0119SA)
* 04/2014-Corso introduttivo su Business Objects XI 4.0/SAP Explorer 4.0 
* 24-27 Marzo 2014 – Corso Server Publisher 11.2 c/o QlikTech Italy (classroom 3gg )
* 02/2014 - Corso introduttivo su Informatica Data Quality 9.5.1 c/o Informatica
* 11/2012 - QlikView Server/Publisher  
* 09/2012 - QlikView Designer 1 
* 09/2012 - QlikView Designer 2 
* 09/2012 - QlikView Developer 1 
* 09/2012 - QlikView Developer 2 
* 03/2012 - Corso introduttivo alla tecnologia SSIS (per SqlServer 2005) 
* 12/2008 - Corso introduttivo su Business Objects XI r.2 

Capacità Organizzative
----------------------

-  Nel corso degli anni ho maturato 

    * una buona esperienza nella gestione dei progetti nel rispetto delle tempistiche e delle specifiche di consegna. 
    * ottima capacità organizzativa e ottima propensione al Problem Solving, consolidata in anni di esperienza nel coordinamento di risorse impiegate nella gestione delle attività di AM per il principale cliente in ambito GDO. 
    * forte predisposizione all’apprendimento in autonomia
    * forte predisposizione al prototyping in relazione alle nuove tecnologie esplorate

Personal Skills
---------------

Lingue
:   Italiano (lingua madre)
:   Francese (liv.B1)
:   Inglese (liv.A2)

Interessi:
:   Cerco di tenermi aggiornato costantemente sulle ultime tecnologie HW & SW, sempre alla ricerca di attività stimolanti, seguendo diversi blog e strumenti di aggiornamento, quali

    * [Medium]
    * [InfoQ] 
    * [Tecnology Radar]
    * [Tom's HW]

:   Progetti collaterali

    *   Prototipizzazione di un Ducklake (Data Lakehouse con catalogo su db postgres e dati su bucket server s3/minio) esposto tramite server Gizmosql e connettività Arrow Flight Sql 
    *   Autenticazione ed autorizzazione app basata su JWT
    *   Utilizzo del protocollo gRPC per la comunicazione tra microservizi nodejs
    *   Automazione testing pl/sql con utPlSql
    *   Analisi di un cluster iperconvergente con Proxmox VE
    *   Linguaggio documentale di markdown per GitHub e Mulesoft
    *   Linguaggi di formattazione documenti LaTeX, TeX
    *   Esplorazione del framework Apache Spark in relazione ai DataLakeHouse
    *   Analisi di DuckDB come in-process OLAP RDBMS

[Medium]: https://medium.com/
[InfoQ]: https://infoq.com
[Tecnology Radar]: https://www.thoughtworks.com/radar
[Tom's HW]: https://www.tomshw.it/



----

- Autorizzo il trattamento dei dati personali come da D.Lgs 196 del 30/06/2003 e GDPR n° 679/2016

> <maxmodena@hotmail.com> • +39 349 16 35 304 • \
> Via delle Acacie 1, 20090 Cesano Boscone, Milano

