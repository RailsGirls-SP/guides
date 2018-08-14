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
