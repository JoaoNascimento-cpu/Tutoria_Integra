# Integra - Guia de Instalação para Windows 10/11

Este guia explica como instalar e configurar os programas essenciais para utilizar o Integra.

---

## 📦 Pré-requisitos
- Windows 10 ou 11 (64-bit).
- Acesso administrativo no computador.
- Conexão com a internet.

---

## 🛠 Instalação dos Programas

### 1. Visual Studio Code
**Descrição**: Editor de código para desenvolvimento e configuração do Integra.

#### Passo a passo:
1. Acesse o site oficial: [https://code.visualstudio.com](https://code.visualstudio.com).
2. Clique em **Download for Windows** (versão Stable).
3. Execute o instalador baixado (`VSCodeSetup-x64-XXXXX.exe`).
4. Siga as instruções de instalação (marque as opções desejadas, como "Adicionar à PATH").
5. Após a instalação, abra o VS Code e instale as extensões recomendadas:
   - **Laravel Extension Pack** (para suporte ao Laravel).
   - **PHP Intelephense** (autocompletar PHP).

---

### 2. MySQL Workbench
**Descrição**: Ferramenta para gerenciar bancos de dados MySQL.

#### Passo a passo:
1. Acesse o site oficial: [https://dev.mysql.com/downloads/workbench](https://dev.mysql.com/downloads/workbench).
2. Role para baixo e clique em **Download** na seção "MySQL Workbench".
3. Execute o instalador (`mysql-workbench-community-XXXXX-winx64.msi`).
4. Siga as instruções do instalador.
   -
5. Após a instalação:
   - Abra o MySQL Workbench.
   - Clique em `+` em "MySQL Connections" para criar uma nova conexão.
   - Preencha os dados do servidor Integra (host, porta, usuário e senha fornecidos pela equipe).

---

### 3. Laravel Herd
**Descrição**: Ambiente de desenvolvimento local para Laravel (PHP, Nginx, MySQL).

#### Passo a passo:
1. Acesse o site oficial: [https://herd.laravel.com](https://herd.laravel.com).
2. Clique em **Download for Windows**.
3. Execute o instalador e siga as etapas:
4. Após a instalação:
   - Abra o Herd e ative os serviços (PHP, MySQL, Nginx) na aba **Services**.
   - Na aba **Sites**, adicione o diretório do projeto Integra.
   - Configure o arquivo `.env` do projeto com as credenciais do banco de dados local.

---

## 🔍 Verificações Pós-Instalação
1. **VS Code**:
   ```bash
   code --version
