Criar pasta: mkdir


Criar arquivo: echo

echo hello > hello.txt



Deletar arquivos: dell (nome da pasta)

Deletar pasta: rmdir (nome da pasta) /S /Q


SHA1: siginifica Hash Algorithm (algoritmo de hash seguro), é um conjunto de funções hash criptograficas projetadas pela NSA
(Agencia Nacional de Segurança dos Estados Unidos).

A encriptação gera conjunto de caracteres de 40 digitos.


Objetos fundamentais: blobs
			    trees
			    commits

Blob sendo o bloco básico de composição, a Tree armazenando e apontando para os tipo de blobs diferentes.
 ...

O blob guarda o SHA do arquivo, que são os caracteres indentificadores daquele arquivo.

A arvore aponta para um blob e ela também guarda o nome desse arquivo. Responsável por montar toda a estrutura de onde estão localizados esses arquivos. 
Pode apontar para blobs ou outras árvores.

Commit, objeto que vai juntar tudo. Aponta para uma árvore, aponta para o ultimo commit antes dele, aponta para oa autor. Tem um carimbo de tempo, tem data e hora de quado foi criado e também possui SHA1.



Chave SSH: forma de se conectar de uma forma segura e encriptada entre duas maquinas.

chave publica + chave privada


Token de acesso pessoal: gera um token que deve ser salvo em localseguro. (quando tem token, usa HTTPS para clonar)

get clone (url)

Gitnit: ela inicia um conceito do git chamado repositório.

Tracked: unmodified

git status: verificar o status dos arquivos.
