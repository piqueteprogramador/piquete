# Instruções para Criar o Repositório GitHub

## Passo 1: Criar o Repositório no GitHub

1. Acesse [GitHub.com](https://github.com) e faça login
2. Clique no botão "+" no canto superior direito
3. Selecione "New repository"
4. Configure o repositório:
   - **Repository name**: `piquete-site`
   - **Description**: "Site profissional do canal PIQUETE - Central de conteúdos sobre IA e programação"
   - **Visibility**: Public (ou Private se preferir)
   - **NÃO** marque "Add a README file" (já temos um)
   - **NÃO** marque "Add .gitignore" (já temos um)
   - **NÃO** marque "Choose a license"
5. Clique em "Create repository"

## Passo 2: Fazer Push do Código

Após criar o repositório, execute os seguintes comandos no terminal:

```bash
# Navegar para o diretório do projeto
cd /caminho/para/piquete-site

# Fazer push para o GitHub
git push -u origin main
```

Quando solicitado:
- **Username**: piqueteprogramador
- **Password**: SEU_TOKEN_AQUI (substitua pelo seu PAT)

## Passo 3: Verificar o Upload

1. Acesse https://github.com/piqueteprogramador/piquete-site
2. Verifique se todos os arquivos foram enviados
3. O README.md deve aparecer automaticamente na página principal

## Passo 4: Configurar GitHub Pages (Opcional)

Para hospedar o site gratuitamente no GitHub Pages:

1. No repositório, vá em "Settings"
2. Role para baixo até "Pages"
3. Em "Source", selecione "Deploy from a branch"
4. Escolha "main" como branch
5. Deixe "/ (root)" como pasta
6. Clique em "Save"
7. O site ficará disponível em: https://piqueteprogramador.github.io/piquete-site/

## Comandos para Futuras Atualizações

```bash
# Clonar o repositório (primeira vez)
git clone https://github.com/piqueteprogramador/piquete-site.git
cd piquete-site

# Abrir no VS Code
code .

# Após fazer alterações
git add .
git commit -m "Descrição das alterações"
git push origin main
```

## Estrutura Final do Repositório

```
piquete-site/
├── index.html          # Página inicial
├── prompts.html        # Página de prompts
├── scripts.html        # Página de scripts
├── apps.html           # Página de apps
├── contato.html        # Página de contato
├── assets/
│   └── css/
│       ├── input.css   # CSS fonte
│       └── output.css  # CSS compilado
├── README.md           # Documentação
├── .gitignore          # Arquivos ignorados
├── package.json        # Dependências
└── tailwind.config.js  # Configuração Tailwind
```

