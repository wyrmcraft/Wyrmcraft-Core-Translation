# Guide de Contribution

Merci de contribuer aux traductions du serveur Wyrmcraft !

## 🎯 Méthodes de contribution

### Via Pull Request
1. Fork le dépôt
2. Créez/modifiez un fichier JSON dans `/lang`
3. Nommage : `langue_region.json` (ex: `de_de.json`, `ja_jp.json`)
4. Validez votre JSON (utilisez un validateur en ligne)
5. Créez votre Pull Request

## 📝 Règles de traduction

- **Format JSON strict** : Vérifiez la syntaxe
- **Clés identiques** : Ne modifiez pas les clés, seulement les valeurs
- **Variables préservées** : Gardez `<joueur>`, `[Tier I]`, etc. tels quels
- **Cohérence** : Utilisez le même ton et vocabulaire
- **Contexte** : Les traductions concernent un serveur Minecraft RPG

## 🔍 Exemple

```json
{
    "serveur_tpa_demande_envoyee": "Demande de téléportation envoyée à",
    "serveur_pnj_1_titre": "Marchande de chasse"
}
```

✅ Bon : Traduction naturelle et contextuelle  
❌ Mauvais : Traduction mot-à-mot ou clés modifiées

## ⚡ Validation

Avant de soumettre, vérifiez que votre JSON est valide avec un outil comme [JSONLint](https://jsonlint.com/).

---

Des questions ? Ouvrez une issue sur GitHub.