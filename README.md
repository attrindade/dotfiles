# 🛠️ Dotfiles | André Trevisol Trindade

Repositório de configurações e automação de ambiente, gerenciado pelo [chezmoi](https://www.chezmoi.io/). Este setup foi desenhado para ser agnóstico, garantindo paridade entre **Ubuntu** e **Windows 11 (WSL/PowerShell)**.

---

## 📂 Estrutura do Repositório

| Pasta | Nome | Descrição |
| :--- | :--- | :--- |
| 🎨 | `aesthetics/` | Temas, wallpapers e scripts de instalação de fontes (Nerd Fonts). |
| 🚀 | `bin/` | Scripts executáveis personalizados adicionados ao `$PATH`. |
| 📦 | `modules/` | Listas de pacotes e scripts de instalação (`APT`, `Scoop`, `Brew`). |
| ⚙️ | `scripts/` | Automações de sistema, bootstrap e manutenção de ambiente. |
| 📝 | `dot_` | Arquivos de configuração (Dotfiles) gerenciados pelo chezmoi. |

---

## 🗺️ Roadmap de Sincronização

### 1. Core (Trio de Ferro)
- [x] **Git** & **GitHub CLI** (`.gitconfig`, `gh auth`)
- [ ] **SSH** (Configurações de hosts e chaves públicas)
- [ ] **IDE** (Antigravity / VS Code settings & extensions)

### 2. Package Managers (Instalações)
- [ ] **Linux**: `APT`, `Flatpak`, `Snap`
- [ ] **Windows**: `Scoop`, `Winget`
- [ ] **Cross-Platform**: `Homebrew`

### 3. Data & Dev Stack
- [ ] **Linguagens**: Python (Pip/Venv), Node.js (NPM)
- [ ] **Infra**: Docker & Docker Compose
- [ ] **Database**: SQL Clients (PostgreSQL/DuckDB)

### 4. Aesthetics (Identidade Visual)
- [ ] **Fonts**: Instalação automatizada de Nerd Fonts
- [ ] **Wallpapers**: Sincronização de galeria cinematográfica
- [ ] **Terminal**: Temas e prompts customizados

