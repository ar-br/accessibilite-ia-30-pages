# Accessibilité — Expérimental : 30 pages générées par 3 IA

Exercice : faire générer la même page web (menu de navigation + burger, formulaire de contact, message de confirmation dynamique) par **Gemini**, **ChatGPT** et **Claude**, avec deux prompts :

- **« bonnes pratiques »** : page accessible (labels reliés, `fieldset`/`legend`, vrais boutons et liens, ARIA corrects, focus visible, navigation au clavier) ;
- **« mauvaises pratiques »** : page qui applique mal ou pas du tout les règles d'accessibilité.

Chaque prompt a été lancé **5 fois par IA**, dans une conversation neuve à chaque fois.

## Fichiers

Nom des fichiers : `ia-prompt-numéro.html` (ex. `claude-mauvais-3.html` = Claude, prompt « mauvaises pratiques », génération 3).

| IA | Bonnes pratiques | Mauvaises pratiques |
|---|---|---|
| Gemini | `gemini-bon-1.html` à `gemini-bon-5.html` | `gemini-mauvais-2.html` à `gemini-mauvais-5.html` |
| ChatGPT | `chatgpt-bon-1.html` à `chatgpt-bon-5.html` | `chatgpt-mauvais-2.html` à `chatgpt-mauvais-5.html` |
| Claude | `claude-bon-1.html` à `claude-bon-5.html` | `claude-mauvais-1.html` à `claude-mauvais-5.html` |

Remarques :
- `gemini-mauvais-1.html` et `chatgpt-mauvais-1.html` sont à ajouter.
- `gemini-mauvais-3.html` est incomplet : le début du code n'a pas été copié depuis la conversation.

Pour voir une page : ouvrir le fichier, puis cliquer sur **Raw** ou le télécharger et l'ouvrir dans un navigateur.

L'analyse complète (tableaux d'homogénéité, captures des conversations, choix argumentés) est sur HackMD.
