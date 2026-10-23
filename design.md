@"
# Djama — Guide de design

## Lien Figma
https://www.figma.com/file/XXXXX/Djama-Design  *(à remplacer par le vrai lien)*

## Palette de couleurs
- **Vert principal** : `#1F5F4A` (sidebar, bulles envoyées)
- **Terracotta** : `#C8553D` (boutons primaires, accents)
- **Or** : `#E3A72F` (badges, focus, statuts ✓✓)
- **Crème** : `#FAF6EF` (fond de la zone de chat)
- **Encre** : `#26201C` (texte principal)
- **Muted** : `#6F665F` (texte secondaire)

## Typographie
- **Display** : `Bricolage Grotesque` (titres, logo)
- **Body** : `Public Sans` (texte courant)
- **Fallback** : `system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif`

## Composants
- **Avatar** : cercle coloré avec initiales, point vert pour "en ligne"
- **Bulle de message** : coins arrondis asymétriques (coin pointu côté expéditeur)
- **Bouton primaire** : terracotta, texte blanc, hover plus foncé
- **Badge** : or, texte foncé, forme pill

## Thème sombre
- Fond : `#1a1a1a`
- Texte : `#f0f0f0`
- Sidebar : `#143d2f` (vert plus foncé)

## Captures d'écran
*(À ajouter : page de connexion, liste des conversations, fenêtre de chat, profil)*
"@ | Out-File -FilePath "design.md" -Encoding utf8