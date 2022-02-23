# História do Git

A BitKeeper era uma empresa que armazenava todo o código do kernel do Linux em seu sistema, ou seja,todo o código do Linux era versionado dentro desse sistema. Houve uma quebra entre a BitKeeper e a Linux Foundation, que fez com que a BitKeeper retirasse o direito do Linux de ser isento (o que vai em contrapartida a proposta do SO). Linus Torvalds decidiu que não iria manter contrato com a empresa e resolveu criar seu próprio sistema de versionamento, incrementando melhorias que ele sentia falta no sistema da BitKeeper. Foram elas:  

- velocidade;
- simplicidade de uso;
- suporte robusto a desenvolvimento não linear;
- totalmente distribuído;
- eficiência para lidar com grandes projetos como o kernel do Linux;


# Comandos básicos do Git Bash

### Comandos 

- **git config** - Esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit.
- **git init** - O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.
- **git clone** - Esse comando Git cria uma cópia exata de um repositório já existente.
- **git add** - Esse comando Git adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados.
- **git commit** - O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.
