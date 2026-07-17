## Terminal: Manipulação de Diretórios e Arquivos

# Atalhos

Na manipulação de diretórios através do terminal o tab é nosso melhor amigo. Na manipulação de diretórios alguns atalhos são interessantes de serem usados, principalmente quando falamos de navegabilidade, apesar do tema ser bem básico vale apena destrincha-lo de forma inteligente. Pensando nisso logo após alguns exemplos de atalhos de navegabilidade na manipulação de diretórios veremos os comandos de criação:

- Tab: O tab é um ótimo atalho, ele serve para completar comandos assim facilitando e agilizando no processo de navegação.

- --help: O --help é um comando utilizado no terminal que serve para identificar outros comandos e ajudar a entender as suas funções, ele é utilizado como um parâmetro sendo o primeiro comando o comando que será detalhado ao usuário.

- cat: O cat é um comando utilizado no terminal que exibe arquivos de texto diretamente no terminal, podendo até mesmo exibir e criar arquivos texto direto no terminal.

- man: O man segue a mesma linha do --help a diferença é que ele é utilizado como comando e não como parâmetro, sendo assim o segundo comando é oque será detalhado ao usuário.

# Comandos de criação

Alguns comandos são destinados a criação de pastas ou arquivos. Para entender melhor sobre o tema, achei interessante separalo em comandos de criação, exclusão e manipulação, sendo assim vamos aos comandos que são destinados a criação dentro do terminal Linux:

- mkdir: O mkdir é um comando destinado a criação de pastas, podendo criar diversas pastas e subpastas em um só comando, pode ser usado em conjunto ao nome da pasta que será criada "mkdir pasta1" ou pode criar mais de uma pasta com a mesma linha de raciocínio "mkdir pasta1 pasta2 pasta3", seguindo essa logicá o mkdir também cria pastas dentro de pastas utilizando o parâmetro -p "mkdir -p pasta1/pasta2/pasta3".

- cp: O comando cp copia pastas ou arquivo já existente e a cria em outro diretório ou no mesmo diretório, pode ser usado em conjunto ao nome do arquivo e jogado a outro diretório "cp arquivo1.txt Downloads/" também pode ser copiada no mesmo diretório com nome diferente "cp arquivo1.txt arquivo1(2).txt", quando utilizamos para copiar pastas completas é um pouco diferente utilizando o parâmetro -r "cp -r pasta1/ Downloads".

- touch: Touch cria um arquivo txt totalmente vazio, o modo de uso é bem simples "touch notas.txt".

# Comandos de exclusão

Os comandos de exclusão como diz o nome é destinado a excluir arquivos e pastas. Os comandos de exclusão são perigosos porém necessários, alguns exemplos são valídos:
 
- rm: O rm remove pasta ou arquivos atráves do terminal, a forma de utilizar é bem simples "rm notas.txt" remove arquivos, "rm arquivo1.txt arquivo2.txt" remove multriplos arquivos, "rm -r pasta1/" apaga uma pasta inteira, "rm -rf pasta1/" apaga a força sem nenhuma verificação.

- userdel e groupdel: userdel exclui usuários do sistema, o modo de usar é bem básico "sudo userdel -r fulano" deleta só o usuário e "sudo groupdel fulanopasta" exclui os arquivos do usuário.

- shred: O shred Sobrescreve o arquivo várias vezes e depois deleta ele, impedindo com que ajá alguma recuperação a esses arquivos, a fomra de usar é bem facíl "shred -u arquivo1.txt".

# comandos de manipulação e navegabilidade

Por ultimo os comandos mais utilizados quando se falamos de manipulação de diretórios. Os comandos de navegabilidade e manipulação inclui comandos destinados a entregar dados relacionados a navegação como por exemplo o ls e mover conteúdos aos seus destinos, exemplos:

- cd: O cd é utilizado para entrar em pastas, sendo literalmente a navegabilidade do terminal, alguns parâmetros são muito úteis tipo "cd .." que volta ao diretório anterios ou o "cd ~" que volta a pasta home.

- ls: O comando ls mostra os arquivos e pastas presentes no diretório, ele é utilizado de forma base "ls" alguns parametros também são apĺicados como por exemplo o -l que mostra detalhes sobre as pastas e arquivos.


- mv: O comando mv move arquivos e pastas ao destino desejado, utilizamos da seguinte forma "mv arquivo caminho", alguns parâmetros como o -f força a substituição de arquivos com mesmo nome.

- pwd: O comando pwd te devolve o caminho até o diretório onde foi chamado, geralmente é utilizado sem parâmetros.
