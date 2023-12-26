# IPgeolocator

### Overview:

Developed a Python script to analyze network traffic captured using Wireshark and visualize the geolocation of IP addresses on a Google Map. This project leverages the Scapy library for parsing Wireshark files, the GeoLite2 database for IP geolocation, and Folium for creating interactive maps.

### Project Steps:

1. **Capture Network Traffic:**
    - Utilized Wireshark to capture network traffic and saved it in a pcap file.
2. **Python Script Setup:**
    - Developed a Python script to read the Wireshark file using the Scapy library.
    - Used GeoLite2 City database for IP geolocation.
3. **IP Geolocation Mapping:**
    - Implemented a function to map IP addresses to their geolocations using the GeoLite2 database.
    - Extracted source and destination IP addresses from the captured packets.
4. **Visualization with Folium:**
    - Integrated Folium to create an interactive map.
    - Plotted markers on the map for each geolocated IP address.
5. **Additional Information Display:**
    - Displayed additional information, including IP address, hostname, city, region, country, location coordinates, and organization.
6. **Project Execution:**
    - Executed the Python script with the Wireshark file as input, resulting in an HTML file containing the interactive map.
7. **Map Analysis:**
    - Examined the map to identify the geolocations of IP addresses present in the network traffic.
    - Analyzed patterns, identified locations, and gained insights into the network communication.

### Technologies Used:

- Python
- Scapy
- GeoLite2 City database
- Folium
- Wireshark

### Results:

- Successfully created an interactive map that visualizes the geolocation of IP addresses from the captured network traffic.
- Obtained detailed information about each IP address, enhancing the understanding of network communication.

### **1. Capture Network Traffic:**

- Used Wireshark, a widely-used network protocol analyzer, to capture network traffic.
- Configured Wireshark to capture packets and saved the captured data in a pcap (Packet Capture) file format.
- Ensured that the Wireshark capture included a diverse set of network activities for comprehensive analysis.

### **2. Python Script Setup:**

- Set up a Python development environment to create and run the script.
- Installed necessary Python libraries, including Scapy, GeoLite2, and Folium, using package management tools like pip.
- Created a Python script to read and parse the Wireshark pcap file.

### **3. IP Geolocation Mapping:**

- Utilized Scapy, a powerful library for packet manipulation, to extract relevant information from the Wireshark capture.
- Integrated the GeoLite2 City database to map IP addresses to their corresponding geolocations.
- Developed a function to extract source and destination IP addresses from the captured packets.

### **4. Visualization with Folium:**

- Integrated Folium, a Python library for creating interactive maps, into the project.
- Leveraged Folium's capabilities to create a base map and customize it according to project requirements.
- Implemented markers on the map to represent the geolocated IP addresses.

### **5. Additional Information Display:**

- Enhanced the project by displaying detailed information for each IP address on the map.
- Extracted and presented information such as IP address, hostname, city, region, country, location coordinates, and organization.
- Formatted the displayed information for clarity and user understanding.

### **6. Project Execution:**

- Executed the Python script, providing the Wireshark pcap file as input.
- Monitored the script's execution to ensure it processed the data correctly.
- Validated that the output was saved in the expected format, typically an HTML file containing the interactive map.

### **7. Map Analysis:**

- Examined the generated map to visually analyze the geolocations of IP addresses.
- Identified patterns, clusters, or anomalies in the network traffic.
- Extracted insights into the geographical distribution of communication, potentially revealing geographic concentrations of network activity.

### **8. Technologies Used:**

- Python: Primary programming language for scripting and data manipulation.
- Scapy: Library for packet manipulation and analysis.
- GeoLite2 City database: External database for IP geolocation.
- Folium: Python library for creating interactive maps.
- Wireshark: Network protocol analyzer for capturing and analyzing network traffic.

### **9. Results:**

- Successfully created an interactive map providing a visual representation of IP geolocations from the captured network traffic.
- Extracted valuable information about each IP address, contributing to a comprehensive understanding of network communication.

### **10. Future Enhancements:**

- **Real-time Geolocation Mapping:** Explore capabilities for live network monitoring and real-time mapping.
- **Additional Data Sources:** Investigate the integration of other data sources to enrich information about IP addresses.
- **User-Friendly Features:** Implement customization options and additional features to enhance user experience.

### **11. Skills Demonstrated:**

- **Python Programming:** Demonstrated proficiency in scripting and utilizing Python libraries.
- **Network Traffic Analysis:** Applied knowledge of network protocols and packet analysis.
- **IP Geolocation Mapping:** Leveraged external databases for mapping IP addresses to geographical locations.
- **Data Visualization:** Used Folium to create interactive maps for data visualization.
- **Integration of External Databases:** Successfully integrated GeoLite2 City database for geolocation information.

### **12. Conclusion:**

- This project showcases practical skills in network analysis, data manipulation, and visualization using Python.
- The interactive mapping tool contributes to understanding network communication patterns and can be further enhanced for real-world applications.

### Conclusion:

This project showcases my ability to leverage Python and relevant libraries to analyze and visualize network traffic, providing valuable insights into the geographical distribution of IP addresses. The interactive mapping tool serves as a useful resource for understanding network communication patterns.
