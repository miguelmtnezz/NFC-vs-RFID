# NFC vs RFID

## ¿Que es NFC?
*Comunicacion de campo cercano*, es una tecnonologia de comunicacion inalambrica, de corto alcance y alta frecuencia que permite el intercambio de datos entre dispositivos. Todo estandar se encuentra recogido en la ISO 14443.

**Funcionamiento**


NFC se comunica mediante induccion en un campo magnetico, en donde dos antenas de espiral son colocadas dentro de sus respectivos campos cercanos. Trabaja en la banda de los 13,56MHz, haciendo que no se aplique ninguna restriccion y no requiera de licencia para su uso.

Soporta dos modos de funcionamiento:
 - Activo, ambos dispositivos generan su propio campo electromagnetico, que utilizara para transmitir sus datos.
 - Pasivo, solo un dispositivo generara el campo electromagnetico y el otro se aprovecha de la modulacion de la carga para poder transferir los datos.


## ¿Que es RFID?
*Identificacion por radiofrecuencia*, es un sistema de almacenamiento y recuperacion de datos remotos que usa dispositivos *tags* o tarjetas.Trabaja en la banda 125KHz, su proposito es transmitir la entidad de un objeto mediante ondas de radio.

**Funcionamiento**

El modo de funcionamiento de los sistemas RFID es simple. La etiqueta RFID contiene los datos de identificacion unico que se encuentra adherido al objeto, genera una señal de radiofrecuencia con dichos datos. Esta señal puede ser captada con un lector especifico, el cual se encarga de leer la informacion y pasarla en formato digital a la aplicacion especifica que utiliza el RFID666.

La tecnologia RFID consta de la siguientes partes:
- Etiqueta RFID,compuesta por una antena, un tranductor radio y un chip. El proposito de la antena es permitirle al chip, transmitir la informacion contenida. Estas etiquetas a su vez se diciden segun su rol:
  - Solo lectura
  - De lectura y escritura
  - Anticolision
- Lector RFID, compuesto por una antena, un transceptor y un decofdificador. El lector envia periodicamente señales para ver si hay alguna etiqueta en sus inmediaciones. Esta extrae la informacion y se pasa a un subsistema de procesamiento de datos.
- Middleware RFID, proporciona los medios de proceso y almacenamiento de datos.


>_Fuente Wikipedia [NFC](https://es.wikipedia.org/wiki/Comunicaci%C3%B3n_de_campo_cercano) y [RFID](https://es.wikipedia.org/wiki/RFID)
Consultado el 28/09/2022_
---

## HACKING ETICO

Ahora en el siguiente articulo se aplicaran ejemplos de uso y algunos tipicos ataques sobre tarjetas NFC/RFID. Para ello has de tener un dispositivo movil que incluya tecnologia NFC. Y en el accederemos a la Play Store para descargarnos la siguiente aplicacion.

https://play.google.com/store/apps/details?id=de.syss.MifareClassicTool

**MIFARE Classic Tool**

Es una simple aplicacion para leer, escribir y analizar etiquetas NFC/RFID.

