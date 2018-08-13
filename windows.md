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
ruby 2.4.4p296 (2018-03-28 revision 63013) [x64-mingw32]
```

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
