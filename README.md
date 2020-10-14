# M2-Workshops
**NB** We did not see the last version of the instructions, and worked according to [this version of the instruction](https://github.com/xblanc33/cdp-td/blob/fddadd904f381fe97cdd8e3f81bcafe5da5f8970/td4_code.md)

## Architecture

Pour répondre à la première question du TD nous avons modifié l'architecture et refactorer le code en nous inspirons de la  _clean architecture_.
Pour cela nous avons:
- un dossier UI: comportant tous les fichiers relatifs à l'interface utilisateur.
- un dossier repository: comportant toutes les implémentations d'un repository. (ici seulement InMemory)
- un dossier domain: comportant le code relatif au dommaine métier de l'application.
  - useCase: rassemble toutes les cas d'utilisation implémenter (chaque classe a une méthode execute)
  - entity: rassemble toutes les classe métier de l'application (ici workshop)
  - ports: rassemnle toutes les interfaces métier qui seront implémenter à l'exterieur du domain
 
 
