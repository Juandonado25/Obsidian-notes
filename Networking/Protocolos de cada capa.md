El **modelo OSI** (Open Systems Interconnection) tiene **siete capas**, y cada una tiene protocolos específicos. A continuación, se detallan los principales protocolos de cada capa:

---

### 🔹 **Capa 7: Aplicación**

👉 **Proporciona servicios de red a las aplicaciones del usuario.**  
📌 **Protocolos comunes:**

- **HTTP / HTTPS** → Navegación web
- **FTP / SFTP** → Transferencia de archivos
- **SMTP, IMAP, POP3** → Correo electrónico
- **DNS** → Resolución de nombres de dominio
- **SNMP** → Monitoreo de redes
- **Telnet / SSH** → Acceso remoto

---

### 🔹 **Capa 6: Presentación**

👉 **Traduce y encripta los datos para la capa de aplicación.**  
📌 **Protocolos comunes:**

- **SSL / TLS** → Seguridad en la comunicación (HTTPS usa TLS)
- **JPEG, PNG, MP3, MP4** → Codificación de imágenes, audio y video
- **ASCII, EBCDIC, Unicode** → Formatos de texto

---

### 🔹 **Capa 5: Sesión**

👉 **Establece, administra y termina sesiones entre dispositivos.**  
📌 **Protocolos comunes:**

- **NetBIOS** → Comunicación en redes Windows
- **RPC (Remote Procedure Call)** → Llamadas remotas entre procesos
- **SIP (Session Initiation Protocol)** → Control de sesiones VoIP

---

### 🔹 **Capa 4: Transporte**

👉 **Gestiona la entrega de datos, asegurando fiabilidad o velocidad.**  
📌 **Protocolos comunes:**

- **TCP (Transmission Control Protocol)** → Confiable y orientado a conexión
- **UDP (User Datagram Protocol)** → No confiable, pero más rápido
- **SCTP (Stream Control Transmission Protocol)** → Similar a TCP, usado en telecomunicaciones

---

### 🔹 **Capa 3: Red**

👉 **Dirige los paquetes a su destino a través de múltiples redes.**  
📌 **Protocolos comunes:**

- **IP (Internet Protocol)** → Dirección y enrutamiento de paquetes
- **ICMP (Internet Control Message Protocol)** → Diagnóstico (ping)
- **ARP (Address Resolution Protocol)** → Traduce direcciones IP a MAC
- **RIP, OSPF, BGP** → Protocolos de enrutamiento

---

### 🔹 **Capa 2: Enlace de Datos**

👉 **Asegura la transmisión confiable de datos dentro de la misma red.**  
📌 **Protocolos comunes:**

- **Ethernet (IEEE 802.3)** → Conexiones por cable
- **Wi-Fi (IEEE 802.11)** → Conexión inalámbrica
- **PPP (Point-to-Point Protocol)** → Comunicación punto a punto
- **MAC (Media Access Control)** → Control de acceso a la red
- **LLC (Logical Link Control)** → Control lógico de enlace

---

### 🔹 **Capa 1: Física**

👉 **Define los medios físicos de transmisión.**  
📌 **Ejemplos de estándares:**

- **RS-232** → Comunicación en serie
- **DSL, ISDN, T1, E1** → Líneas de transmisión
- **Fibra óptica, Ethernet (cableado), Wi-Fi (radiofrecuencia)** → Medios físicos

---

📌 **Resumen visual:**

```
[7] Aplicación   → HTTP, FTP, DNS, SMTP
[6] Presentación → SSL/TLS, JPEG, Unicode
[5] Sesión       → NetBIOS, SIP, RPC
[4] Transporte   → TCP, UDP, SCTP
[3] Red          → IP, ICMP, ARP, BGP, OSPF
[2] Enlace       → Ethernet, Wi-Fi, MAC, PPP
[1] Física       → RS-232, DSL, Fibra óptica
```