# FLUJO DE TRABAJO CON GIT FLOW

**Tabla de Contenido**

[TOCM]

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

#### 3. NICIALIZAR UN PROYECTO

| Git  | Git Flow |
| - | - |
| **Iniciar repositorio**  `git init` | **Iniciar repositorio**  `git flow init -d`|
| **Iniciar rama master**  `git commit --allow-empty -m "Initial commit"` | **Integración con repositorio remoto VACÍO**  `git remote add origin git@gitlab.wiedii.co:namespace/project.gi`|