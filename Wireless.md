# 📡 Wireless Networking

<br>

**MEANING:**

Consists of a way of communication using RF (Radio Frequency) waves instead of depending on physical cables.

It is also important to acknowledge that LAN, WAN, and MAN describe the scope or geographic area of a network, not whether it uses cables or wireless communication.

A LAN that uses Wi-Fi is called a WLAN (Wireless Local Area Network), while wireless versions of WAN and MAN are called WWAN (Wireless Wide Area Network) and WMAN (Wireless Metropolitan Area Network).

<br>

<img width="451" height="378" alt="WiredXWirelessExample" src="https://github.com/user-attachments/assets/4ce78a8a-e3de-4df4-bcd4-68601b4bb5e9" />

<sup>(A screenshot taken from Arash Deljoo's CCNA course on Udemy - Section 22)</sup>

<br>
<br>

## CONCEPTS AND TERMS

### Access Point (AP)
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/cc6d9f57-9abb-4ea5-b343-10111d01acff" />

An **Access Point (AP)** in a wireless network allows devices to communicate with the network, acting as a transmitter and receiver.

### Independent Basic Service Set (IBSS)

An **Independent Basic Service Set (IBSS)**, also known as ad-hoc, allows devices such as tablets and phones to communicate directly with each other without an Access Point.
It can be used for direct and temporary connections between devices.

### Basic Service Set (BSS)

A **Basic Service Set (BSS)** is the fundamental building block of an IEEE 802.11 wireless local area network (WLAN), commonly known as Wi-Fi.

In a standard infrastructure BSS, a single Access Point (AP) acts as the central coordinator or base station, instead of no Access Point (AP) at all.

### SSID

**SSID (Service Set Identifier)** is basically the name of a Wi-Fi network that users see when they search for available wireless networks.

It identifies the wireless network that devices can connect to, such as `Home_WiFi` or `School_WiFi`.

### BSSID

**BSSID (Basic Service Set Identifier)** is an identifier used to identify a specific BSS.

In most Wi-Fi networks, it is the MAC address of the Access Point's wireless interface.
While the SSID can be the same for multiple Access Points, each BSSID is normally unique, allowing devices to distinguish between different APs.
For example, if a school has several Access Points all using the SSID `School_WiFi`, they can all provide the same wireless network while having different BSSIDs.
This allows a device to identify which specific AP it is currently connected to, even when multiple APs use the same SSID.

**Basic Service Set (BSS)**

A Basic Service Set (BSS) is a group of wireless devices that communicate within a specific 802.11 network area.
In an infrastructure BSS, the devices communicate through a single Access Point (AP). The AP coordinates wireless communication and connects the wireless devices to the network.
Each BSS has its own BSSID, which normally identifies the AP's wireless interface.
For example, if an office has one AP providing the SSID Office_WiFi, the AP and the wireless devices associated with it form a BSS.

**Extended Service Set (ESS)**

An Extended Service Set (ESS) consists of two or more BSSs connected through a Distribution System (DS), allowing them to provide a larger wireless network.

The BSSs can use the same SSID, while each individual BSS has a different BSSID.
For example, a school may have several APs throughout the building. All APs can use the SSID School_WiFi, 
but each AP has a different BSSID. Together, these interconnected BSSs form an ESS, allowing users to move between coverage areas while remaining connected to the same wireless network.

An ESS is commonly used in enterprise networks, schools, offices, hotels, and other large environments where multiple APs are required to provide wider Wi-Fi coverage.

____________________________________________________________________________________________________________________________

Wi-Fi is a wireless networking technology that allows devices to connect to a local area network (LAN) and exchange data without requiring a physical cable connection. It uses radio waves to transmit and receive data between wireless devices and a wireless access point (AP) or wireless router.

Wi-Fi operates primarily within the 2.4 GHz, 5 GHz, and 6 GHz frequency bands, depending on the supported Wi-Fi standard, the device, and the regulatory requirements of the country. Each frequency band has different characteristics in terms of range, interference, and potential data transmission speeds. For example, 2.4 GHz generally provides better coverage over longer distances and through obstacles, while 5 GHz and 6 GHz can offer higher throughput and access to more channels under suitable conditions.

When a device, such as a laptop or smartphone, connects to a Wi-Fi network, it communicates wirelessly with an access point. The access point typically forwards traffic to the wired LAN and, when an internet connection is available, allows devices to access external networks, including the internet.

Wi-Fi is based on the IEEE 802.11 family of standards, which defines how wireless devices communicate at the physical (PHY) and media access control (MAC) layers. Different generations, such as Wi-Fi 4 (802.11n), Wi-Fi 5 (802.11ac), Wi-Fi 6/6E (802.11ax), and Wi-Fi 7 (802.11be), introduce improvements in throughput, efficiency, capacity, and other capabilities.

Wi-Fi networks can be secured using authentication and encryption mechanisms, such as WPA2 and WPA3, to help protect wireless communications against unauthorized access. Network performance depends on several factors, including signal strength, distance from the access point, physical obstacles, radio interference, channel congestion, supported standards, and the number of connected devices.

Although Wi-Fi is commonly used to provide internet access, Wi-Fi and the internet are not the same thing. Wi-Fi provides a wireless connection to a local network, while the internet is a global network of interconnected networks. A Wi-Fi network can operate locally even when its internet connection is unavailable.
