Import noderes.json into Node-RED.

Required Files (must re-generate youself on AWS IoT Management Console)
1. device certificate
2. private key
3. root CA

Required Device (ESP-EYE)
Refer to https://github.com/beetlskills/beetlskills/aws

Required MQTT Broker (AWS-IoT Core)
Refer to https://github.com/beetlskills/beetlskills/aws


Setting up the Node-RED Flow
1. Click on MQTT In node. Click on Server. Click on Use TLS.
2. Specify the FULL local path of the three required files there. Then click Update and Done.
3. Deploy the flow. 
4. Run the ESP-EYE. Press the side tactile button. THe count will appear on the Node-RED dashboard.