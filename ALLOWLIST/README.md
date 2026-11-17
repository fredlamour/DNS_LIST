# ALLOWLIST
Listes de domaines autorises (abonnement Pi-hole, type allowlist).

- `allow-default.txt` : 44 domaines exacts autorises pour le groupe Default.
- `allow-microsoft-telemetrie.txt` : telemetrie Microsoft Office (groupes Default + Enfants).
- `allow-enfants-test.txt` : test Family Safety (groupe Enfants), a garder ou retirer apres le bilan du 23/11/2026.

Limite Pi-hole : une liste d'autorisation ne gere que des domaines exacts. Le format `||domaine^` (sous-domaines compris) n'y est pas pris en compte ; les autorisations avec sous-domaines restent donc des regex dans le menu Domaines.
