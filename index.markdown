---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Pàgina amb Sintaxi Avançada (Strikethrough)
permalink: /sintaxi-avancada-st/
---

# Sintaxi Avançada en Markdown

Aquesta pàgina mostra diferents elements de **Markdown avançat**, incloent taules, blocs de codi, strikethrough i més.[^intro]

---

## Llista amb Strikethrough

utilitzem text ~~ratllat~~ per destacar elements:

- ~~Seguretat~~
- ~~Informàtica~~
- ~~Alertes~~
- ~~Celebració~~
- ~~Protecció~~

---

## Task List

Llista de tasques típiques en un projecte de ciberseguretat:

- [x] Escanejar vulnerabilitats
- [ ] Realitzar proves d’intrusió
- [ ] Redactar l’informe final
- [x] Analitzar logs del sistema

---

## Taula Informativa

Una taula simple comparant eines de seguretat:

| Eina          | Funció principal              | Nivell |
|---------------|--------------------------------|--------|
| **Nmap**      | Escaneig de ports              | Alt    |
| **Wireshark** | Anàlisi de tràfic de xarxa     | Mig    |
| **Metasploit**| Explotació de vulnerabilitats  | Alt    |

---

## Codi en Fenced Code Blocks

Exemple d'un escaneig amb Nmap:

```bash
# Escaneig de ports
nmap -sV -Pn 192.168.1.20

# Escaneig de vulnerabilitats amb scripts
nmap --script=vuln 192.168.1.20