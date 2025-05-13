# LeetCode-Optimal-Solutins-CPP-JAVA


" ========================
" Basic .vimrc Configuration
" ========================

" Enable line numbers
set number                  " Show absolute line number on current line
set relativenumber          " Show relative line numbers for all other lines

" Enable syntax highlighting
syntax on

" Enable file type detection and plugins
filetype plugin indent on

" Tab and indentation settings
set tabstop=4               " Number of spaces that a <Tab> in the file counts for
set shiftwidth=4            " Number of spaces to use for each step of (auto)indent
set expandtab               " Convert tabs to spaces
set autoindent              " Auto-indent new lines
set smartindent             " Smarter auto-indentation based on syntax

" Search settings
set ignorecase              " Case-insensitive search
set smartcase               " Override 'ignorecase' if uppercase is used
set incsearch               " Show search results while typing
set hlsearch                " Highlight all search matches

" Backspace behavior
set backspace=indent,eol,start " Make backspace behave like most editors

" Clipboard integration
set clipboard=unnamedplus   " Use system clipboard (requires +clipboard support)

" Matching parentheses
set showmatch               " Highlight matching parentheses/brackets

" Scrolling and wrapping
set scrolloff=5             " Minimum number of screen lines to keep above and below the cursor
set wrap                    " Wrap long lines (disable with 'set nowrap')

" Status line and cursor position
set laststatus=2            " Always show the status line
set ruler                   " Show line and column number of the cursor

" Disable swap file (optional, use with caution)
set noswapfile              " Don't create swap files

" Enable mouse support
set mouse=a                 " Enable mouse in all modes

" Persistent undo
set undofile                " Enable undo even after closing file

" Visual and UI tweaks
set cursorline              " Highlight the current line
set wildmenu                " Enhanced command-line completion
set lazyredraw              " Don't redraw while executing macros (faster)
set ttyfast                 " Improve scrolling speed

" Color scheme (choose your favorite)
colorscheme desert          " Built-in color scheme (can be changed)

" ========================
" Optional: Plugin Manager (vim-plug)
" ========================
" To enable plugins, install vim-plug and uncomment the lines below:
"
" call plug#begin('~/.vim/plugged')
" Plug 'preservim/nerdtree'             " File explorer
" Plug 'junegunn/fzf', { 'do': { -> fzf#install() } } " Fuzzy finder
" Plug 'tpope/vim-surround'             " Surround text objects easily
" call plug#end()

" ========================
" Custom Key Mappings (optional)
" ========================
" nnoremap <Space> :nohlsearch<CR>     " Clear search highlight with Space
" nnoremap <C-n> :NERDTreeToggle<CR>   " Toggle NERDTree with Ctrl+n
