# SolarScale

**Annotation scientifique d'images solaires** — pour astrophotographes solaires.

SolarScale ajoute à vos images du Soleil des annotations à l'échelle, prêtes à publier :

- 🌍 **La Terre à l'échelle**, incrustée à côté du disque solaire
- 📏 **Arcs d'altitude** (50 000 / 100 000 / 150 000 km…) parallèles au limbe,
  pour donner la mesure des protubérances
- 🏷️ **Régions actives NOAA** positionnées automatiquement à la date/heure de la prise de vue
- 📝 **Légende scientifique** : date, échelle, Ø apparent, instrument, filtre
- 🧭 **Calibration d'orientation automatique** sur les images GONG du jour
- 🎨 **Colorisation jaune/orange** des images mono (normales ou en négatif)
- 🎞️ **Mode batch** pour annoter toutes les frames d'une séquence vidéo
  (compatible PIPP : tailles uniformisées, TIFF/PNG…)
- Détection du limbe robuste (halos, vignettage, gros plans Barlow), presets complets,
  16 bits préservés

## Téléchargement

➡️ **[Dernière version — onglet Releases](../../releases/latest)**

Décompressez `SolarScale-win64.zip` où vous voulez, puis lancez `SolarScale/SolarScale.exe`.

**Configuration** : Windows 10/11, 64 bits. Aucune installation, aucun droit administrateur.

> ⚠️ **Windows SmartScreen** : l'application n'est pas encore signée numériquement.
> Au premier lancement, cliquez sur « *Informations complémentaires* » puis
> « *Exécuter quand même* ». Le code est développé de manière privée mais les binaires
> sont compilés automatiquement par GitHub Actions à partir de sources testées
> (130 tests automatisés).

## Formats d'image pris en charge

TIFF (8/16 bits, mono ou RGB), PNG, JPEG — la profondeur de bits d'origine est
toujours préservée à l'export.

## Questions, bugs, suggestions

Ouvrez une **[Issue](../../issues)** sur ce dépôt — retours bienvenus, en français ou en anglais.

---

*Version macOS envisagée. Ce dépôt ne contient que les binaires ; le code source est développé séparément.*
