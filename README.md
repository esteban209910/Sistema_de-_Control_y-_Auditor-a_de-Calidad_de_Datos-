# Sistema de Control de Calidad de Datos con SSIS


##  Descripción
Este proyecto consiste en el desarrollo de un sistema automatizado para validar, auditar y controlar la calidad de archivos antes de su carga en una base de datos SQL Server.

El enfoque principal es garantizar la **integridad, trazabilidad y control del proceso ETL**, mejorando la confiabilidad de la información.

---

## ⚙️ Tecnologías utilizadas
- SQL Server  
- SQL Server Integration Services (SSIS)  
- T-SQL  
- SQL Server Agent  

---

##  Objetivo
Automatizar la validación y carga de archivos, asegurando la calidad de los datos y el control del proceso.

---

##  Funcionalidades principales

###  Proceso ETL con SSIS
Pipeline que procesa archivos Excel aplicando reglas de negocio:

- ✔ Validación de calidad de datos  
- ✔ Separación de registros válidos e inválidos  
- ✔ Registro de auditoría del proceso  
- ✔ Control del porcentaje de errores  
- ✔ Envío de alertas automáticas en fallos  
- ✔ Automatización mediante SQL Server Agent  

---

### Control de calidad de datos
Implementación de validaciones usando:

- Data Flow  
- Conditional Split  

Permite clasificar los registros en:
- ✅ Válidos  
- ❌ Inválidos  

---

###  Auditoría y automatización
- Registro de métricas de carga  
- Monitoreo del proceso ETL  
- Ejecución automática con SQL Server Agent  

---


## 📈 Resultados
- Mejora en la calidad de los datos  
- Control y trazabilidad del proceso ETL  
- Reducción de errores en la carga de información  
- Automatización completa del flujo de datos  

---

## ✍️ Autor
**Esteban David González Meneses**
