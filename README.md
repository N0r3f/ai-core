# .ai-core - Règles et Configuration pour Systèmes IA

Ce dossier contient les règles et configurations pour les systèmes d'IA travaillant sur ce projet.

## Fichiers

### `documentation-rules.json`

Ce fichier définit les règles de documentation pour le projet. Il spécifie que :

- **Toute documentation doit être dans le dossier `wiki`**
- La structure du wiki doit être respectée
- Un workflow de documentation doit être suivi
- Les standards de documentation doivent être respectés
- La documentation doit être maintenue à jour

## Utilisation

Les systèmes IA doivent consulter ce fichier avant d'ajouter ou de modifier de la documentation pour s'assurer de respecter les règles définies.

## Validation

Pour valider le fichier JSON :

```bash
python3 -m json.tool .ai-core/documentation-rules.json
```

## Mise à jour

Ce fichier doit être mis à jour si les règles de documentation changent.

---

**Dernière mise à jour** : 2025-01-27

