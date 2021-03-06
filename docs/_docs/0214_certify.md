---
title: "Certify for IoT Edge"
permalink: /docs/certify/
excerpt: "Certify for IoT Edge"
variable:
  - platform: windows
    name: Windows
  - platform: macos
    name: macOS
last_modified_at: 2019-07-08
---

## IoT Edge Certification

### General 
Azure IoT Edge Certification program started in June 2018 and there is currently 80 + IoT Edge Certified devices in Device Catalog. Microsoft is certifying against IoT Edge runtime pre-installation and ability to deploy the Edge Modules on the Edge device apart from connectivity to Azure IoT Hub.

## Process
-	Submit Device: Partner submit the device in [Partner Dashboard](https://catalog.azureiotsolutions.com/){:target="_blank"}
-	Prepare the Device: Partner prepare the device and download the Azure IoT Edge Runtime [here](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/iot-edge/how-to-install-iot-edge-linux.md){:target="_blank"}
-	Perform the Test : Partner pick the OS and perform the test mentioned in [AICS](https://github.com/Azure/azure-iot-device-ecosystem/blob/master/AICS/how-to-use-aics-edge.md){:target="_blank"} and submit the logs files generated from AICS.
-	Verify the Logs: IoT Cert Team verify the logs and get started submitted by partner.
-	Certifying Criteria: Device is certified based on the log files generated by AICS test, [get started](https://github.com/Azure/azure-iot-device-ecosystem/tree/master/iotcertification/iotedge/iotedge_get_started_template){:target="_blank"} document shared by partner and results are validated on actual physical device. Partner need to send the Hardware & software manuals explaining about the device connection and get started document.
-	Details guidelines can be found [here](https://github.com/Azure/azure-iot-device-ecosystem/blob/master/iotcertification/iotedge/iotedge_getstarted.md){:target="_blank"}

### Note
-	Partners needs to send the device to Microsoft to validate the product truth to ensure that the Edge runtime components (Edge security manager specifically) are pre-installed. On physical device, we are testing the product truth with the actual hardware

If OEMs have any questions, feel free to direct them to the email alias below:
Azure Certified for IoT [iotcert@microsoft.com](mailto:iotcert@microsoft.com)
