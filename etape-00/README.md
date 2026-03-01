# Étape 0 - configurer IntelliJ et Java

Dans cette étape, nous allons nous assurer que Java 25
est bien installé et configuré dans le projet.

## Configurer Java 25 sur votre projet

> Vous devriez voir ceci
> 
> ![](.img/configurer-sdk/etape-00-settings-project-sdk-ok.png)
> 
> Si c'est le cas, **il n'y a rien à faire**.
> 
> Votre SDK Java 25 **est correctement configuré**.

---

Si aucun SDK Java n'a été détecté, SDK : `<No SDK>`

- SDK : Ouvrir le menu déroulant

![](.img/configurer-sdk/etape-00-project-structure-no-sdk.png)

---

- Cliquer du **"Download JDK"** (Télécharger JDK)

![](.img/configurer-sdk/etape-00-no-sdk-download-sdk.png)

- Ouvrir la liste déroulante "Vendor"
- Sélectionner **"Eclipse Temurin (AdoptOpenJDK HotSpot)"**

![](.img/configurer-sdk/etape-00-sdk-download-sdk-eclipse-temurin-adoptopenjdk-25.png)

---

La fenêtre devrait ressembler à ceci : 

- Cliquer sur **"Download"** (Télécharger)

![](.img/configurer-sdk/etape-00-sdk-download-sdk-click-download.png)

---

Après quelques instants, vous devriez avoir ceci :

![](.img/configurer-sdk/etape-00-settings-project-sdk-ok.png)

---

Confirmer la configuration du projet en cliquant sur **OK**.

![](.img/configurer-sdk/etape-00-file-project-structure-OK.png)

---

Votre projet est désormais **configuré pour Java 25**.

## (Optionnel) Plugins pouvant être désactivés

Certains **plugins** de Intellij peuvent être gourmands en ressources.

Il est possible d'en désactiver certains sans impact majeur sur l'expérience de développement.

Pour activer/désactiver des plugins.

---

**1 - Ouvrir les "Settings"** 

![](.img/desactiver-plugins/etape-00-ouvrir-settings.png)

---

**2 - Se positionner sur "Plugins"**

![img.png](.img/desactiver-plugins/etape-00-se-positionner-sur-settings.png)

---

**3 - Filtrer les plugins "bundled"**

![](.img/desactiver-plugins/etape-00-filtrer-plugins-bundled.png)

---

**4 - Désactiver le plugin "MCP Server"**

- Trouver un plugin nommé "MCP Server"
- Le désactiver en décochant la case

![](.img/desactiver-plugins/etape-00-desactiver-plugin-mcp-server.png)

Quand il est désactivé, il doit **être grisé**.

![](.img/desactiver-plugins/etape-00-plugin-mcp-server-desactive.png)

---

**4 - Désactiver les plugins se basant sur de l'IA locale**



Les plugins basés sur de l'IA peuvent être désactivés
car ils peuvent consommer beaucoup de ressources :

- Full Line Code Completion
- Machine Learning Code Completion
- Machine Learning Find Usages
- Machine Learning in Search Everywhere

![](.img/desactiver-plugins/etape-00-plugins-pouvant-etre-desactives.png)

---

**5 - Valider la configuration en appuyant sur OK**

![](.img/desactiver-plugins/etape-00-valider-modification-plugins.png)

---

**6 - Confirmer s'il est demandé de redémarrer**

En cliquant sur "Restart" (ou "Redémarrer")

![](.img/desactiver-plugins/etape-00-redemarrer-apres-modifie-plugins.png)
