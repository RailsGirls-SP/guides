# Tutorial para instalação e configuração do rails no Windows

## Ruby

O jeito mais simples de instalar o _Ruby_ e na sua máquina é usando o [Rails Installer](http://www.railsinstaller.org/pt-BR).


Baixe o instalador da versão `2.3` do _ruby_.
Execute o programa e siga as instruções do instalador.

Durante a instalação, não se esqueça de marcar a opção para instalar o git junto.

Para ter certeza de que deu tudo certo, procure e abra o programa `git bash` no seu computador (isso deve abrir uma tela preta esquisita haha).
No `git bash`, digite o seguinte comando:
```bash
ruby -v
```

Se a resposta for parecida com o texto abaixo, quer dizer que tudo está certo até agora! :tada:
```bash
ruby 2.3.2p217 (2016-11-15 revision 56796) [x86_64-darwin16]
```

Como a versão 2.3 está um pouco velhinha, vamos precisar fazer algumas outras coisinhas para instalar uma mais nova. 

Primeiro, baixe o instalador mais recente do [Ruby + DevKit](https://rubyinstaller.org/downloads/) e o execute em seu computador.
Selecione todas as caixinhas que aparecem durante a instalação. Após finalizar a instalação, marque a caixinha que diz `Run 'ridk install' ...` e clique em _Finalizar_. O computador vai abrir um terminal, com 3 opções. Digite **3** e aguarde. Se ele perguntar a mesma coisa de novo, apenas aperte _enter_.

Agora, você precisa abrir o "seu computador", na pasta **C:\\**. Lá deve ter aparecido uma pasta do ruby, algo como `C:\Ruby26-x64`. Copie esse caminho. Precisaremos alterar o caminho do computador para o ruby, então:
1. Abra o menu do windows
2. Clique com o botão direito em _Meu Computador_ e depois clique em _Propriedades_
3. Clique em _Configurações avançadas do sistema_
4. Clique em _Variáveis de ambiente_
5. Nas variáveis do usuário, clique em cima de `PATH` e depois em _Editar_
6. Onde tiver algo como `C:\RailsInstaller\Ruby....\bin`, clique em cima e depois em _Editar_ novamente
7. Troque o que tiver lá para o que a gente copiou antes do primeiro passo, adicionando um _\bin_ no final. Vai ficar algo como `C:\Ruby26-x64\bin`

Para finalizar, feche o _Git Bash_ e abra-o novamente. Digite `ruby -v` nele. Se a resposta for parecida com o texto abaixo, quer dizer que tudo está certo até agora! :tada:

```bash
ruby 2.6.5p114 (2019-10-01 revision 67812) [x64-mingw32]
```

## SQLite

Para que a gente consiga fazer o workshop, precisamos de um lugar para salvar algumas informações: um banco de dados. No nosso caso, usaremos o **SQLite**. Faça download do [sqlite-tools-win32-x86-3300100.zip](https://www.sqlite.org/download.html) e descompacte os 3 arquivos que tem lá dentro em uma pasta chamada `sqlite`. Depois disso, copie essa pasta para `C:/` (assim você fica com uma pasta chamada `C:/sqlite`. Agora precisamos adicionar esse caminho no _PATH_ do nosso computador.

1. Abra o menu do windows
2. Clique com o botão direito em _Meu Computador_ e depois clique em _Propriedades_
3. Clique em _Configurações avançadas do sistema_
4. Clique em _Variáveis de ambiente_
5. Nas variáveis do usuário, clique em cima de `PATH` e depois em _Editar_
6. Adicione em uma linha nova: `C:\sqlite`

## Node
TODO

## Rails

Se deu tudo certo na instalação do _ruby_, para instalar o _Rails_ bastar abrir o `git bash` e digitar o seguinte comando:
```bash
gem install rails
```

A resposta deve ser algo parecida com o texto abaixo:
```bash
Fetching: activesupport-5.2.1.gem (100%)
Successfully installed activesupport-5.2.1
Fetching: actionview-5.2.1.gem (100%)
Successfully installed actionview-5.2.1
Fetching: actionpack-5.2.1.gem (100%)
Successfully installed actionpack-5.2.1
Fetching: activemodel-5.2.1.gem (100%)
Successfully installed activemodel-5.2.1
Fetching: activerecord-5.2.1.gem (100%)
Successfully installed activerecord-5.2.1
Fetching: railties-5.2.1.gem (100%)
Successfully installed railties-5.2.1
Fetching: rails-5.2.1.gem (100%)
Successfully installed rails-5.2.1
11 gems installed
```

Para ter certeza que tudo deu certo até aqui, digite o seguinte comando:
```bash
rails -v
```
A resposta deve ser algo como:
```bash
Rails 5.2.1
```

## Editor de texto

Para escrever o seu código (ou _codar_, como costumamos dizer), recomendamos que use algum editor de texto próprio para esta atividade.
Os editores recomendados são (qualquer um deles vai servir muito bem para você):

- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime](https://www.sublimetext.com/3)
- [Atom](https://atom.io/)
- [Ruby Mine](https://www.jetbrains.com/ruby/)

## Git

Git é uma forma de verisonar arquivos de forma bem mais eficiente que ter os arquivos `código_v1`, `código_v2`, `código_versaoFinal` e `código_versaoFinalAgoraVai`. Como parte do workshop Rails Girls, é legal ter ele configurado e instalado!
Usando o Rails Installer, o git já é instalado automagicamente no seu computador, então fica faltando apenas criar uma conta lá. Para isso, siga os seguintes passos:

1. Entre no [site do github](https://github.com/);
2. Escolha um username qualquer, coloque seu email, invente uma senha e clique em **"Create an account"**;
3. Na página seguinte, nas opções de plano, escolha *"Unlimited public repositories for free"* e clique em **"Continue"**;
4. A etapa de seguinte tem um monte de perguntinha sobre você, mas você pode não responder nada e pular essa etapa, clicando em *"skip this step"*, no final da página;
5. PRONTO! Você já tem uma conta do git :tada:
