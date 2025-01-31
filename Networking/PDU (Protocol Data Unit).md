 **PDU (Protocol Data Unit)** significa **Unidad de Datos del Protocolo** y es el formato específico en que los datos se organizan en cada capa del modelo [[OSI Model]] para ser transmitidos a través de la red.

### 🔹 **PDU en cada capa del modelo OSI**

Cada capa del modelo OSI maneja los datos de manera diferente y les asigna un nombre específico:

| **Capa OSI**                 | **Nombre del PDU**                   | **Descripción**                                                                |
| ---------------------------- | ------------------------------------ | ------------------------------------------------------------------------------ |
| **Capa 7 - Aplicación**      | **Datos**                            | Información generada por el usuario o la aplicación.                           |
| **Capa 6 - Presentación**    | **Datos**                            | Información en formato adecuado para su transmisión.                           |
| **Capa 5 - Sesión**          | **Datos**                            | Información que gestiona sesiones de comunicación.                             |
| **Capa 4 - Transporte**      | **Segmento (TCP) / Datagrama (UDP)** | Se fragmentan los datos y se les añade información para garantizar la entrega. |
| **Capa 3 - Red**             | **Paquete**                          | Se agrega la dirección IP de origen y destino para el enrutamiento.            |
| **Capa 2 - Enlace de datos** | **Trama (Frame)**                    | Se añade la dirección MAC y se prepara para ser transmitido en la red local.   |
| **Capa 1 - Física**          | **Bits**                             | Los datos se convierten en señales eléctricas, ópticas o de radio.             |
![[Pasted image 20250129115839.png]]
---

### 🔹 **Ejemplo de PDU en acción**

Imagina que envías un mensaje por WhatsApp. El proceso de encapsulación de los datos seguiría estos pasos:

1️⃣ **Capa de Aplicación (Datos):** Se genera el mensaje de texto.  
2️⃣ **Capa de Transporte (Segmento o Datagrama):** Se fragmenta el mensaje y se le agregan puertos de origen y destino.  
3️⃣ **Capa de Red (Paquete):** Se añade la dirección IP del remitente y del destinatario.  
4️⃣ **Capa de Enlace de Datos (Trama):** Se incluye la dirección MAC para enviarlo dentro de la red local.  
5️⃣ **Capa Física (Bits):** Se convierte en señales eléctricas o inalámbricas y se envía al destinatario.

💡 **En resumen:** La **PDU** representa los datos en diferentes niveles de la red y cambia de nombre según la capa en la que se encuentre. 🚀