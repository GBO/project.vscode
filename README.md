# project.vscode : Exemple de projet C++ simple pour Visual Studio Code

**Pré-requis** : un outil de compilation fonctionnel et disponible.

La tâche de compilation par défaut est définie dans le fichier `.vscode/tasks.json` dans la tâche `Build active file`.

Il est possible de configurer cette tâche, notamment :
* `command` : la commande utilisée pour compiler (ici `g++` qui doit être accessible dans le [PATH](https://fr.wikipedia.org/wiki/Variable_d%27environnement#%3CPATH%3E_pour_l'emplacement_des_ex%C3%A9cutables))
* `args` : les arguments passés au compilateur, et ainsi le fait qu'il compile le fichier courant pour en produire un exécutable en `.exe`.

# Détails des fichiers

* `.vscode/c_cpp_properties.json` : Configure le [plugin VSCode C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
* `.vscode/launch.json` : [Configuration du debugger VSCode](https://code.visualstudio.com/docs/cpp/launch-json-reference)
* `.vscode/tasks.json` : [Configuration des tâches de compilation de VSCode](https://code.visualstudio.com/Docs/editor/tasks)

