<img width="1280" height="640" alt="HPA" src="https://github.com/user-attachments/assets/539cca48-94a5-4978-8ebb-fd03831920c7" />

## Contenido del repositorio
Este repositorio contiene la documentación de análisis y diseño utilizada para implementar el sistema [Hotel Premier](https://github.com/romsreu/Hotel_Premier). Incluye todos los diagramas producidos durante el proceso de diseño, así como el modelo de datos y el script de creación de la base de datos. La implementación final del sistema se basa en esta documentación, con posibles diferencias menores surgidas durante la codificación. Este material sirve como base para revisar, mantener o ampliar el sistema en el futuro.

## **1. Diagrama de entradas y salidas**
Contiene los diagramas de entradas y salidas del sistema, incluyendo:
- Wireframes de pantalla
- Tablas de control por campo
- Tablas de errores y mensajes
- Modelos visuales de pop-ups y reglas de interacción
- Validaciones, máscaras y comportamiento de cada formulario  
  
### **Casos de uso incluidos:**
- **CU-02 | Buscar Huésped**  
- **CU-04 | Reservar Habitación**
- **CU-05 | Mostrar Estado de Habitaciones**
- **CU-07 | Facturar**  
- **CU-09 | Dar Alta de Huésped**  
- **CU-11 | Dar Baja de Huésped**  
- **CU-15 | Ocupar Habitación**  
- **CU-18 | Listar Ingresos**

## **2. Diagrama de clases**
Incluye el diagrama completo de clases del sistema, modela:
- DAOs 
- DTOs
- Gestores 
- Enumeraciones
- Modelo de dominio  
- Relaciones entre capas y entidades  

## **3. Diagramas de secuencia**

### **Diagramas de secuencia incluidos:**
- **CU-02 | Buscar Huésped**  
- **CU-04 | Reservar Habitación**  
- **CU-05 | Mostrar Estado de Habitaciones**  
- **CU-09 | Dar Alta de Huésped**  
- **CU-15 | Ocupar Habitación**  

Cada diagrama muestra el flujo interno de mensajes entre:
- Interfaz gráfica  
- Gestores  
- DAOs  
- Entidades  

Incluye flujos alternativos, validaciones y errores.

## **4. Diagramas de estado**
Contiene los diagramas de estado de entidades centrales del sistema.

### **Diagramas incluidos:**
- **Factura**
- **Reserva**  
- **Estadía**
- **Huesped**
- **Habitación**
- **ResponsableDePago**

Estos diagramas describen el ciclo de vida de cada entidad y las transiciones según eventos del sistema.

## **5. Diagramas de base de datos**
Esta carpeta reúne todos los documentos relacionados con el modelo de datos del sistema.

### Incluye:

- **DER completo del sistema**  
  Representa las entidades principales, sus atributos, claves primarias, claves foráneas y las cardinalidades entre tablas.  
  Es el modelo conceptual que describe la estructura lógica de la base de datos.

- **Diagrama de Tablas**  
  Vista tabular del esquema físico, mostrando todas las columnas de cada tabla, sus tipos de datos, restricciones y relaciones.  
  Permite visualizar de forma directa cómo se implementan las entidades del DER en la base de datos real.

- **Script SQL de creación de la base de datos (DDL)**  
  Archivo SQL que crea todas las tablas, claves primarias, claves foráneas, índices y restricciones necesarias.  
  Este script permite reconstruir, replicar o migrar la base de datos sin necesidad de herramientas adicionales.


