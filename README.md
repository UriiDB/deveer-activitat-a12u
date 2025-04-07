# Activitat A12U — Dissenya el teu propi repte amb GitHub i Markdown

## Objectius d’aprenentatge

Amb aquesta activitat assoliràs els següents objectius:

- Consolidar els coneixements sobre Git, GitHub i Markdown.
- Aprendre a comunicar conceptes tècnics de forma clara i didàctica.
- Conèixer el fitxer `.gitignore` i aplicar-lo al teu projecte.
- Utilitzar opcions avançades de Markdown com taules, quotes, enllaços i imatges.
- Fer bons commits, ben organitzats i amb missatges descriptius.

---

## Descripció de l'activitat

Simularàs que ets el docent i dissenyaràs una activitat com les que fem a classe. Has de pensar en una activitat **realista**, que pugui fer un company amb el teu mateix nivell. Aquesta activitat ha d'incloure:

1. Objectiu clar.
2. Instruccions detallades.
3. Explicació d’un **nou concepte** relacionat amb Git o Markdown.
4. Exemples pràctics (taules, quotes, imatges, etc.).
5. Format net i estructurat amb Markdown.

---

## Passos detallats

### 1️⃣ Crea el repositori a GitHub

- Nom del repositori: **deveer-activitat-a12u**
- No marquis "Add a README".
- Clica "Create repository".
- Convida l’usuari **joanpardogine** com a col·laborador.

---

### 2️⃣ Clona el repositori al teu ordinador

Obre Visual Studio Code i el terminal Git Bash. Escriu:


1. cd /c/projectes
2. git clone https://github.com/<el-teu-usuari>/deveer-activitat-a12u.git
3. cd deveer-activitat-a12


| Fitxer        | Descripció                       |
|---------------|-----------------------------------|
| `README.md`   | Instruccions de l’activitat       |
| `.gitignore`  | Llista de fitxers a ignorar       |
| `imatge.png`  | Imatge decorativa (opcional)      |

> “La millor manera d’aprendre és ensenyar.” – Albert Einstein

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### 3️⃣ Crea el fitxer `.gitignore`

.gitignore és un fitxer especial utilitzat per Git per ignorar fitxers o carpetes quan fem seguiment dels canvis en un projecte. Això vol dir que, encara que aquests fitxers existeixin al teu ordinador, Git no els tindrà en compte quan facis git add, commit o push.

🔎 Per a què serveix?

Evitar pujar fitxers temporals o innecessaris al repositori.

Mantenir el projecte net i professional.

Evitar conflictes amb configuracions locals (ex: carpetes de l’editor).

💡 Exemple pràctic: Si tens la carpeta .vscode/ dins el projecte, però no vols que altres usuaris vegin la teva configuració personal de VS Code, pots afegir-la al .gitignore.

Crea un fitxer anomenat `.gitignore` dins del teu repositori escrivint:

```bash
nano .gitignore

# Fitxers del sistema
.DS_Store
Thumbs.db

# Fitxers de l’editor
.vscode/
*.code-workspace

# Fitxers temporals
*.log
*.tmp

