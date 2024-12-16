# Indoor Positioning System (IPS)  

This project implements an **Indoor Positioning System (IPS)** using Wi-Fi fingerprinting and sensor-based detection methods. It is designed to determine an individual's location in indoor environments and distinguish between indoor and outdoor spaces based on environmental data.  

## Features  
### 1. Wi-Fi Fingerprinting  
- **Offline Phase:**  
  - Collect Wi-Fi signal strengths (RSSI) from surrounding access points.  
  - Store the collected data in a database for future comparisons.  

- **Online Phase:**  
  - Compare the current received signal strength values with the stored fingerprint database.  
  - Accurately estimate the user's location based on the matching results.  

### 2. Indoor/Outdoor Detection  
- Utilize environmental sensors and parameters to determine whether the user is indoors or outdoors:  
  - **Light Sensor:** Measure ambient light levels.  
  - **Magnetic Sensor:** Analyze magnetic field strength.  
  - **Satellite Count and Signal:** Assess the number of satellites and the average signal strength received.  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/FS-Hosseini/fingerprint.git
