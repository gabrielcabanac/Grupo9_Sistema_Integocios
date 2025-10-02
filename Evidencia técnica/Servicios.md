# Servicios Big Data: HDFS, Hive y Spark

## 🗄️ HDFS (Hadoop Distributed File System)
- Sistema de **almacenamiento distribuido**.  
- Divide los archivos grandes en **bloques** y los reparte en varios servidores.  
- Garantiza **tolerancia a fallos** al guardar copias de los bloques.  
- Permite trabajar con **grandes volúmenes de datos** en paralelo.

---

## 🔍 Hive
- Herramienta para **consultar y analizar datos** en HDFS.  
- Usa un lenguaje similar a SQL, llamado **HiveQL**.  
- Facilita el trabajo a usuarios que no dominan MapReduce.  
- Ideal para **resúmenes, transformaciones y análisis** de datos.

---

## ⚡ Spark
- Motor de **procesamiento en memoria** (más rápido que MapReduce).  
- Permite análisis en **tiempo casi real**.  
- Se utiliza para **procesamiento de datos masivos, machine learning y streaming**.  
- Altamente escalable y eficiente.

---

## 📊 Relación entre ellos
- **HDFS**: almacena los datos.  
- **Hive**: consulta los datos con SQL.  
- **Spark**: procesa y analiza los datos rápidamente.
