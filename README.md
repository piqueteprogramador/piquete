# PIQUETE - O Poder da IA nas Mãos do Criador

Site profissional para o canal PIQUETE, criador de conteúdo angolano especializado em ensinar como usar inteligência artificial para criar aplicativos, scripts, bots e automações no mercado digital.

## 🚀 Sobre o Projeto

Este site serve como central de conteúdos do canal, oferecendo:

- **Scripts e Códigos**: Automações prontas para uso
- **Prompts Otimizados**: Comandos testados para IA
- **Apps Criados**: Projetos desenvolvidos com IA
- **Parcerias**: Espaço para colaborações e contatos

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna
- **Tailwind CSS**: Framework CSS utilitário
- **JavaScript**: Interatividade e funcionalidades
- **Font Awesome**: Ícones profissionais

## 📁 Estrutura do Projeto

```
piquete-site/
├── index.html          # Página inicial
├── prompts.html        # Página de prompts
├── scripts.html        # Página de scripts e ferramentas
├── apps.html           # Página de apps criados
├── contato.html        # Página de contato e parcerias
├── assets/
│   ├── css/
│   │   ├── input.css   # CSS fonte do Tailwind
│   │   └── output.css  # CSS compilado
│   ├── js/             # Scripts JavaScript (futuro)
│   └── images/         # Imagens do site (futuro)
├── tailwind.config.js  # Configuração do Tailwind
├── package.json        # Dependências do projeto
└── README.md          # Este arquivo
```

## 🚀 Como Rodar o Projeto Localmente

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

### Instalação

1. **Clone o repositório:**
```bash
git clone https://github.com/piqueteprogramador/piquete-site.git
cd piquete-site
```

2. **Instale as dependências:**
```bash
npm install
```

3. **Compile o CSS (se necessário):**
```bash
node node_modules/tailwindcss/dist/lib.js -i ./assets/css/input.css -o ./assets/css/output.css
```

4. **Abra o projeto:**
- Abra o arquivo `index.html` em seu navegador
- Ou use um servidor local como Live Server no VS Code

## ✏️ Como Editar o Conteúdo

### Editando Informações Pessoais

**Links das Redes Sociais** (em todas as páginas):
- Procure por `@programadorhumilde` e `@programado.humilde`
- Substitua pelos seus handles

**Link do Grupo WhatsApp**:
- Procure por `https://chat.whatsapp.com/BiDE2pul0uS1YU7UvTzjxw`
- Substitua pelo link do seu grupo

**Vídeo do YouTube** (index.html):
- Procure por `src="https://www.youtube.com/embed/dQw4w9WgXcQ"`
- Substitua pelo ID do seu vídeo

### Adicionando Novos Prompts (prompts.html)

1. Localize a seção `<!-- Lista de prompts -->`
2. Copie um dos cards existentes
3. Edite:
   - `data-keywords`: palavras-chave para busca
   - `data-prompt`: o prompt completo
   - Título e descrição
   - Tags

### Adicionando Novos Scripts (scripts.html)

1. Localize a seção `<!-- Lista de scripts -->`
2. Copie um dos cards existentes
3. Edite:
   - `data-tags`: tags para filtros
   - Título, descrição e ícone
   - Links para GitHub

### Adicionando Novos Apps (apps.html)

1. Localize a seção `<!-- Lista de apps -->`
2. Copie um dos cards existentes
3. Edite:
   - Título e descrição
   - Tecnologias utilizadas
   - Links para teste e repositório

## 🔄 Como Publicar Atualizações

### Método 1: Via VS Code (Recomendado)

1. **Abra o projeto no VS Code:**
```bash
code .
```

2. **Faça suas alterações nos arquivos**

3. **Recompile o CSS se necessário:**
```bash
node node_modules/tailwindcss/dist/lib.js -i ./assets/css/input.css -o ./assets/css/output.css
```

4. **Commit e push das alterações:**
```bash
git add .
git commit -m "Descrição das alterações"
git push origin main
```

### Método 2: Via Terminal

```bash
# Após fazer as alterações
git add .
git commit -m "Atualizações no site"
git push origin main
```

## 🎨 Personalização de Cores

O site usa uma paleta de cores escura com detalhes vibrantes:

- **Fundo Principal**: `bg-gray-900` (cinza muito escuro)
- **Fundo Secundário**: `bg-gray-800` (cinza escuro)
- **Cor de Destaque**: `text-cyan-400` (ciano)
- **Texto Principal**: `text-white` (branco)
- **Texto Secundário**: `text-gray-300` (cinza claro)

Para alterar as cores, edite as classes Tailwind nos arquivos HTML.

## 📱 Responsividade

O site é totalmente responsivo e funciona em:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (até 767px)

## 🤝 Contribuições

Este é um projeto pessoal, mas sugestões são bem-vindas! Entre em contato através das redes sociais.

## 📄 Licença

Este projeto é de uso pessoal. Todos os direitos reservados ao PIQUETE.

## 📞 Contato

- **TikTok**: [@programadorhumilde](https://tiktok.com/@programadorhumilde)
- **Instagram**: [@programado.humilde](https://instagram.com/programado.humilde)
- **WhatsApp**: [Grupo PIQUETE](https://chat.whatsapp.com/BiDE2pul0uS1YU7UvTzjxw)

---

**Desenvolvido com ❤️ por PIQUETE**

