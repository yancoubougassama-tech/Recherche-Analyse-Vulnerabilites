# Recherche-Analyse-Vulnerabilites
Ce projet consiste à mettre en pratiques les méthodes de recherche, d’identification et d’analyse de vulnérabilités à partir de bases de données publiques, de scans réseau et d’outils spécialisés. C'est le concept d’Ethical Hacking et Pentesting. Il utilise  des outils comme Nmap et Nessus pour évaluer la sécurité d’une machine vulnérable.
## Objectifs
- Rechercher des vulnérabilités connues dans les bases publiques (CWE, CVE, NVD)
- Identifier les vulnérabilités présentes sur une machine cible (Mestasploitable) après un scan réseau
- Analyser les résultats du scan Nmap et Nikto pour repérer les failles
- Évaluer la criticité des vulnérabilités détectées (CVSS, impact, exploitabilité)
- Utiliser Nessus pour automatiser la détection et générer un rapport
## Technologies
- VMware Workstation Hyperviseur type 2
- Nessus
- Scan Nmap
- Bases publiques (NVD, CWE, CVE Mitre)
## Commandes Principales
- sudo apt upgrade 
- nmap -sV -o "Ip-mestasploitable"/prefixe: pour scanner meta
- ip a: determiner son réseau
