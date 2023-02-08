# MiT_APP_IoT
Chunk code for MiT App Inventor Development
--- 
Development Target (in chunk): 
- [x] MQTT Publish (included in MQTT_1.aia)
- [x] MQTT Subscribe (included in MQTT_1.aia)
- [x] Camera Access (Currently connected to Automate Flow, Extension which support background capture is paid, therefore i try to use the free option) -> (included in Camera_1.aia)
- [x] Access file -> convert to Base64 -> Send to MQTT (included in MQTT_1.aia)
- [ ] Microphone Access
- [ ] GPS Data Access
- [ ] Batery status Access 
- [ ] BARDI control using battery status
- [ ] Add switch animation (currently no animation)
- [ ] 

---
Activity starter set for Automate (Create node for App Start inside the Automate Flow): 
* Action: com.llamalab.automate.intent.action.START_FLOW
* Activity Class: com.llamalab.automate.StartServiceActivity
* Activity Package: com.llamalab.automate
* Data Uri: content://com.llamalab.automate.provider/flows/[Your Flow Number]
** Flow number is defined in the beginning flow description