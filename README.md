# SSM — Simple Sales Management

**SSM (Simple Sales Management)** é um app desktop simples e rápido para **gerenciar clientes e vendas**, com foco em fluxo enxuto, visual limpo (dark mode) e dados salvos **localmente**.  
Feito por **Levi Pantaleão**.

> App desktop para gerenciar clientes e vendas, com setup inicial (idioma/tema/diretório/perfil do negócio), recibos/impressões e dados locais — SSM (Simple Sales Management).

---

## ✨ Principais recursos

- **Clientes**
  - Cadastro, visualização e edição
  - Busca e filtros para encontrar rápido
- **Vendas**
  - Registro de novas vendas
  - Listagem com busca/filtros
  - Visualização detalhada em pop-up/modal
- **Recibos / Impressões**
  - Perfil do negócio usado em **recibos/impressões**
- **Setup inicial (primeiro uso)**
  - Seleção de **idioma**, **tema**, **diretório de dados** e **dados do Business**
- **Multilíngue**
  - **Português (pt-BR), Inglês (en) e Espanhol (es)**
- **Privacidade**
  - Dados do app ficam **no seu computador** (sem nuvem por padrão)

---

## 🖥️ Capturas de tela

> Adicione prints depois (recomendado para o GitHub):

- `docs/screenshots/sales.png`
- `docs/screenshots/clients.png`
- `docs/screenshots/new-sale.png`
- `docs/screenshots/settings.png`
- `docs/screenshots/business.png`
- `docs/screenshots/welcome.png`

---

## ✅ Instalação (Setup.exe)

### Windows (recomendado)
1. Baixe o instalador na aba **Releases** do GitHub.
2. Execute o `SSM-Setup.exe` (gerado com **Inno Setup**).
3. Abra o SSM e finalize o **setup inicial**.

> Dica: se o Windows SmartScreen alertar, clique em **“Mais informações” → “Executar assim mesmo”** (comum em apps independentes).

---

## ▶️ Executar pelo código-fonte (modo dev)

> Útil para quem quer **modificar** e rodar localmente.

### Requisitos
- **Python 3.10+** (recomendado)
- Pip / venv

### Passo a passo
```bash
# 1) Clonar
git clone https://github.com/SEU_USUARIO/SSM.git
cd SSM

# 2) Ambiente virtual
python -m venv .venv

# 3) Ativar
# Windows:
.venv\Scripts\activate
# Linux/macOS:
# source .venv/bin/activate

# 4) Instalar dependências
pip install -r requirements.txt

# 5) Rodar
python server.py
