# Konforme

**La facturation électronique sans effort pour les restaurateurs.**

Konforme automatise toute la chaîne de traitement des factures fournisseurs
des petits et moyens restaurants : de la réception à la transmission au
comptable, en passant par la mise en conformité avec la réforme française
de la facture électronique (2026/2027).

## Le problème

Aujourd'hui, les restaurateurs reçoivent leurs factures fournisseurs en PDF
par email et les transfèrent manuellement à leur comptable. Demain, la loi
impose la facture électronique via une plateforme agréée. Deux corvées, une
seule solution.

## Ce que fait Konforme

- 📥 **Capture automatique** des factures (email + OCR pour les PDF, Factur-X
  pour l'électronique)
- 🧾 **Traitement conforme** via une Plateforme de Dématérialisation Partenaire
  (PA/PDP) immatriculée
- 🔀 **Double flux** : électronique (Factur-X) et legacy (OCR sur les anciens PDF)
- 📊 **Structuration** des données (fournisseur, SIREN, montants HT/TVA/TTC,
  échéances…)
- 📤 **Transmission** automatique au comptable + export FEC
- 🔔 **Notification** du restaurateur à chaque facture traitée

## Stack technique

- **Orchestration** : Make
- **Base de données** : Supabase (PostgreSQL)
- **OCR / IA** : Mindee
- **Plateforme agréée (PA/PDP)** : Super PDP (Factur-X)
- **Front / Landing** : hébergé sur Netlify

## Conformité

Konforme s'adosse à une plateforme immatriculée par la DGFiP pour garantir la
conformité à la réforme française de la facture électronique :
- Réception obligatoire depuis le **1er septembre 2026**
- Émission pour les PME/micro-entreprises au **1er septembre 2027**
