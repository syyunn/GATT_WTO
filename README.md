
# Auto-generation of GATT_WTO panel report

------

#### Simple Introduction with just 3 Questions

##  - What is this repository for?

###### This repository is designed to develope integrated system for auto-generation of GATT_WTO panel report.


## - What is World Trade Organization?

##### WTO, formely known as GATT till 1995, is an international organiztion that supports the global level of free trade.


## - What is panel report?

##### WTO has its own rulings based on its law, the WTO agreement. We call this ruling WTO panel report.

-------

## System Outline

Our system comprises following three compartments

#### 1. GATT_WTO Crawler
automatically crawls any information from http://www.wto.org

check : https://github.com/syyunn/GATT_WTO_crawler
        
#### 2. GATT_WTO Panel Report Parser

automatically retrieves any relevant part from the given panel report. For instance, if an user queries "I want factual relationship on Korea-Beef Case" then the parser retreives the part exactly

#### 3. GATT_WTO Panel Report generation
       
  automatically generates panel report based on given factual aspect. the system doesn't require you to parse it or to manually design any features. Just type-in the Facutal Aspect into the system. Then the system will generates panel report based on its own artificial legal discretion.

--------

# More in Detail..

### Why do I choose WTO to auto-generate?

##### First, I know WTO rulings. 

##### Secon, WTO rulings are compact. Its main citation of Articles are limited to GATT Article I, III, XI and XX only.

##### Third, WTO rulings are the "case law". It means that its legal disseratations are higly conditional, repetitive and relying on  the past cases and legal logics.
