# ohmyzsh + k-vim  配置#

## zsh ##
+ 1 安装zsh
	
>		apt-get install zsh
 
+ 2 安装ohmyzsh
	
>参照[ github ](https://github.com/robbyrussell/oh-my-zsh "oh my zsh")上的说明

+ 3 配置zsh

> .oh-my-zsh/themes下有多个主题，编辑 .zshrc中ZSH_THEME="XXX"即可选择主题。

>修改默认shell 
>
	chsh -s /bin/zsh username

##k-vim##
+	安装k-vim

>参照[ github ](https://github.com/wklken/k-vim "k-vim")上的说明

+	异常

>+ YouCompleteMe unavailable: requires Vim compiled with Python (2.6+ or 3.3+) support
> 
		apt-get install vim-nox
>+ YouCompleteMe unavailable: requires Vim 7.4.1578+.
>
>>需要升级vim
>>
	sudo apt-get update && sudo apt-get upgrade
>或重新编译安装
>>
	git clone https://github.com/vim/vim.git
	cd vim/src
	./configure --enable-pythoninterp=yes
	make
	sudo make installvim
>



	
	