
# DIO RESUMO GIT GITHUB

Repositório para armazenar resumos sobre git e github do curso de versionamento  de código git e github da DIO
[Digital inovation One](https://web.dio.me/course/bootcamps-dio-educacao-gratuita-e-empregabilidade-juntas/learning/69d466f2-65e7-4799-b5d9-1074a9884313?back=/track/santander-bootcamp-2023-ciencia-de-dados-com-python)
## 📚📙 Documentação
- [Documentação git](https://git-scm.com/doc)
- [Documentação github](https://docs.github.com/pt/get-started)

## 💻 Resumos Aulas
### Diferença entre git X github📌
**git**: Responsável por controlar e gerenciar todas as versões de um arquivo

**github**: Responsável por hospedar o seu código em servidor remoto



| Comando | Explicação |
| ----- | -------|
 git clone |Clona o Repositório do Servidor para a sua maquina
cat| Exibe o conteudo do seu arquivo|
git config --global credential.helper store| Ele permite que voce clone um Repositório para a sua máquina sem precisar de uma autenticação 
ls | lista  todos os arquivos existentes naquele diretório|
ls -al ~/.SSH| verifica a existência de uma chave SSH
touch reademe.md| criar um reademe vazio|
git status | fornece informações de quais arquivos foram adcionados,modificados  e também pastas novas adicionadas|
gitigonre| utilizado para ignorar uma pasta especifca|
touch nomearquivo.extensao | Adiciona um arquivo na pasta desejada,sempre vazia e não realiza o controle de versao|
git add nomeArquivo.extensao |Adiciona arquivo e controla o versionamento do mesmo|
git commit -m |Responsavel por criar um checkpoint ao longo do seu projeto registrando mudanças que ocorrem ao longo do tempo|
rm -rf .git | removendo o versionamento de uma pasta|




## Transformando um Repositório local em remoto
Criação de uma pasta em um diretório desejado:

- MKdir nomePasta
 
 inicialização daquele Repositório:

 - git init
 
 acessando a pasta desejada:
 - cd nomePasta/
conectando a pasta ao Repositório do servidor remoto:
 - git remote add origin URL

<img src= "https://github.com/julianoAlessandro/Bootcamp-DIO-GitGitHUB/assets/111141842/ba677f00-d83b-43ed-8184-512320deafc1"><br>
<img src="https://github.com/julianoAlessandro/Bootcamp-DIO-GitGitHUB/assets/111141842/2cc7ebe6-f746-40ba-b6c4-d2614a3a9f3e">

