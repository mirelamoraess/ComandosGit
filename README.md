# Comandos usando o git

### Configurando a identificação no Git

```bash
>> git config user.name "seuUsuario"
>> git config user.email "seuEmail"
```
---

### Salvando a primeira versão de um projeto

Depois de criar um repositório no github, executar os seguintes comandos ->

```bash
>> git init
>> git add .
>> git remote add origin https://github.com/seuLinkDoRepositorio
>> git commit -m "nomeDoCommit"
>> git push -u origin master
```
---

### Salvando uma nova versão
```bash
>> git add .
>> git commit -m "nomeDoNovoCommit"
>> git push
```
---

### Clonando um repositório

Após copiar o link do repositório que deseja clonar, fazer ->
```bash
>> git clone codigocopiado
>> code .
```
---

### Criando uma Branch
```bash
>> Configure seu usuário
>> git checkout -b nomeBranch
>> git checkout (mostra em qual branch você está)
>> git push origin nomeBranch
```
---

### Plus

#### Se estiver na Bosch não esqueça de remover suas credenciais que ficaram salvas em:
```bash
>> "Gerenciador de Credenciais"
>> "Credenciais do Windows"
>> Também não se esqueça de desconectar o git do edge
```
