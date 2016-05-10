# vimrc

## 공통 기능
 * 더블 탭(<TAB><TAB>)으로 분할된 창끼리 쉽게 이동할 수 있다.
 * 특정 단어에 커서를 두고 <F8>키를 누르면 '다음영어사전'에서 단어를 찾아준다.
 * 윈도우용 Vim에서 인코딩을 UTF-8로 설정한 경우, 메뉴의 한글이 깨지지 않게 해주는 설정 추가

## vimrc_basic
 * colorscheme: murphy
 * set lines=999 columns=999 옵션을 지우지 않으면 우분투 터미널에서 화면이 엉망이 됨

## vimrc_noplugins
 * colorscheme: molokai
  * https://github.com/tomasr/molokai
  * https://github.com/dokenzy/macvim 으로 빌드하면 molokai 테마가 기본으로 내장되어 있다.
 * macvim용 vimrc 파일. 플러그인을 깔지 않아도 꽤 편리함.
 * 내가 fork한 macvim(https://github.com/dokenzy/macvim)에는 molokai 테마가 기본 설치되어 있다.

## vimrc_pluings
 * colorscheme: molokai
 * 내가 사용하는 플러그인에 대한 설정이 추가된 vimrc
 * 플러그인은 Vundle로 쉽게 설치할 수 있다.

### vimrc_plugins__windows
 * Windows용 설정 추가
 * 참고 URL: https://github.com/VundleVim/Vundle.vim/wiki/Vundle-for-Windows
 * Vundle로 플러그인을 설치하기 위해서는 curl을 설치해야 함. 쉽게 cmder를 사용하는 것이 좋음
 * patched 폰트 설치: *https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/BitstreamVeraSansMono

### 플러그인 리스트
 * gmarik/Vundle.vim: let Vundle manage Vundle, required
 * jiangmiao/auto-pairs: insert or delete brackets, parens, quotes in pair
 * SearchComplete: Tab completion of words inside of a search ('/')
 * bling/vim-airline: lean & mean status/tabline for vim that's light as air
 * fugitive.vim: a Git wrapper so awesome, it should be illegal
 * nathanaelkane/vim-indent-guides: A Vim plugin for visually displaying indent levels in code
 * neocomplcache: Ultimate auto-completion system for Vim
 * terryma/vim-multiple-cursors: True Sublime Text style multiple selections for Vim
 * scrooloose/nerdcommenter: Vim plugin for intensely orgasmic commenting
 * sheerun/vim-polyglot: A solid language pack for Vim
 * scrooloose/nerdtree: A tree explorer plugin for vim
 * tpope/vim-surround: quoting/parenthesizing made simple
 * scrooloose/syntastic: Syntax checking hacks for vim
 * gcmt/wildfire.vim: Smart selection of the closest text object
 * othree/javascript-libraries-syntax.vim: Syntax file for JavaScript libraries
 * Lokaltog/vim-easymotion: EasyMotion provides a much simpler way to use some motions in vim.
 * klen/python-mode: Vim python-mode. PyLint, Rope, Pydoc, breakpoints from box.
 * vim-scripts/Pydiction: Tab-complete your Python
 * kana/vim-textobj-user: Create your own text objects
 * glts/vim-textobj-indblock: Vim text objects for blocks of indentation whitespace
 * majutsushi/tagbar: displays tags in a window, ordered by scope. require ctags.
 * gorkunov/smartpairs.vim: Fantastic selection for VIM
 * haya14busa/incsearch.vim: Improved incremental searching for Vim
 * mustache/vim-mustache-handlebars: spacebars, mustache and handlebars mode for vim
 * kshenoy/vim-signature: Plugin to toggle, display and navigate marks
 * jeetsukumaran/vim-indentwise: A Vim plugin for indent-level based motion.
 * chrisbra/vim-diff-enhanced: Better Diff options for Vim
 * jelera/vim-javascript-syntax: Enhanced javascript syntax file for Vim
 * zefei/vim-colortuner: Adjust your vim colors using sliders
 
