

|==============================================================================================================================================================||======================================================================== COMANDOS GIT ========================================================================|
|==============================================================================================================================================================|


ls -a -> Listar a pasta exibindo todos os arquivos e pastas incluindo arquivos e pastas ocultos. utilizar este comando para certificar para que já não exista um arquivo .git criado.

rd .git /S/Q -> Elimina qlq arquivo .git de dentro da pasta. Isso evitará possíveis conflitos entre as versões.

git init -> Inicia um repósitório. Após as verificações anteriores. Após este comendo será criada uma pasta .git contendo os arquivos que serão enviados para o repositório no GitHub.

git status -> Mostra o status dos arquivos no seu repósitório local. Este comando nos dá toda informação necessária sobre a branch atual.

git add . -> Adiciona todos os arquivos no modo stage deixando-os preparados para a sequencia de envio para o repositório no GitHub.

git commit -m "informação sobre o envio" -> Este é o comando que define o ponto de verificação do projeto que está sendo enviado. Entre " " precisamos escrever uma mensagem do commit realizado. O git commit salva suas aletrações no espaço de trabalho.

git remote add origin http://...endereço do repositório no GitHub -> este comando será usado quando fizermos o primeiro envio do nosso repositório local(computador) para o repositório remoto(GitHub).

git push -u origin master -> Este comonado é o que finalmente envia nosso projeto para o repositório remoto. 

Quando ja temos um repositório no GitHub e realizamos alteração no mesmo, precisamos fazer um update neste repósitório para que fique sempre atualizado com a última versão. Então utlizamos os camandos para envio na sequencia informada a seguir:
	git add .
	git commit -m "?mensagem?"
	git push -u origin master

	obs.: Utilizar sempre o git status entre os camonados listados acima para verificar o se todos os arquivos atualizados no repositório local(computador) serão enviados para o repositório remoto(GitHub).



|==============================================================================================================================================================||==================================================================== OUTROS COMANDOS GIT =====================================================================|
|==============================================================================================================================================================|

git repack -> Utilizei este comando quando tentei subir um projeto muito extenso(CursoJava_Udemy) e a memória do meu notebbok não estava suportando o envio dando erro: "error rpc failed http 408 curl 92 stream error in the http/2 framing layer"




|==============================================================================================================================================================||==================================================================== URL's PARA PESQUISA =====================================================================|
|==============================================================================================================================================================|

https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/

https://www.youtube.com/watch?v=aINs3ouaoJk&t=248s
