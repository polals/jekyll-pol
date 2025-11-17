---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Pàgina amb Sintaxi Avançada
permalink: /sintaxi-avancada/
---

# Sintaxi Avançada en Markdown :sparkles:

Aquesta pàgina mostra diversos elements de **Markdown avançat** compatibles amb Jekyll.  
Això és especialment útil per enriquir la documentació, posts tècnics o pàgines informatives.

---

## :rocket: Emoji Shortcodes

Pots utilitzar emojis directament amb codis curts:

- :shield: Seguretat
- :computer: Informàtica
- :fire: Alertes
- :tada: Celebració  
- :lock: Protecció

---

## :white_check_mark: Task List

Aquí tens una llista de tasques típica per un projecte de ciberseguretat:

- [x] Escanejar vulnerabilitats
- [ ] Realitzar proves d’intrusió
- [ ] Redactar l’informe final
- [x] Analitzar logs del sistema

---

## :books: Taula informativa

Una taula simple per comparar eines de seguretat:

| Eina          | Funció principal         | Nivell |
|---------------|---------------------------|--------|
| **Nmap**      | Escaneig de ports         | Alt    |
| **Wireshark** | Anàlisi de tràfic         | Mig    |
| **Metasploit**| Explotació de vulnerabilitats | Alt |

---

## :keyboard: Fenced Code Blocks

Un exemple de codi de ciberseguretat:

```bash
# Escaneig de ports bàsic
nmap -sV -Pn 192.168.1.20

# Escaneig de vulnerabilitats amb scripts
nmap --script=vuln 192.168.1.20
