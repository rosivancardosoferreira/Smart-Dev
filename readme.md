# 📦 Guia de Instalação - Smart Dev (macOS)

Guia completo para instalar e usar o Smart Dev no macOS.

## 📋 Sobre o Smart Dev

Smart Dev é um gerenciador de projetos para desenvolvedores que trabalham com múltiplos projetos simultaneamente. Ideal para quem trabalha com microfrontends, microserviços ou simplesmente precisa organizar vários projetos.

### Principais Funcionalidades

- ✅ **Organização por Workspaces**: Agrupe projetos relacionados
- ✅ **Abertura Rápida na IDE**: VS Code, Cursor, IntelliJ, Android Studio, Xcode
- ✅ **Terminal Integrado**: Acesso rápido ao terminal do projeto
- ✅ **Links de Repositório**: Abra GitHub/GitLab direto no navegador
- ✅ **Busca Inteligente**: Encontre projetos rapidamente
- ✅ **Favoritos**: Marque projetos importantes
- ✅ **Personalizável**: Configure suas stacks e tipos de projeto

---

## 🚀 Instalação

### 1. Download

Faça o download do arquivo correspondente à sua arquitetura:

### 2. Extração

1.  Descompacte o arquivo `.zip` baixado
2.  Arraste o arquivo `Smart Dev.app` para a pasta **Applications** (`/Applications`)

### 3. Remover Quarentena do macOS ⚠️

**Importante**: O aplicativo ainda não está assinado com certificado da Apple Developer, então o macOS bloqueará a execução na primeira vez.

Para resolver, abra o **Terminal** e execute:

```bash
sudo xattr -rd com.apple.quarantine /Applications/"Smart Dev.app"
```

- Digite sua senha de administrador quando solicitado
- Pressione Enter

### 4. Executar

Agora você pode abrir o Smart Dev normalmente:

- **Aplicativos**: Vá até a pasta Applications e clique duas vezes
- **Launchpad**: Procure por "Smart Dev"
- **Spotlight**: Pressione `⌘ + Espaço`, digite "Smart Dev" e pressione Enter

---

## 🎯 Primeiros Passos

### 1. Configurar IDEs

Antes de adicionar projetos, configure os comandos das suas IDEs:

1.  Clique no ícone **⚙️ Configurações** no rodapé da barra lateral
2.  Na seção **"Comandos das IDEs"**, configure as IDEs que você usa
3.  As configurações são salvas automaticamente

### 2. Personalizar Stacks e Tipos

Configure as tecnologias e categorias que você trabalha:

1.  Em **Configurações**, clique em **"Campos do Projeto"**
2.  Em **Stacks**, adicione tecnologias como:
    - Node.js
    - Vue
    - Angular
    - Kotlin
    - Java
    - Outros...

3.  Em **Tipos de Projeto**, adicione categorias como:
    - Frontend
    - Backend
    - Mobile
    - Fullstack
    - Microfrontend
    - Outros...

### 3. Criar Workspaces

Organize seus projetos em grupos:

1.  Na barra lateral, clique no botão **+** ao lado de "Workspaces"
2.  Dê um nome (ex: "E-commerce", "Ferramentas Internas", "Clientes")
3.  Workspaces ajudam a separar projetos relacionados

### 4. Adicionar Projetos

1.  Clique no botão **+ Novo Projeto** no topo
2.  Preencha as informações:
    - **Nome do Projeto**: Nome de identificação
    - **Stack**: Tecnologia principal
    - **Tipo**: Categoria do projeto
    - **IDE Preferida**: IDE que será usada ao clicar em "Abrir"
    - **Repositório Remoto** (opcional): URL do GitHub/GitLab/Bitbucket
    - **Path do Projeto**: Caminho da pasta (use 📁 para buscar)

---

## 💡 Uso Diário

### Abrir Projeto na IDE

No card do projeto, clique no botão **"Abrir no [IDE]"**

### Abrir Terminal

No card do projeto, clique no botão **"Terminal"**

### Abrir Repositório

Se você cadastrou a URL do repositório, clique no botão **"Repositório"** para abrir no navegador

### Buscar Projetos

Use a barra de busca no topo da barra lateral para filtrar projetos por nome

### Favoritar Projetos

1.  Clique no menu **⋮** no card do projeto
2.  Selecione **"Adicionar aos favoritos"**
3.  Acesse rapidamente pela seção **"Favoritos"** na sidebar

### Editar Projeto

1.  Clique no menu **⋮** no card do projeto
2.  Selecione **"Editar"**

### Mover para Outro Workspace

1.  Clique no menu **⋮** no card do projeto
2.  Selecione **"Mover para workspace"**
3.  Escolha o workspace de destino

### Menu de Contexto

Clique com o **botão direito** no card do projeto para abrir o menu rápido (igual ao menu **⋮**)

---

## 🎨 Entendendo a Interface

### Status dos Projetos

- **● Verde**: Projeto ativo
- **● Cinza**: Projeto inativo

### Tags

- **Azul**: Stack e Tipo configurados normalmente
- **Vermelho**: Stack ou Tipo foi deletado das configurações (edite o projeto para corrigir)

---

## 📝 Dicas e Boas Práticas

### Para Microfrontends

- Crie um workspace para cada produto/domínio
- Use tags consistentes (ex: "host", "remote", "shared")
- Cadastre sempre o repositório remoto

### Para Múltiplos Clientes

- Crie um workspace para cada cliente
- Use nomenclatura clara nos projetos
- Favorite os projetos em andamento

### Organização Geral

- Use a busca com `⌘ + F` para agilizar
- Mantenha apenas projetos ativos visíveis
- Revise periodicamente seus workspaces

---

## ❓ Problemas Comuns

### "Não consigo abrir o aplicativo"

Execute o comando de remoção da quarentena novamente:

```bash
sudo xattr -rd com.apple.quarantine /Applications/"Smart Dev.app"
```

### "A IDE não abre ao clicar no botão"

Verifique se:

1.  A IDE está instalada no `/Applications`
2.  O comando nas configurações está correto
3.  O nome da IDE no comando corresponde ao nome real no `/Applications`

### "O terminal não abre"

Verifique se o caminho do projeto está correto e se a pasta existe

---

## 🆘 Suporte

Encontrou algum problema ou tem sugestões?

- **Email**: rosivancardoso767@gmail.com

---

**Desenvolvido para desenvolvedores que trabalham com múltiplos projetos e precisam de agilidade no dia a dia.**
