# LAB-1-Edroukat-Hicham-

Étape 1 — Télécharger Mobexler (OVA) et tracer le téléchargement
1 Télécharger l’OVA
<img width="1147" height="164" alt="image" src="https://github.com/user-attachments/assets/573e786e-d3b4-4e36-a79f-aa189a7a2099" />

Étape 2 — Importer l’OVA dans VirtualBox/VMware
Import VirtualBox
VirtualBox → File → Import Appliance
Sélectionner .ova → Import
Après import : VM → Settings → Network
Adapter 1 : NAT
Adapter 2 : Host-Only Adapter
<img width="1920" height="965" alt="image" src="https://github.com/user-attachments/assets/f8e673bb-2195-4356-9a31-c5491d94bfd2" />

<img width="1189" height="693" alt="image" src="https://github.com/user-attachments/assets/8fd431ec-6c02-455f-9f7c-3b7cb2df5631" />
<img width="1222" height="713" alt="image" src="https://github.com/user-attachments/assets/b1e7d4f5-45f2-474e-9c15-03b975ea1b2f" />

Étape 3 — Premier démarrage + connexion
Démarrer Mobexler.
Login : la doc indique mot de passe mobexler.
<img width="1587" height="1030" alt="image" src="https://github.com/user-attachments/assets/8bf51e6a-50a2-425b-9042-e3552155679d" />
<img width="1612" height="1014" alt="image" src="https://github.com/user-attachments/assets/33838c47-336f-4c31-9210-836db99dbc2e" />

Étape 4 — Vérifier le réseau (tests “santé”)
1 Vérifier IPs
<img width="1433" height="684" alt="image" src="https://github.com/user-attachments/assets/138d54a9-d1e1-4cf8-877e-ff3204c42ea6" />
2 Vérifier route par défaut
<img width="1435" height="760" alt="image" src="https://github.com/user-attachments/assets/ae74d0c6-ea2c-4b2c-8a4f-30c50067a012" />
3 Tester Internet
<img width="1439" height="855" alt="image" src="https://github.com/user-attachments/assets/48f2214f-be6f-430f-bedb-58489faa0961" />

Étape 5 — Créer le snapshot “CLEAN” (baseline)
VM → Snapshots → Take
Nom : CLEAN_BASELINE_TP1
Description : “Import OK, NAT+HostOnly OK, boot OK, prêt ADB”

<img width="1920" height="1004" alt="image" src="https://github.com/user-attachments/assets/a1d1b8f5-5c6b-4529-b8de-d568a05ae483" />
<img width="1920" height="849" alt="image" src="https://github.com/user-attachments/assets/606a4965-6061-48f4-9536-22de3dfcc3e9" />

Étape 6 — Préparer la cible Android (choisir 1 option)
Option A — Smartphone test via USB (recommandé)

<img width="1440" height="971" alt="image" src="https://github.com/user-attachments/assets/6530ffd2-c8e6-4d04-a624-ca7450e731af" />

<img width="1438" height="882" alt="image" src="https://github.com/user-attachments/assets/716a4382-148c-43b2-ab7f-25dbbdf3cae9" />











