# Arquitectura Hadoop para Business Intelligence
La siguiente arquitectura describe el flujo de datos desde las **fuentes** hasta la **visualización de KPIs**:
---
## 1. Origen de Datos
- Archivos planos: CSV, XLSX, DBF.  
- Bases de datos relacionales (SQL, Redshift, etc.).  
- Sistemas transaccionales (tickets, clientes, promociones).
---
## 2. Ingesta de Datos
- **Apache NiFi** → ingesta en tiempo real (streaming o batch).  
- **Apache Sqoop** → extracción desde bases de datos hacia HDFS.  
---
## 3. Almacenamiento de Datos (HDFS)
- **Bronze** → datos crudos (raw).  
- **Silver** → datos limpios y transformados.  
- **Gold** → datos listos para consumo analítico.  
---
## 4. Procesamiento de Datos
- **Apache Spark (SQL, Core)** → transformación y métricas.  
- **Spark MLlib** → segmentación y machine learning.  
---
## 5. Monitoreo
- **Apache Ambari** → administración del clúster.  
- **Spark UI** → seguimiento de jobs y rendimiento.  
---
## 6. Visualización
- **Apache Superset** → dashboards analíticos.  
- **Power BI** → reportes ejecutivos y de negocio.  
---
## Flujo General
**Fuentes → Ingesta (NiFi/Sqoop) → HDFS (Bronze/Silver/Gold) → Spark (procesamiento/ML) → Ambari (monitoreo) → Superset/Power BI (visualización)**

