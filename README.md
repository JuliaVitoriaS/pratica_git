# pratica_git
Repositório para prática de comandos do Git


~~~bash
git config --global core.editor "code --wait"
~~~ 

O comando acima define o Visual Studio Code com o edito padão das mensagens de commit 

~~~bash
git commit --allow-empty
~~~

O  parâmetro `--allow-empty`permite a criação de um commit vazio, para fins de teste e pratica do Git.


~~~bash
git commit -a 
~~~ 
<!-- O -a significa o Add(adicionar) no momento de realizar o commit -->
O parâmetro `-a`adiciona todos os arquivos modificados ou não ignorados ao commit atual.

~~~bash
git checkout -b novoBranch
git switch -c git novoBranch
~~~

O parâmetro `-b` alterna para `novoBranch`criando o branch. O mesmo acontece com o comando `git switch`com o parâmetro `-c`.