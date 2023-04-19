


### |============================ COMANDOS GIT ================================|



ls -a -> Listar a pasta exibindo todos os arquivos e pastas incluindo arquivos e pastas ocultos. utilizar este comando para certificar para que já não exista um arquivo .git criado.

rd .git /S/Q -> Elimina qlq arquivo .git de dentro da pasta. Isso evitará possíveis conflitos entre as versões.

git config --local ou --global -> com este comando informamos o nome de usuário(user.name) e o e-mail deste usuário(user.email). Usando --local podemos configurar e/ou alterar os dados apenas para 1 projeto, ja usando --global as configurações serão definidas para todos os projetos.

git init --bare -> Com este comando nós criamos um repositório que não terá a working tree, ou seja, não conterá uma cópia dos nossos arquivos. Como o repositório servirá apenas como servidor, para que outros membros da equipe sincronizem seus trabalhos, poupamos espaço de armazenamento desta forma.

git init -> Inicia um repositório. Após as verificações anteriores. Após este comendo será criada uma pasta .git contendo os arquivos que serão enviados para o repositório no GitHub.

git status -> Mostra o status dos arquivos no seu repositório local. Este comando nos dá toda informação necessária sobre a branch atual.

git add . -> Adiciona todos os arquivos no modo stage deixando-os preparados para a sequencia de envio para o repositório no GitHub.

git commit -m "informação sobre o envio" -> Este é o comando que define o ponto de verificação do projeto que está sendo enviado. Entre " " precisamos escrever uma mensagem do commit realizado. O git commit salva suas alterações no espaço de trabalho.

git log -> este comando nos mostra o histórico de commits realizados em nosso repositório. Existe várias opções de flags para o comando git log como --online, -p... Para mais informações podemos utilizar o comando git log --help e também em https://devhints.io/git-log

git remote -> lista os repositórios remotos que o seu repositório local conhece

git remote add origin http://...endereço do repositório no GitHub -> este comando será usado quando fizermos o primeiro envio do nosso repositório local(computador) para o repositório remoto(GitHub). Em caso de repositório
local devemos informar o caminho para a pasta onde foi criado o repositório. D:/...

git push -u origin master -> Este comando é o que finalmente envia nosso projeto para o repositório remoto. 

Quando ja temos um repositório no GitHub e realizamos alteração no mesmo, precisamos fazer um update neste repositório para que fique sempre atualizado com a última versão. Então utilizamos os comandos para envio na sequencia informada a seguir:
	git add .
	git commit -m "?mensagem?"
	git push -u origin master

	obs.: Utilizar sempre o git status entre os comandos listados acima para verificar o se todos os arquivos atualizados no repositório local(computador) serão enviados para o repositório remoto(GitHub).

Se deseja que o gitHub passe a ignorar certos arquivos ou pastas, crie um arquivo com o nome .gitignore e tudo o desejar que seja ignorado pelo monitoramento do gitHub deve ser especificado nele. Como por exemplo um nome de arquivo ou a pasta/.  



### |========================== OUTROS COMANDOS GIT ============================|


git repack -> Utilizei este comando quando tentei subir um projeto muito extenso(CursoJava_Udemy) e a memória do meu notebook não estava suportando o envio dando erro: "error rpc failed http 408 curl 92 stream error in the http/2 framing layer"



### |========================== URL's PARA PESQUISA ==============================|


https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/

https://www.youtube.com/watch?v=aINs3ouaoJk&t=248s
