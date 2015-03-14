# DRAW DB #

| **current version: 0.0.26** |
|:----------------------------|
| last update: 11th May 2010 ~4:40 PM |
| The current version is still the source codes |
| project deprecated, full function is here: http://www.mysql.com/products/workbench/ |

| Pozor chystá se nová verze programu, tentokrát bude zřejmě i kompatibilní s fork-nutým progamem dbdesigner, bude podpora GTK+/QT s jejich autopřepínáním, nová ikona ;) a s čistějším GUI, bohužel od ukládání v SQLite3 asi upustím a použiji zdřejmě jako řešení  xml uložiště. |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

![https://lh5.googleusercontent.com/_cCblnDV9C4o/TdLEJJdOwxI/AAAAAAAAAJ4/n4w0Y95gGmo/Draw%20DB.jpg](https://lh5.googleusercontent.com/_cCblnDV9C4o/TdLEJJdOwxI/AAAAAAAAAJ4/n4w0Y95gGmo/Draw%20DB.jpg)

**svn link na projekt drawdb gambas2:**

`https://drawdb.googlecode.com/svn/gambas2/drawdb/`

**svn link na projekt drawdb gambas3:**

`https://drawdb.googlecode.com/svn/gambas3/drawdb/`


---


## US: ##

fork program DB designer from fabFORCE.net by geniv

main features of the program is generating SQL query for other programming languages
This is a complete program written in Gambas 2

Since the project was halted fabFORCE and its installation on systems like Debian and Ubuntu have been practically impossible, we decided to overwrite the program for own use and actually just look for the maintenance of the session and export the query in SQL.

### Control ###
  * Create the region
  * The region produces a table
  * Table to be established gradually databases and their relationships among themselves
  * Goes to export tables from various SQL queries
  * Can be imported into the region, create SQL queries

### How it works ###
  * Configuration program is stored in {login}/.config/gambas/drawdb.conf
  * Imposed on the region, and the session table is stored in the SQLite3 database which can be anywhere on the disk

### Version ###

#### 0.0.22 ####
##### Correction of errors from 0.0.21 #####
  * When you insert a blank type: Bounds out of
  * Fixed bug when importing database take a wrong type or strange name links placed
  * Fixed saving to a database treatments character bestowed

##### Allowance #####
  * selectbox correction in the Region to readonly

#### 0.0.23 ####
##### Correction of errors from 0.0.22 #####
  * Fix location of the modification detection
  * Fix bug when right-clicking on the session

##### Allowance #####
  * Added option to open the database from a terminal with the -f _name_
  * Added button refresh to redraw the region's current

#### 0.0.24 ####
##### Correction of errors from 0.0.23 #####
  * fix import tables from the create query

##### Allowance #####
  * Adding a number to version information

#### 0.0.25 ####
##### Correction of errors from 0.0.24 #####
  * fix the rendering of column

##### Allowance #####
  * improved design tables

#### 0.0.26 ####
##### Correction of errors from 0.0.25 #####
  * corrected translation
  * fix dependency for sqlite: gambas2-gb-db-sqlite

##### Allowance #####
  * added item last projects

I then like to be my way back to the mail reportnente any errors that can occur there, or possibly the inaccuracies in the translation ;)
English translation was partially translated to: translate.google.com

## CZ: ##

forknuty program DB designer od fabFORCE.net by geniv

hlavni funkce programu je generovani sql dotazu pro jine programovaci jazyky
Tento program je komletne napsany v gambas 2

Jelikoz byl projekt fabFORCE zastaven a jeho instalace na systemy typu Debian a Ubuntu byla prakticky nemozna, rozhodl jsme se tento program prepsat pro vlastni vyuziti a to vlastne jen pro udrzeni vzhledu relaci a export dotazu v sql.

### Ovladani ###
  * vytvori se region
  * do regionu se vytvori tabulka
  * do tabulky se vytvori postupne databaze a jejich relace mezi sebou
  * z tabulek jdou exportovat ruzne sql dotazy
  * do regionu lze importovat sql create dotazy

### Jak to funguje ###
  * konfigurace programu se ukladaji do {login}/.config/gambas/drawdb.conf
  * ukladani regionu, tabulek a relaci se uklada do SQLite3 databaze ktera muze byt kdekoliv na disku

### Verze ###

#### 0.0.22 ####
##### Oprava chyb z 0.0.21 #####
  * při vlozeni prazdneho typu: out of bounds
  * opraveny chyby pri importu databaze pri chybnem typu nebo divne umistenem nazvu
  * opraveno ukladani do databaze, osetrenim nekorektnich znaku

##### Dodelavky #####
  * oprava select boxu v uprave regionu na readonly

#### 0.0.23 ####
##### Oprava chyb z 0.0.22 #####
  * oprava umisteni detekce modifikace
  * oprava chyby pri kliknuti pravym tlacitkem mysi na relaci

##### Dodelavky #####
  * pridana moznost otevirat databaze z terminalu s parametrem -f _nazev_
  * pridano tlacitko refresh na prekresleni platna regionu

#### 0.0.24 ####
##### Oprava chyb z 0.0.23 #####
  * oprava importu tabulky z create dotazu

##### Dodelavky #####
  * pridani cisla verze programu do informace

#### 0.0.25 ####
##### Oprava chyb z 0.0.24 #####
  * oprava vykreslovany typu sloupce

##### Dodelavky #####
  * vylepseny vzhled tabulek

#### 0.0.26 ####
##### Oprava chyb z 0.0.25 #####
  * oprava prekladu
  * oprava zavislosti pro sqlite: gambas2-gb-db-sqlite

##### Dodelavky #####
  * pridana polozka posledni projekty

budu pak rad kdyz me zpatecne na mail reportnente pripadne chyby, ktere se tam muzou vyskytnout a nebo pripadne i nepresnosti v prekladu ;)
anglicky preklad byl castecne prelozen na: translate.google.com