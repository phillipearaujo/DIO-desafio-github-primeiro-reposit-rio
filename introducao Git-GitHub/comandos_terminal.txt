COMANDO TERMINAL Windows

dir -> listar as pastas(diretórios) e arquivos
cd + 'nome da pasta' -> acessa a pasta 'nome da pasta'
cd/ -> vai direto para a raiz do sistema (C: ou D:)
cd.. ->
cls -> limpa o terminal
cd.. -> retorna a pasta anterior(retorcede 1 nível)
mkdir -> criar uma nova pasta. Criamos a pasta workspace

echo 'hello' -> o comando echo faz com que a 'mensagem' seja exibida no terminal. Utiloizamos o mesmo comando para criar um aquivo. Neste exemplo vamos criar um arquivo .txt usando o comando " echo hello > hello.txt " dentro da pasta workspace.

del -> usando este comando e passando a pasta que criamos workspace ele irá deletar apenas o conteúdo interno da pasta e não a pasta em sí.

rmdir -> este comando exclui a pasta selecionada. Para fazer a exclusão da pasta workspace vamos utilizar " rmdir workspace /S /Q "

cls -> limpa o terminal

tecla TAB -> auto completar



COMANDO TERMINAL LINUX

ls -> listar as pastas(diretórios) e arquivos
	adicionando a flag -a será exibido as pastas ocultas.
cd + 'nome da pasta' -> acessa a pasta 'nome da pasta'
cd / -> vai direto para a raiz do sistema (C: ou D:)
cd .. -> retorna a pasta anterior(retorcede 1 nível)
clear / Ctrl+l -> limpa o terminal
cd .. -> retorna a pasta anterior(retorcede 1 nível)
mkdir -> criar uma nova pasta

echo 'hello' -> o comando echo faz com que a 'mensagem' seja exibida no terminal. Utilizamos o mesmo comando para criar um aquivo. Neste exemplo vamos criar um arquivo .txt usando o comando " echo hello > hello.txt " dentro da pasta workspace.

rm -rf -> este comando exclui a pasta selecionada juntamente com todas as pastas contidas nela. Ainda na raiz do diretório vamos utilizar " rm -rf workspace " e será excluido a pasta e todas subpastas contidas em seu interior. Para excluir apenas um arquivo dentro de qualquer pasta somente utilizar o comando rm+arquivo

clear / Ctrl+l -> limpa o terminal

tecla TAB -> auto completar