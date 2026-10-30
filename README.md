# ADF-Research-2026 — Flash Recherche, Congrès ADF 2026

Carte interactive des connexions entre les séances avec temps recherche (Flash Recherche et apparentés) du Congrès ADF 2026 (Paris, 24-28 novembre 2026).

**Voir la carte : https://raphaelrichertg-png.github.io/ADF-Research-2026/**

## Principe

Chaque séance du programme comportant un temps recherche (flash recherche identifié, temps recherche embarqué dans une séance clinique, ou chercheur invité) est reliée à ses concepts fédérateurs. Le graphe est bipartite : intervenants (ronds, code de séance) — concepts (losanges ; taille = nombre de connexions ; doré = fil rouge).

Fil rouge proposé : faire juste plutôt que faire plus — bon diagnostic, décision fondée sur les preuves, intervention proportionnée qui préserve les tissus.

## Méthode

1. Extraction des résumés de séance (Quintessence du Congrès ADF 2026) et identification des temps recherche.
2. Pour chaque intervenant : profil PubMed (publications récentes, PMID, DOI) et laboratoire d'appui.
3. Conceptualisation croisée : les poids des liens combinent l'importance du concept dans le texte de la séance et l'ancrage du chercheur (similarité séance/publications).
4. Clustering en trois pôles : Biologie/Implant — Anomalies du développement/Diagnostic — Numérique/Matériaux.

## Fichiers

- `index.html` : la carte interactive (autonome, sans dépendance).

## Sources

- Quintessence du Congrès ADF 2026 (programme scientifique).
- PubMed (NCBI) pour les profils de publication des intervenants.

Auteur : Raphaël Richert — responsable Recherche/Innovation, Comité scientifique Congrès ADF 2026.
