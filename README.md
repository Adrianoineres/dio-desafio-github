# 📚Desafio de Projeto
sobre Git/GitHub da DIO
Repositório criado para o Desafio de projeto, incluir
todas as atividades da [Digital Innovaion - DIO](https://web.dio.me/home),
executados pelo Bootcamp
Otávo Reis Frontend Developer.

## 📑Atividades

Abaixo, todas as atividades do Bootcamp Otávo
Reis Frontend Developer: 

- Introdução ao Git e ao Github;
- [Entendendo o que é Git e sua importância](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Realizando a instalação do GIT](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/014fe14a-dc5a-41ec-9965-755a79694f27?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Objetos internos do Git](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/02d99abe-e83c-4800-9100-a4258119a781?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Chave SSH e Token](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/7410b862-1989-421a-a48d-500db5857f53?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Iniciando o Git e criando um commit](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/12607816-1128-4906-9645-cbe0f7fcc72b?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Passo a passo no ciclo de vida](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/54cd3040-b3d1-4e91-aea3-e3b031367774?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Trabalhando com o GitHub](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/00c82124-1594-49e8-9f82-4d8c85aa5a48?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Tópicos fundamentais para entender o funcionamento do Git](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/0f9c0907-c8dd-4cf4-b9f5-05f5dd486875?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Como os conflitos acontecem no GitHub e como resolvê-los](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/4895182a-ae5a-44e3-8f12-daa9861ab035?back=/track/orange-tech&tab=undefined&moduleId=undefined)
- [Criando seu primeiro repositório no Github para compartilhar seu progresso; 📎](https://web.dio.me/course/como-entregar-seu-desafio-de-projeto/learning/488fc49a-0738-4e9d-bf87-ea22d2591fde?back=/track/orange-tech&tab=undefined&moduleId=undefined) 
-  📎 [Certificado](https://www.dio.me/certificate/8B22BA3A/share)

### 🔑Algumas Coisas Importantes

Comandos importantes do Prompt de Comando (também utilizado no Git):

- `cls(win), clear(git, linux)` - para apagar todo o histórico de comandos do prompt;

- `cd(win, git, linux)` - para se transitar entre as pastas dos diretórios, também há a variante "cd .." para retornar à pasta anterior;

- `dir(win), ls(git, linux)` - para mostrar a lista de diretórios contidos na pasta em que estiver, também há a variante dir -a(win), ls -a(git, linux) para mostrar inclusive os diretórios ocultos ;

- `mkdir(win, git, linux)` - para criar uma pasta no diretório;

- `echo(win, git, linux)` - retorna o que for inserido, entretanto se utilizado como "echo > nome.extensão", ele cria o arquivo na extensão desejada, ótimo para criar um readme bem rápido sem sair do git em?! :happy:

- `start(win, git, linux`) - inicia um arquivo executável de qualquer tipo;

- `TAB` - Sim, a tecla TAB tem a incrível função de abreviar algo que você deseja escrever, extremamente útil e vai agilizar muito a sua vida!

### Comandos de iniciação do Git:

- `git init` - inicia o versionamento na pasta em que estiver;
- `git config --global user.email "email"` - configura o ambiente de versionamento para todos os repositórios, com essa identificação de e-mail; em caso da necessidade de alterar isso posteriormente, use git config --global unset user.email;
- `git config --global user.name "username"` - configura o ambiente de versionamento para todos os repositórios, com essa identificação de usuário no github (é importante ressaltar que os dados aqui, devem refletir o usuário no Github); em caso da necessidade de alterar isso posteriormente, use git config --global unset user.name
- `git config --list` - mostra todos os parâmetros da configuração atual do Git; para sair, use a tecla q;
- `git remote add nome (link)` - direciona seu repositório local para um repositório na nuvem, o parâmetro NOME é apenas um apelido para que você possa referenciar o link sem tê-lo que mencionar novamente; você também pode posteriormente utilizar o comando `git remote -v` para consultar o repositório que está recebendo os arquivos locais.
  
  ##### A configuração do ambiente com Git/Github com chave SSH:

Use o código abaixo no Git, para gerar uma chave SSH;

`<u>$ ssh-keygen -t ed25519 -C "seu_email@example.com"</u>`
cat (chave gerada) - use esse comando (git, linux) para "ler" o conteúdo da chave, em seguida vá até a página principal no Github>settings>SSH and GPG keys>New SSH key em seguida insira o seu conteúdo da chave no campo "key".

Calma que ainda não acabou!😆 Agora no Git Bash, você precisa executar o agente para que gerencie suas chaves.

`$ eval "$(ssh-agent -s)"`
A saída do comando será "> Agent pid (número_qualquer)", o agente continuará executando em segundo plano. Agora como última etapa, você deve passar a chave privada para o agent com o seguinte código:

`$ ssh-add "chave privada"`
Pronto!🤝 Agora você pode usar todas as funcionalidades do git sem precisar se identificar o tempo todo.

O editor de arquivos Markdown(.md), muito útil para o Github:

[Typora - clique aqui para baixar o Typora;](https://typora.io/)
[Lista completa de emoticons]()💀😃💥;

