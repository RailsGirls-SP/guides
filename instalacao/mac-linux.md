# Tutorial para instalação e configuração do rails no Mac ou Linux

## Ruby

Primeiramente, abra o seu `terminal` (uma tela preta esquisita) e digite os seguintes comandos para instalar o [RVM](https://rvm.io/)(gerenciador de versões do ruby), já com a última versão estável do [ruby](https://www.ruby-lang.org/en/downloads/releases/):
```bash
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

\curl -sSL https://get.rvm.io | bash -s stable --ruby
```

Para ter certeza de que deu tudo certo, `terminal`, digite o seguinte comando:
```bash
ruby -v
```

Se a resposta for parecida com o texto abaixo, quer dizer que tudo está certo até agora! :tada:
```bash
ruby 3.0.2p107 (2021-07-07 revision 0db68f0233) [x86_64-darwin16]
```

> :warning: Verifique se a versão baixada corresponde a mais estável do [site oficial](https://www.ruby-lang.org/en/downloads/releases/)

## Rails

Se deu tudo certo na instalação do _ruby_, para instalar o _Rails_ bastar abrir o `terminal` e digitar o seguinte comando:
```bash
gem install rails
```

A resposta deve ser algo parecida com o texto abaixo:
```bash
Building native extensions. This could take a while...
Successfully installed nio4r-2.5.8
Successfully installed websocket-extensions-0.1.5
Building native extensions. This could take a while...
Successfully installed websocket-driver-0.7.5
Successfully installed actioncable-6.1.4.1
Successfully installed marcel-1.0.2
Successfully installed activestorage-6.1.4.1
Successfully installed actionmailbox-6.1.4.1
Successfully installed actiontext-6.1.4.1
Successfully installed thor-1.1.0
Successfully installed method_source-1.0.0
Successfully installed railties-6.1.4.1
Successfully installed sprockets-4.0.2
Successfully installed sprockets-rails-3.2.2
Successfully installed rails-6.1.4.1
14 gems installed
```

Para ter certeza que tudo deu certo até aqui, digite o seguinte comando:
```bash
rails -v
```
A resposta deve ser algo como:
```bash
Rails 6.1.4
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
