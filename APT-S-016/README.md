**NAME:**  
APT-S-016  
  
**Alias**  
APT-S-016  
   
**Description**:  
 APT-S-016 is a malicious PDF file disguised as an official meeting protocol of Mohammed Dahlan (Palestinian politician, former leader of Fatah) with the Egyptian Intelligence. The document is blurred and contains a paragraph in Arabic that is supposed to lure the victim to click a link and download an Adobe Reader update. Interestingly, the Google Drive link leads to a malicious APK file by the name: com.adobe.reader.apk. When examining the application that was flagged malicious by 15 AV-providers in VirusTotal, we noticed that as part of its functionality, the application forces setting a new device unlock password, deletes call logs/history, monitor outgoing calls and has vast capabilities.
The file is signed using a digital certificate of which the "issuer" and "subject" sections are filled with words in Turkish (For example: CN=Benim ismim - translation: "my name")
  
**References**:  
https://www.joesandbox.com/analysis/84739/0/pdf