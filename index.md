# Pràctica 1: Sistemes de control de versions

## 1. Introducció teòrica

### Què és Git
Git és un sistema de control de versions distribuït que registra els canvis fets en els fitxers d'un projecte. Permet treballar en equip, tornar a versions anteriors i desenvolupar en paral·lel amb branques.

### Què és Git Flow
Git Flow és una metodologia de ramificació amb aquestes branques:
- **main**: codi estable en producció, amb les versions etiquetades.
- **develop**: integració del desenvolupament.
- **feature/\***: una branca per a cada funcionalitat nova.
- **release/\***: preparació d'una versió.
- **hotfix/\***: correccions urgents sobre producció.

### Per què la utilitzem
El projecte té 3 desenvolupadors i diverses seccions independents. Git Flow evita conflictes, manté `main` estable i deixa un historial ordenat.

## 2. Procés realitzat

### 2.1 Usuari 1: creació del repositori i estructura inicial
Descripció i comandes...

![Creació del repositori](img/01-crear-repo.png)

### 2.2 Usuari 2: features contingutHTML i atributsHTML
![Feature contingutHTML](img/03-feature-contingut.png)
![Feature atributsHTML](img/04-feature-atributs.png)

### 2.3 Usuari 3: feature estilsCSS i release v1.0
![Feature estilsCSS](img/05-feature-estils.png)
![Release v1.0](img/06-release.png)

### 2.4 Usuari 1: hotfix milloresV_1_0
![Hotfix](img/07-hotfix.png)

### 2.5 Resultat final
![Graf final](img/08-log-final.png)
