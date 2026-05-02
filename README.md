# TP3 – Mini Scanner (Kali, Python, nmap, Git)

## Prérequis

- Kali Linux avec Python 3 installé
- nmap installé :
  bash
  sudo apt install nmap
  

## Lancement du script

bash
python3 tp3_kali_scanner.py


## Options du menu


1) Scan rapide: Scanne les 100 ports les plus courants
2) Détection services: Détecte les services en cours
3) Scan personnalisé: Tu saisis tes propres options nmap
4) Quitter: Ferme le programme

Note: La seule cible autorisée est `127.0.0.1` (localhost).

## Rapports

Les rapports sont générés automatiquement dans le dossier "reports" avec un nom horodaté, par exemple :

reports/top100_20251112_213000.txt


## Structure du dépôt

tp3-mini-scanner/
├─ tp3_kali_scanner.py
├─ README.md
├─ GIT_PROOFS.txt
└─ reports/


## Mentions éthiques

- Scanner uniquement `127.0.0.1` (localhost).
- Ne jamais scanner des réseaux publics ou non autorisés.
- Ce projet est à visée pédagogique uniquement.
