# LAB-14-Bypass-Root-Detection-sur-Android-Techniques-Dynamiques-avec-Frida-Objection-et-Hooks-Natif

OS: Windows, Microsoft Windows NT 10.0.26200.0
Python: Python 3.14.3
Modèle Android: sdk_gphone64_x86_64 via AVD Pixel_6
Version Android: 16, SDK 36
Architecture: x86_64
Package cible exact: owasp.mstg.uncrackable1
Activité: sg.vantagepoint.uncrackable1.MainActivity
Frida: 17.9.1
ADB device: emulator-5554 device

# Votre OS (Windows/macOS/Linux) et la version de Python

<img width="1098" height="124" alt="image" src="https://github.com/user-attachments/assets/bed04c8f-ca9e-4716-95d9-7e5fefc354d6" />

<img width="169" height="63" alt="image" src="https://github.com/user-attachments/assets/7debf862-dcda-467e-8dce-9552f01e2016" />



# Le modèle d’appareil Android et sa version

<img width="506" height="54" alt="image" src="https://github.com/user-attachments/assets/fb3d776f-12df-4ede-8c93-d7cb85aacda9" />

<img width="589" height="60" alt="image" src="https://github.com/user-attachments/assets/15eb2abe-1261-4611-a6b1-c34632cf41cb" />

<img width="314" height="61" alt="image" src="https://github.com/user-attachments/assets/c91eda09-e11c-4d28-853a-7e83173b678b" />


# Le package exact de l’app cible

<img width="901" height="83" alt="image" src="https://github.com/user-attachments/assets/b8e8673d-63f1-4220-ab02-e5d8689cf1c9" />

# La sortie d’erreur

## frida version 17.9.1 rejette "--no-pause"

<img width="1090" height="97" alt="image" src="https://github.com/user-attachments/assets/cebef94a-0da2-4798-99b7-b95e5b0209b3" />

corrigé en retirant --no-pause

## INSTALL_FAILED_UPDATE_INCOMPATIBLE

corrigé par desinstaller et reinstaller l'apk
