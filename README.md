# Customização do Vim - Arquivo .vimrc

Este arquivo `.vimrc` fornece uma configuração otimizada para o Vim, melhorando a usabilidade, navegação e experiência visual.

## Recursos Principais

- **Melhor visualização**: Numeração de linhas, realce de sintaxe e suporte a cores.
- **Melhoria na edição**: Indentação automática, substituição de tabs por espaços.
- **Navegação eficiente**: Rolagem otimizada e atalhos para facilitar buscas.
- **Desempenho aprimorado**: Renderização mais rápida e melhor suporte a terminais modernos.

## Configuração

Adicione as seguintes linhas ao seu arquivo `~/.vimrc`:

```vim
" Configuração básica\
set nocompatible    " Garante que o Vim não rode no modo de compatibilidade com Vi
set encoding=utf-8   " Usa codificação UTF-8
set number          " Exibe a numeração das linhas
set relativenumber  " Exibe numeração relativa para facilitar movimentação

" Melhorias visuais
set cursorline      " Destaca a linha do cursor
set cursorcolumn    " Destaca a coluna do cursor
set termguicolors   " Habilita suporte a cores verdadeiras
set background=dark " Define fundo escuro para melhor legibilidade

" Melhorias na edição
set shiftwidth=4    " Define indentamento de 4 espaços
set tabstop=4       " Define tabulação de 4 espaços
set expandtab       " Converte tabulações em espaços
set autoindent      " Mantém a indentação da linha anterior

" Pesquisa inteligente
set ignorecase      " Ignora maiúsculas por padrão
set smartcase       " Respeita maiúsculas se houver na busca
set incsearch       " Realiza busca incremental
set hlsearch        " Realça resultados da busca

" Melhorias de navegação
set scrolloff=10    " Mantém 10 linhas visíveis acima/abaixo ao rolar
set nowrap         " Impede quebra de linha automática
set splitbelow splitright " Janelas divididas abertas de forma intuitiva

" Melhorias de desempenho
set lazyredraw      " Evita redesenho desnecessário da tela
set ttyfast         " Diz ao Vim que o terminal é rápido
set wildmenu        " Habilita menu de autocomplete
set wildmode=list:longest " Melhora autocomplete estilo Bash
set mouse=a        " Habilita uso do mouse

" Evitar arquivos desnecessários
set nobackup       " Não salva arquivos de backup
set nowritebackup  " Não salva arquivos temporários
set wildignore=*.docx,*.jpg,*.png,*.gif,*.pdf,*.pyc,*.exe,*.flv,*.img,*.xlsx " Ignora arquivos indesejados
```

## Como Aplicar as Configurações

1. Abra seu terminal.
2. Edite ou crie o arquivo `.vimrc` no diretório home:
   ```sh
   nano ~/.vimrc
   ```
3. Copie e cole as configurações acima.
4. Salve o arquivo e saia (`CTRL + X`, `Y`, `Enter`).
5. Abra o Vim e aproveite sua nova configuração!

## Contribuidor
José Roberval Vieira Gomes Neto

[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=FF00F6&color:FFF)](mailto:robervalg.neto@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=FF00F6&color:FFF)](https://www.linkedin.com/in/joseroberval)
[![Instagram](https://img.shields.io/badge/-Instagram-000?style=for-the-badge&logo=instagram&logoColor=FF00F6&color:FFF)](https://www.instagram.com/robervalgneto/)



