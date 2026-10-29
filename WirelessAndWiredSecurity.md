Network security is extremely important for preventing attacks, unauthorized access, and other issues that could damage networks, devices, and users. Therefore, it is essential to understand security methods—their functions, how they work, examples of them, why and how they improved and their overall importance. Devices connected to a network can exchange information that should not be accessible to unauthorized users, and that is the reason why we have many methods to use. Wireless and wired networks have different security risks, so they use different methods to protect data, control access, and prevent attacks.

Wireless Security

Wireless networks transmit data through radio waves, which means devices within range may be able to detect wireless traffic. Because of this, encryption and authentication are important for protecting a Wi-Fi network.

WEP (Wired Equivalent Privacy) was one of the first security protocols developed for Wi-Fi networks. It uses RC4 encryption to protect transmitted data, but its design has serious weaknesses that allow attackers to recover encryption keys under certain conditions. WEP is considered obsolete and should not be used in modern networks. WEP used an initialization vector (IV) of only 24 bits, which could repeat. This, combined with other weaknesses in the system, provides useful information for cryptographic attacks. For example, if someone captures enough packets from a WEP-protected Wi-Fi network, they may be able to crack its key without knowing the password beforehand.
<img width="552" height="204" alt="image" src="https://github.com/user-attachments/assets/0446ce80-584b-47fb-a940-9c2a4791aa3d" />

WPA (Wi-Fi Protected Access) was introduced to address weaknesses in WEP. The original WPA used TKIP (Temporal Key Integrity Protocol), which improved security without requiring all older hardware to be replaced. However, TKIP also has known weaknesses and is no longer recommended. It dynamically changes encryption keys over time instead of relying on WEP's weak key-handling approach and also make it harder to exploit the weaknesses associated with WEP's repeated IVs and static encryption keys.
<img width="505" height="270" alt="image" src="https://github.com/user-attachments/assets/7025ad8c-ab90-4018-81a2-151c34568074" />


WPA2 introduced stronger security through AES-based CCMP encryption. It is still widely used and provides good protection when configured correctly. In a typical home network, WPA2-Personal uses a shared password that allows authorized devices to connect. WPA2-Enterprise uses an authentication server, commonly RADIUS, to verify individual users or devices instead of relying on a single shared password. CCMP helps detect unauthorized modifications to transmitted packets.

WPA3 is a newer security standard that improves protection against password-guessing attacks. WPA3-Personal uses Simultaneous Authentication of Equals (SAE), which provides stronger protection when users choose passwords that are not particularly complex. WPA3-Enterprise offers additional security options for organizations with more demanding requirements.

It is also important to understand that 802.11 is the IEEE family of standards used for Wi-Fi communication, rather than a single security protocol. Different amendments define wireless communication features, while security mechanisms such as WPA2 and WPA3 protect access and data. For example, IEEE 802.11i introduced security improvements that formed the basis of WPA2.

Other wireless security practices include disabling WPS when it is not needed, changing default router credentials, updating firmware, and creating a separate guest network. MAC address filtering can restrict connections to listed devices, but it should not be treated as strong security because MAC addresses can be copied or spoofed. Hiding the network name (SSID) also does not provide meaningful protection by itself.

Wired Security

Wired networks commonly use Ethernet connections to transfer data between devices, switches, routers, and servers. Since communication travels through physical cables instead of radio waves, an attacker generally needs physical access to the network or access to a connected device or system. However, wired networks are not automatically secure. An unauthorized person who connects a laptop to an available network port may still gain access if proper controls are missing.

One important wired security method is IEEE 802.1X port-based network access control. It allows a switch to check the identity of a user or device before granting network access. A common implementation uses a supplicant on the device, an authenticator such as a managed switch, and an authentication server such as RADIUS. For example, when an employee connects a laptop to an office Ethernet port, the switch can require authentication before allowing the laptop to communicate with internal resources.

VLANs (Virtual Local Area Networks) are also widely used to separate network traffic. A company can place employee computers, servers, printers, and guest devices in different VLANs. This helps limit unnecessary communication between groups, although VLANs alone do not replace firewalls or access-control policies. Routing rules and firewall configurations can determine which VLANs are allowed to communicate.

Access Control Lists (ACLs) can restrict traffic based on information such as source and destination IP addresses, protocols, and ports. For example, a network administrator can configure rules to allow employee computers to reach a file server while preventing guest devices from accessing the same server. Switch port security can also limit which MAC addresses are allowed on a particular port, although this is not a complete defense against spoofing.

Encryption is another important part of wired security. Protocols such as TLS protect application data while it travels between systems, and IPsec can protect traffic at the IP layer. These methods are especially useful when sensitive information crosses networks that cannot be fully trusted. Physical security also matters: switches and routers should be kept in restricted areas, and unused Ethernet ports can be disabled to reduce opportunities for unauthorized connections.

Real-Life Network Example

Consider a small company with an office network containing employee laptops, desktop computers, printers, a file server, and guest Wi-Fi. The wireless network uses WPA3-Personal or WPA2-AES, depending on device compatibility, while the guest network is isolated from internal company resources. The router uses a strong administrator password and receives regular firmware updates.

Employees who connect through Ethernet use managed switches configured with VLANs. Employee computers are placed in one VLAN, servers in another, and guest devices in a separate network. The company can also use 802.1X authentication to verify employee devices before granting access to the internal network. Firewall rules restrict access to the file server so that only the necessary devices and services can communicate with it.

If a visitor connects to the guest Wi-Fi, they can access the internet without being allowed to access company files or internal management interfaces. If an employee connects a laptop to an office Ethernet port, the switch can authenticate the device and assign it the appropriate network access. TLS protects information exchanged with websites and other supported services, even when the underlying connection is wired or wireless.

This example shows that network security does not depend on a single protocol. Wireless encryption, authentication, network segmentation, traffic filtering, software updates, and physical security work together to reduce risk. The correct combination depends on the network's size, the sensitivity of its data, the devices being used, and the level of access each user requires.
