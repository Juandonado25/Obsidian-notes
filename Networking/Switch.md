A switch, similar to a [[Hub]], connect multiple devices in a [[Network]]. However, unlike a hub, a switch sends data only to the specific device it is intended for. It achieves this by analyzing the [[MAC address (Media Access Control Address)]] of connected devices and directing the data to the appropriate port.

### **Additional Details:**

1. **Functionality:**
    
    - A switch creates a virtual connection between the sending and receiving devices, which reduces network congestion and improves efficiency.
    - Switches operate at Layer 2 (Data Link Layer) of the OSI model but can also function at Layer 3 (Network Layer) if they support IP routing (Layer 3 switches).

2. **Comparison with Hubs:**
    
    - **Hub:** Broadcasts data to all devices, leading to potential collisions.
    - **Switch:** Directs data to the specific recipient, reducing unnecessary traffic.

3. **Learning MAC Addresses:**
    
    - A switch builds a MAC address table (or CAM table) by learning the MAC addresses of connected devices. This table is used to determine the destination port for each data packet.

4. **Use Cases:**
    
    - Switches are widely used in modern Ethernet networks for connecting computers, printers, and other devices.