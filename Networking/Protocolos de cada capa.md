El [[OSI Model]] (Open Systems Interconnection) tiene **siete capas**, y cada una tiene protocolos específicos. A continuación, se detallan los principales protocolos de cada capa:

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

**Explicación breve pero detallada** de cada protocolo mencionado en cada capa del **modelo OSI**.

---

## 🔹 **Capa 7 - Aplicación**

Proporciona **servicios directos a las aplicaciones** del usuario.

- **HTTP (HyperText Transfer Protocol)** → Protocolo de navegación web que permite la transferencia de páginas web.
- **HTTPS (HTTP Secure)** → Versión segura de HTTP con cifrado TLS/SSL.
- **FTP (File Transfer Protocol)** → Permite transferir archivos entre clientes y servidores.
- **SFTP (Secure File Transfer Protocol)** → Variante de FTP con cifrado SSH para mayor seguridad.
- **SMTP (Simple Mail Transfer Protocol)** → Se usa para enviar correos electrónicos.
- **IMAP (Internet Message Access Protocol)** → Permite acceder a correos electrónicos en el servidor sin descargarlos.
- **POP3 (Post Office Protocol v3)** → Descarga correos desde el servidor a un dispositivo local.
- **DNS (Domain Name System)** → Traduce nombres de dominio (ej. google.com) a direcciones IP.
- **SNMP (Simple Network Management Protocol)** → Permite monitorear y gestionar dispositivos de red.
- **Telnet** → Permite acceso remoto a dispositivos, sin cifrado.
- **SSH (Secure Shell)** → Acceso remoto seguro mediante cifrado.

---

## 🔹 **Capa 6 - Presentación**

Se encarga de **formatear, cifrar y comprimir los datos**.

- **SSL (Secure Sockets Layer) / TLS (Transport Layer Security)** → Cifran la comunicación en redes (TLS reemplazó a SSL).
- **JPEG, PNG, MP3, MP4** → Formatos de compresión y codificación de imágenes, audio y video.
- **ASCII, EBCDIC, Unicode** → Estándares de codificación de texto para compatibilidad entre sistemas.

---

## 🔹 **Capa 5 - Sesión**

Administra **sesiones entre dispositivos**.

- **NetBIOS (Network Basic Input/Output System)** → Permite comunicación en redes Windows.
- **RPC (Remote Procedure Call)** → Permite que un programa ejecute procedimientos en otro sistema remoto.
- **SIP (Session Initiation Protocol)** → Establece y gestiona sesiones de VoIP (llamadas de voz por internet).

---

## 🔹 **Capa 4 - Transporte**

Garantiza **la entrega de datos de extremo a extremo**.

- **TCP (Transmission Control Protocol)** → Protocolo confiable, orientado a conexión, con control de errores y reenvío de paquetes.
- **UDP (User Datagram Protocol)** → No confiable, sin reenvío de paquetes perdidos, pero más rápido. Usado en streaming y VoIP.
- **SCTP (Stream Control Transmission Protocol)** → Combina características de TCP y UDP, usado en telecomunicaciones.

---

## 🔹 **Capa 3 - Red**

Maneja **el direccionamiento y enrutamiento de datos**.

- **IP (Internet Protocol - IPv4 / IPv6)** → Direccionamiento y enrutamiento de paquetes en redes.
- **ICMP (Internet Control Message Protocol)** → Diagnóstico de red (usado en **ping** para comprobar conectividad).
- **ARP (Address Resolution Protocol)** → Traduce direcciones IP a direcciones MAC en una red local.
- **RIP (Routing Information Protocol)** → Protocolo de enrutamiento basado en distancia (hops).
- **OSPF (Open Shortest Path First)** → Protocolo de enrutamiento basado en el menor costo de ruta.
- **BGP (Border Gateway Protocol)** → Protocolo de enrutamiento entre redes grandes como internet.

---

## 🔹 **Capa 2 - Enlace de Datos**

Administra **las conexiones dentro de una red local**.

- **Ethernet (IEEE 802.3)** → Protocolo para redes cableadas.
- **Wi-Fi (IEEE 802.11)** → Protocolo de redes inalámbricas.
- **PPP (Point-to-Point Protocol)** → Conexión punto a punto en redes WAN.
- **MAC (Media Access Control)** → Control de acceso al medio en redes locales.
- **LLC (Logical Link Control)** → Control lógico de enlace para sincronización y control de errores.

---

## 🔹 **Capa 1 - Física**

Define **los medios físicos y las señales de transmisión**.

- **RS-232** → Comunicación en serie, usada en puertos COM.
- **DSL (Digital Subscriber Line)** → Tecnología de transmisión de datos sobre líneas telefónicas.
- **ISDN (Integrated Services Digital Network)** → Red digital para voz y datos.
- **T1 / E1** → Líneas de telecomunicaciones de alta velocidad.
- **Fibra óptica** → Medio de transmisión de datos con luz en lugar de electricidad.
- **Wi-Fi (radiofrecuencia)** → Transmisión inalámbrica de datos.

---

📌 **Resumen rápido**

- **Capa 7 - Aplicación** → Servicios para el usuario (HTTP, FTP, DNS, SMTP).
- **Capa 6 - Presentación** → Cifrado y compresión (TLS, JPEG, Unicode).
- **Capa 5 - Sesión** → Gestión de sesiones (NetBIOS, SIP, RPC).
- **Capa 4 - Transporte** → Control de datos (TCP, UDP, SCTP).
- **Capa 3 - Red** → Direccionamiento y enrutamiento (IP, ICMP, BGP).
- **Capa 2 - Enlace de Datos** → Redes locales (Ethernet, Wi-Fi, MAC).
- **Capa 1 - Física** → Medios físicos (DSL, fibra óptica, Wi-Fi).

