# DCC Quiz Preparation (Cisco)

## Wireless LAN

### Using a Wireless Router
1. Open a PC, go to the **Physical** tab, turn off the PC, and replace the module to support wireless if necessary. Then, turn it back on. If you see dashed lines, the device is connected.
2. Go to the router's **Config** menu, navigate to **Wireless**, and:
   - Set the **SSID** as specified in the quiz.
   - Select **WPA2-PSK** for authentication (if required in the quiz).
   - Enter the **password** as given in the quiz.
3. In the **GUI Configuration** section, modify:
   - **Router IP**
   - **Start IP**
   - **Maximum users**
   	 *(Follow the quiz instructions for these values.)*
4. On the PC:
   - Go to **Config** → **Wireless**.
   - Set the **SSID** and **password** to match the router settings.
5. In **Config**, change **DHCP → Static → DHCP** to request an IP address.

### Using an Access Point & Switch *(Likely to be in the quiz!)*
1. Open the **Access Point**, go to **Config**, and select the **Port (usually 1 or 0)**.
2. Set:
   - **SSID** as per the quiz instructions.
   - **Authentication to WPA2-PSK**.
   - **Password** as given in the quiz.
3. For devices connecting to the Access Point:
   - Assign a **Static IP** as specified in the label near the device.
4. Follow any additional rules given in the quiz!

## DHCP Server Configuration

1. Open the **DHCP Server**, then:
   - Assign an IP in the **Desktop** section.
   - If connecting multiple divisions, configure each separately based on their respective port (e.g., Finance on **FastEthernet0** → Set **FastEthernet0 IP** as labeled on the switch connection).
2. In the **Services** tab, go to **DHCP**:
   - Select the correct **interface** (e.g., Finance Division → **FastEthernet0**).
   - Enter the **Default Gateway**, **Start IP**, **Subnet Mask**, and **Maximum Users**.
   - Turn **DHCP On** by clicking the toggle.
   - Repeat for other divisions on their respective ports.
3. On each PC:
   - Change **DHCP → Static → DHCP** to request an IP from the server.

---

✅ **Study Tip:** Carefully read the quiz instructions and check labels near devices to ensure correct configuration! also it could be /25 on the DHCP server!

📌 **Hall yeah Hall yeah!** 🚀
