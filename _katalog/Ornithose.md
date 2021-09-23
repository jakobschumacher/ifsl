---
title: Ornithose
layout: post
fortbildung: fortbildung/Ornithose.html
aktionen: aktionen/Ornithose.html

author: Jakob Schumacher

basisdaten:
  bild: https://upload.wikimedia.org/wikipedia/commons/0/00/Chlamydophila_psittaci_FA_stain.jpg
  bildcredits: https://commons.wikimedia.org/wiki/File:Chlamydophila_psittaci_FA_stain.jpg
  bildautor: CDC/Dr. Vester Lewis
  kurzbeschreibung: Ornithose ist eine Zoonose, die grippeähnliche Symptome verursacht. Der Erreger ist üblicherweise in Vögeln zu finden. 

inhalte:  
# Erregerdaten
  - id: erregername
    text: Die Infektionskrankheit Ornithose wird durch den Erreger Chlamydophila psittaci hervorgerufen. 
    kategorie: erregerdaten
  - id: erregertyp
    text: Der Erreger ist ein Bakterium. 
    kategorie: erregerdaten
  - id: erregergruppen
    text: Chlamydophila psittaci wird in Serotypen unterteilt
    quellename: RKI-Ratgeber 
    kategorie: erregerdaten
  - id: toxine
    text: 
    kategorie: erregerdaten
  - id: erregergruppenunterschiede
    text: 
    kategorie: erregerdaten
    
# Vorkommen
  - id: vorkommen_deu
    text: Ungefähr 10 Fälle werden in Deutschland gemeldet.
    kategorie: vorkommen
    quellename: Survstat
    quelleurl: https://survstat.rki.de/
  - id: vorkommen_welt
    text: Der Erreger kommt weltweit vor.
    kategorie: vorkommen
  - id: reservoir
    text: Der Erreger kommt insbesondere in Papageienvögeln vor. Auch Enten, Truthühner und Tauben sind eine wichtige Infektionsquelle. Andere Vogelarten und Säugetiere können ebenfalls betroffen sein.
    kategorie: vorkommen
    quellename: RKI Ratgeber
  - id: umweltresistenz
    text: Der Erreger kann bis zu 4 Wochen infektiös bleiben
    kategorie: vorkommen 
    quellename: RKI Ratgeber 

    
# Zeiten
  - id: inkubationszeit
    text: Eine Inkubationszeit beträgt im Regelfall 1 bis 4 Wochen
    kategorie: zeiten
  - id: inkubationszeit_min
    text: 
    nummer: 7
    kategorie: zeiten
  - id: inkubationszeit_max
    text:
    kategorie: zeiten
    nummer: 28
  - id: ansteckungszeit_normal
    text: Menschen sind üblicherweise nicht ansteckend.
    kategorie: zeiten hygkowichtig
  - id: ansteckungszeit_lang 
    text: 
    kategorie: zeiten
    quellename: RKI Ratgeber
  - id: saisonalitaet
    text: 
    quelleurl: https://www.survstat.rki.de
    kategorie: zeiten

# Übertragungswege
  - id: uebertragungswege
    text: | 
      Der Erreger wird von den Vögeln über die Federn, Exkremente und respiratorischen Sekreten übertragen. Die Übertragung erfolgt aerogen. Eine Übertragung von Mensch zu Mensch ist äußert unwahrscheinlich. 
    kategorie: uebertragungswege 
    quellename: RKI Ratgeber
    

# Klinik
  - id: symptome
    text: |
      Typische Krankheitszeichen sind Zeichen eines grippalen Infekts: hohes Fieber, Muskelschmerzen, uneindeutige Hauterscheinungen. Im weiteren Verlauf kann ein Lungenentzündung entstehen. 
    kategorie: klinik
  - id: komplikationen
    text: Als Komplikation kann es zu einer Entzündung verschiedener Organe kommen, zum Beispiel zu einer Herzklappenentzündung oder Herzmuskelentzündung.
    kategorie: klinik
  - id: krankheitsdauer
    text: 
    kategorie: klinik
  - id: asymptomatik
    text: 
    kategorie: klinik
  - id: letalität
    text: 
    kategorie: klinik

# Meldung
  - varname: IFSG_7

aktionsbausteine:
  - varname: GETINFO
  - varname: UEBERMITTLUNG
  - varname: AUSBRUCHSUNTERSUCHUNG
  - varname: UNTERRICHTUNG_GA
  - varname: UNTERRICHTUNG_VET

interview:     
  - varname: KRANKHEITSZEICHEN
  - varname: ERKRANKUNGSBEGINN
  - varname: AUSBRUCHSABKLAERUNG
  - varname: HOSPITALISIERUNG
  - question: Waren Sie 1-4 Wochen vor der Erkrankung im Kontakt oder in der Nähe von Vögeln
    comment: Wenn dies der Fall ist, sollte eine Meldung an das zuständige Veterinäramt erfolgen. 
    kategorie: abklaerung
  
quellen:
  - name: Ratgeber des Robert Koch-Instituts
    webseite: https://www.rki.de/DE/Content/Infekt/EpidBull/Merkblaetter/Ratgeber_Chlamydiosen_Teil2.html
  - name: Wikipedia-Eintrag
    webseite: https://de.wikipedia.org/wiki/Ornithose
  - name: US-Center for diesease control (englisch)
    webseite: https://www.cdc.gov/pneumonia/atypical/psittacosis/
  - name: Public health england (englisch)
    webseite: https://www.gov.uk/guidance/psittacosis
  - name: Pubmed - Sammlung wissenschaftlicher Publikationen (englisch)
    webseite: https://www.ncbi.nlm.nih.gov/pubmed?term=%22Psittacosis%22%5BMesh%5D
---
