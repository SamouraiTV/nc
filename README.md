# Installation de NC (Netcat) pour le docker Kali 

Ce script installe une version binaire statique de Netcat. Utile si l'installation classique pose problème.

## 1. Récupérer l'outil
Assurez-vous d'avoir `wget` (sinon `sudo apt install wget`).

```bash
wget https://raw.githubusercontent.com/SamouraiTV/nc/main/nc64
````
## 2. donner les permission executable
````bash 
chmod +x nc64
````
## 3. deplacer dans le dossier binaire 
````bash 
mv nc64 /usr/local/bin/nc
````
## 4. verifier que sa a bien marcher 
````bash 
nc  -h
````

