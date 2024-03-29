


#  iOS Temperature Humidity App

The iOS Temperature Humidity App is a versatile tool designed to monitor temperature and humidity levels remotely using a Raspberry Pi and Azure services. This app provides users with real-time updates on environmental conditions, enabling them to track changes and make informed decisions accordingly.

## Features:

1.  **Real-Time Monitoring:** The app enables users to monitor temperature and humidity levels in real-time from anywhere using their iOS device.
    
2.  **Remote Access:** Utilizing Raspberry Pi and Azure services, the app fetches data from sensors deployed in various locations, providing users with remote access to environmental data.
    
3.  **Customizable Alerts:** Users can set up customizable alerts to receive notifications when temperature or humidity levels exceed predefined thresholds, ensuring timely response to environmental changes.
    
4.  **Historical Data Analysis:** The app stores historical data collected over time, allowing users to analyze trends and patterns in temperature and humidity variations.
    
5.  **User-Friendly Interface:** With an intuitive and user-friendly interface, the app offers easy navigation and seamless interaction, making it accessible to users of all levels of technical proficiency.
    

## How It Works:

1.  **Raspberry Pi Setup:** Deploy sensors to measure temperature and humidity levels in desired locations. Connect the sensors to a Raspberry Pi device.
    
2.  **Azure Integration:** Set up Azure services to collect data from the Raspberry Pi and store it in the cloud securely.
    
3.  **iOS App Development:** Develop an iOS app that communicates with Azure services to fetch real-time data and display it to users.
    
4.  **User Interaction:** Users can launch the app on their iOS devices, view current temperature and humidity readings, set up alerts, and access historical data for analysis.
    
5.  **Continuous Updates:** The app periodically fetches updates from Azure services to ensure that users have access to the latest environmental data.
    

## Technologies Used:

-   **Raspberry Pi:** Raspberry Pi serves as the hardware platform for collecting sensor data and transmitting it to the cloud.
    
-   **Azure Services:** Azure services such as Azure IoT Hub, Azure Functions, and Azure Storage are used to collect, process, and store sensor data securely.
    
-   **iOS Development:** The app is developed using Swift programming language and Xcode IDE, leveraging iOS frameworks such as UIKit and CoreData for building the user interface and managing data.
