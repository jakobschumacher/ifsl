---
title: Cholera
layout: post
author: Jakob Schumacher

fortbildung: fortbildung/Cholera.html
aktionen: aktionen/Cholera.html

basisdaten:
  bild: https://upload.wikimedia.org/wikipedia/commons/f/f6/Vibrio_cholerae.jpg
  bildcredits: https://commons.wikimedia.org/wiki/File:Vibrio_cholerae.jpg
  bildautor: Tom Kirn, Ron Taylor, Louisa Howard - Dartmouth Electron Microscope Facility
  kurzbeschreibung: Cholera ist ein vornehmlich über Trinkwasser übertragener Erreger, der eine starke Dehydratation verursacht. In Deutschland werden nur vereinzelt Fälle nachgewiesen.

inhalte:  
# Erregerdaten
  - id: erregername
    text: Die Cholera wird verursacht die das Bekterium Vibrio cholerae 
    kategorie: erregerdaten
  - id: erregertyp
    text: Der Erreger ist ein Bakterium. 
    kategorie: erregerdaten
  - id: erregergruppen
    text: 
    kategorie: erregerdaten
  - id: toxin
    text: Vibrio cholerae produziert das Cholera-Toxin
    kategorie: erregerdaten
  - id: erregergruppenunterschiede
    text: 
    kategorie: erregerdaten hygkowichtig
  - id: saisonalitaet
    text: 
    kategorie: zeiten
    
# Vorkommen
  - id: vorkommen_deu
    text: 1-2 Fälle werden in Deutschland jährlich gemeldet.
    kategorie: vorkommen
    quellename: Survstat
    quelleurl: https://survstat.rki.de/
  - id: vorkommen_welt
    text: Der Erreger kommt insbesondere in Ländern mit niedrigen Hygienestandards bei Trinkwasser vor.
    kategorie: vorkommen
  - id: reservoir
    text: Der Erreger kommt überall in der Umwelt vor, aber nicht in Tieren 
    kategorie: vorkommen
    quellename: Environmental reservoirs of Vibrio cholerae and their role in cholera
    quelleurl: https://www.ncbi.nlm.nih.gov/pubmed/23765995
      
# Zeiten
  - id: inkubationszeit
    text: Die Inkubationszeit beträgt 12 bis 96 Stunden
    kategorie: zeiten 
    quellename: The incubation period of cholera a systematic review. 
    quelleurl: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3677557/
  - id: inkubationszeit_min
    text: 
    nummer: 0.5
    kategorie: zeiten
  - id: inkubationszeit_max
    text:
    nummer: 4.5
    kategorie: zeiten
  - id: ansteckungszeit_normal
    text: Erkrankte Personen sind eigentlich nicht ansteckend.
    kategorie: zeiten
  - id: ansteckungszeit_lang 
    text: 
    kategorie: zeiten

# Klinik
  - id: symptome
    text: Krankheitszeichen sind Erbrechen und reiswasserartiger Durchfall in großen Mengen.
    kategorie: klinik
  - id: komplikationen
    text: |
      Als Komplikation kann auftreten: Dehydratation
    kategorie: klinik
  - id: krankheitsdauer
    text: 
    kategorie: klinik
  - id: asymptomatik
    text: In etwa 65 von 100 Personen entwickeln keine Krankheitszeichen.
    kategorie: klinik
  - id: letalität
    text: 
    kategorie: klinik

# Übertragungswege
  - id: uebertragungswege
    text: | 
      Der Erreger wird durch Trinkwasser übertragen. 
    kategorie: uebertragungswege hygkowichtig

# Meldung
  - varname: IFSG_6_1_2
  - varname: IFSG_7
  - varname: IFSG_34 

aktionsbausteine:
  - varname: IFSG12
  - varname: GETINFO
  - varname: UEBERMITTLUNG
  - varname: AUSBRUCHSUNTERSUCHUNG
  - varname: UNTERRICHTUNG_GA
  - varname: TV34
  - varname: TV42
  - varname: ESSENAUFREISEN
  
interview:     
  - varname: KRANKHEITSZEICHEN
  - varname: ERKRANKUNGSBEGINN
  - varname: AUSLANDSAUFENTHALT
  - varname: HOSPITALISIERUNG
  - varname: AUSBRUCHSABKLAERUNG
  - varname: KONTAKTIN33
  - varname: IN33EINRICHTUNG
  - varname: IN36EINRICHTUNG
  - varname: LEBENSMITTELARBEIT


    
quellen:
  - name: European center for diesease control (englisch)
    webseite: https://www.ecdc.europa.eu/en/cholera
  - name: Wikipedia-Eintrag
    webseite: https://de.wikipedia.org/wiki/Cholera
  - name: US-Center for diesease control (englisch)
    webseite: https://www.cdc.gov/cholera/
  - name: Pubmed - Sammlung wissenschaftlicher Publikationen (englisch)
    webseite: https://www.ncbi.nlm.nih.gov/pubmed?term=%22Cholera%22%5BMesh%5D
---