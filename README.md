# Progreso y Proyectos del Bootcamp JSCamp InfoJobs 🚀

Este repositorio está dedicado a documentar mi progreso y mis proyectos a lo largo del **JSCamp InfoJobs**, el bootcamp de **midudev**.

---

## 📺 La Plataforma

**[JSCamp.dev](https://jscamp.dev)**, la plataforma donde se imparte el bootcamp.

## 👨‍💻 Instructor

**[midudev](https://midu.dev/)**, desarrollador y creador de contenido educativo con una gran comunidad en español.

## 📚 Contenido del Bootcamp

**[GitHub](https://github.com/midudev)**, repositorio oficial del bootcamp con todo el contenido y los proyectos.

---

## 💻 Requisitos de Instalación

Antes de comenzar, estas son las herramientas que he instalado para seguir el bootcamp:

- **[Chrome](https://www.google.com/chrome/)** - Navegador web

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
```

- **[Terminal Warp](https://midu.link/warp)** - Terminal con IA y Agentes

```bash
wget https://releases.warp.dev/stable/v0.2025.09.24.08.11.stable_03/warp-terminal_0.2025.09.24.08.11.stable.03_amd64.deb
sudo apt install ./warp-terminal_0.2025.09.24.08.11.stable.03_amd64.deb
```

- **[Git](https://git-scm.com/)** - Control de versiones

```bash
sudo apt install git
```

---

## 🧩 Configuración de Git

- **Configurar usuario y rama principal:**
```bash
git config --global user.name "Nombre Apellido"
git config --global user.email email@email.com
git config --global init.defaultBranch main
```

- **Verificar la configuración de Git:**
```bash
git config --get user.name
git config --get user.email
git config --get init.defaultBranch
```

- **Comprobar si ya tengo una clave SSH creada:**
```bash
cat ~/.ssh/id_ed25519.pub
```

- **Crear una clave SSH para autenticarme con GitHub:**
```bash
ssh-keygen -t ed25519
```

- **Copiar la clave pública generada y añadirla a GitHub**:
```bash
cat ~/.ssh/id_ed25519.pub
```
Uso: `Settings → SSH and GPG keys → New SSH key`


- **Comprobar la conexión con GitHub:**
```bash
ssh -T git@github.com
```

---

## 🛠️ Herramientas de Desarrollo

- **[Visual Studio Code](https://code.visualstudio.com/)** - Editor de código

```bash
wget -O code-latest.deb 'https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64'
sudo apt install ./code-latest.deb
```

- **[Extensión Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)** - Permite visualizar cambios en HTML/CSS en tiempo real.

Uso: `Ver → Paleta de comandos → "Live Preview: Start Server"`

- **[Extensión Windsurf](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)** - Extensión de autocompletado IA

Uso: `Extensiones → GitHub Copilot → Deshabilitar"`

---

## 🔨 Herramientas Adicionales

- **[Stitch](https://stitch.withgoogle.com/)** - Herramienta para crear prototipos de aplicaciones mediante prompts de IA.

- **[Tabler](https://tabler.io/icons)** - Generador de iconos vectoriales en formato SVG.

---

## 📚 Bibliografía

- **[Documentación de HTML](https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements)** - MDN Web Docs

---

## Tareas

[X] - **[Curso de HTML](https://www.youtube.com/watch?v=3nYLTiY5skU)** - Curso de HTML

[] - **[Curso de CSS](https://www.youtube.com/playlist?list=PLUofhDIg_38q7l8gV4IVCz_pjUeyD99_j)** - Curso de CSS

[] - Hacer la pagina de "Encuentra tu próximo trabajo"

[] - **[Plataforma de aprendizaje JS](https://www.aprendejavascript.dev/)** - Plataforma de aprendizaje JS