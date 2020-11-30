# FLUJO DE TRABAJO CON GIT FLOW

#### 1. INSTALACIÓN EN MacOS
```
brew install git
brew install git-flow
```
#### 2. CLONAR UN PROYECTO EXISTENTE

Con SSH (recomendado) ver uso de llave SSH
```
git clone git@gitlab.wiedii.co:namespace/project.git
```

#### 3. INICIALIZAR UN PROYECTO

| Git  | Git Flow |
| - | - |
| **Iniciar repositorio** `git init` | **Iniciar repositorio**  `git flow init -d`|
| **Iniciar rama master**  `git commit --allow-empty -m "Initial commit"`|**Integración con repositorio remoto VACÍO** `git remote add origin git@gitlab.wiedii.co:namespace/project.git`|
|**Creación y cambio a rama develop a partir de master** `git checkout -b develop master` |**Publicar ramas master y develop (solo perfil “Maintainer” en GitLab)** `git push -v --set-upstream origin master develop`
|
|**Integración con repositorio remoto VACÍO** `git remote add origin git@gitlab.wiedii.co:namespace/project.git`| - |
|**Publicar ramas master y develop (solo perfil “Maintainer” en GitLab)** `git push -v --set-upstream origin master develop`| - |
