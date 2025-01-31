El **Three-Way Handshake** (apretón de manos en tres pasos) es el proceso que usa **TCP (Transmission Control Protocol)** para establecer una conexión confiable entre un cliente y un servidor antes de transmitir datos.

---

## 🔹 **¿Cómo funciona?**

El proceso consta de **tres pasos** entre el cliente y el servidor:

1️⃣ **SYN (Cliente → Servidor)**

- El cliente envía un **segmento SYN** (synchronize) al servidor para iniciar la conexión.
- Indica que quiere comunicarse y su número de secuencia inicial (**ISN**).

2️⃣ **SYN-ACK (Servidor → Cliente)**

- El servidor recibe el SYN y responde con un **SYN-ACK** (synchronize-acknowledge).
- Confirma que recibió el SYN del cliente y envía su propio número de secuencia.

3️⃣ **ACK (Cliente → Servidor)**

- El cliente recibe el SYN-ACK y responde con un **ACK** (acknowledge).
- Ahora la conexión TCP está establecida y se pueden enviar datos.

---

## 🔹 **Ejemplo en red**

Supongamos que un cliente quiere conectarse a un servidor web:

📌 **Cliente:**

```
SYN → Hola, quiero conectarme (Número de secuencia = 1000)
```

📌 **Servidor:**

```
SYN-ACK → Ok, recibí tu solicitud (Mi número de secuencia = 3000, Confirma el tuyo = 1001)
```

📌 **Cliente:**

```
ACK → Confirmado, podemos empezar a transmitir datos (Tu número + 1 = 3001)
```

---

## 🔹 **Importancia del Three-Way Handshake**

✅ **Garantiza que ambas partes están listas para la comunicación.**  
✅ **Evita conexiones falsas o incompletas.**  
✅ **Permite sincronizar los números de secuencia para la transmisión confiable de datos.**

Este proceso es fundamental en cualquier comunicación TCP, como **navegar por internet, enviar correos o descargar archivos**. 🚀