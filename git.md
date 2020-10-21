# O que é git e pra que serve?

O git é uma ferramenta para controle e versionamento de código, ele é utilizado para facilitar o desenvolvimento em equipe, permitindo que várias pessoas alterem o mesmo projeto, ou até o mesmo arquivo.

## Principais comandos

### git branch

Visualiza qual branch você está.

### git branch \<nome da branch\>

Cria uma nova branch

```
git branch rails-girls
```

### git checkout

Entra numa branch.

```
git checkout rails-girls
```

### git checkout -b \<branch\>

Junta os comandos branch e checkout em um só (cria uma nova branch e já muda pra ela)

```
git checkout -b rails-girls
```

### git status

Verifica como está o monitoramento no momento.

### git add \<nome do arquivo\>

Adiciona o arquivo ao monitoramento.

```
git add index.html
```

Para adicionar todos os arquivos de uma vez só

```
git add .
```

### git commit

Confirma as alterações feitas e adicionadas pelo `git add`.

```
git commit -m "menssagem do commit"
```

### git push origin \<branch\>

Envia para o repositório remoto os commits realizados.

```
git push origin rails-girls
```

### git pull origin \<branch\>

Atualiza branch local com o que está no repositório remoto.

```
git pull origin rails-girls
```

Para conferir mais comandos acesse o [site oficial do git](https://git-scm.com/docs)
