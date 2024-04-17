'# pratica_git
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
branch
O parâmetro `-b` alterna para `novoBranch`criando o branch. O mesmo acontece com o comando `git switch`com o parâmetro `-c`.

~~~bash 
git branch -D nomeBranch
git push --delete origin nomeBrnch 
~~~
Para apagar um branch é preciso primeiro apaga-lo localmemte (1° comando) e depois propágar a deleção para o repertorio remopto (2° comando)git 









<!-- dia 17-04 -->

~~~bash
git push --force
~~~

### tags

~~~bash
git tag <tag> <referencia>
~~~

Utilize o comando  `tag`para adicionar marcos ('milestones') a commits ou outras referencias no historicos do Git.Se você não especificar a referente, O git vai atribuifr a tag ao commit apontadi por **HEAD**

VocÊ deve fazer o push da tags para o repertório remoto separadamete com a flag `--tags`.

~~~bash 
git push --tags
~~~

