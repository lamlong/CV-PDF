Les fichiers Adobe PDF sont devenus une norme pour les échanges de documents. Ces fichiers peuvent avoir un poids en octets conséquent notamment en raison de la présence d'images. S'il existe des solutions pour transmettre des fichiers lourds (<a href="https://wetransfer.com/">WeTransfer</a> par ex.) il peut s'avérer judicieux de réduire leur taille. Nous pouvons aussi avoir besoin de modifier les métadatas ou de joindre plusieurs fichiers ensembles. Pour cela nous disposons de nombreuses solutions. Celles que nous allons étudier reposent sur **Ghostscript** (logiciel gratuit) à partir d'un Terminal (bash, zsh, Powershell, etc.) soit à l'aide du code **Python**.

* <a href="#utilisation-dans-le-terminal">Utilisation dans le terminal</a>
    * <a href="#terminal-installation">Installation</a>
        * <a href="#terminal-installation-windows">Windows</a>
        * <a href="http://terminal-installation-macos">MacOS</a>
        * <a href="http://terminal-installation-linux">Linux</a>
    * <a href="#options">Options</a>
    * <a href="#afficher-les-pdf">Afficher un PDF</a>
    * <a href="#obtenir-des-informations">Obtenir des informations</a>
    * <a href="#modifier-les-metadatas">Modifier les métadatas</a>
    * <a href="#deverrouiller-un-pdf">Déverrouiller à l'ouverture</a>
    * <a href="#proteger">Protéger le document</a> 
    * <a href="#joindre-plusieurs-fichiers">Joindre plusieurs fichiers</a>
    * <a href="#convertir-en-pdf-A">Convertir en PDF/A</a>
    * <a href="#orientation">Orientation</a>
    * <a href="#redimensionnement">Redimensionnement</a>
    * <a href="#reduction-de-la-taille-des-documents">Réduction de la taille des documents</a>
        * <a href="#profile-distiller">Profile Distiller</a>
        * <a href="#niveaux-de-gris">Niveaux de gris</a>
        * <a href="#noir-et-blanc">Noir et blanc</a>
    * <a href="#ocr">Reconnaissance de caractères</a>
* <a href="#automatisation">Automatisation</a>
    * <a href="#avec-le-terminal">Avec le Terminal</a>
        * <a href="#automatisation-powershell">Windows Powershell</a>
        * <a href="#automatisation-shell-mac">Shell MacOS/Linux</a>
    * <a href="#automatisation-python">Avec Python</a>
* <a href="#compiler-les-sources">Compiler les sources</a>
    * <a href="#archive-tar">Archive TAR</a>
    * <a href="#depot-distant">Dépôt distant</a>
    * <a href="#ms-visual-studio-code-2022">Windows</a>

<h2 id="utilisation-dans-le-terminal">Utilisation dans le terminal</h2>

Nous allons commencer par installer **Ghostscript** avant de voir les différents usages.

<h3 id="terminal-installation">Installation</h3>

<h4 id="terminal-installation-windows">Windows</h4>
