# Arquivos-para-o-gitHub

Enviar arquivos ao github, para isso precisa baixar o https://git-scm.com/        
abrir a pasta do arquivo e selecionar Git Bash here                                    
                                                                                
 ### Para subir Arquivos para o GuitHub

	//para criar um novo repositoria na linha de comando
	git init 
	git add README.md
	git commit -m "first commit"
	git banch -M main
	git remote add origin https://github.com/...........
	git push -u origin main

ou

	//pode ser assim tambem                                                                                        
	git config --global user.name "Nome do seu github"                                     
	git config --global user.email "E-mail usado no github"                                
	git init                                                                               
	git add .                                                                              
	git branch -M main                                                                     
	git commit -am "First Commit"                                                          
                                                                                       
dentro da sua pasta no guithub existe esta de texto                                
…or push an existing repository from the command line                          
pegue o link abaixo 	                                                           
pegueas a que esta com o link que começa assim https:// 		                   
										                                               
	git remote add origin https://github.com/ essa parte é seu URL depois do origin                                            
	git branch -M main                                                                     
	git push -u origin main                                                                
                                                                                       
se tudo deu certo até aqui, então vai pedir seu nome do gitHub                     
"Seu Nome"                                                                         
então "Sua Senha"                                                                  
aceite os termos caso peça e pronto seu arquivo já subiu.                          
										                                               
*************************************************************************************************
-------------------------PARA ATUALIZAR HEADME NO GITHUB
			                              										                                           
emogis:    https://emojipedia.org/                                                     
Guia básico de Markdown: https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open
*************************************************************************************************
-------------------------PARA ATUALIZAR O PROJETO NO GITHUB			       
                                                                                       
git status
git add .
git commit -a -m "Atualização 0.1"
git push origin main

Se der erro use

git add -A
git push -u origin main

*************************************************************************************************

git pull origin main

git push origin main
*************************************************************************************************
-------------------------LISTA DE COMANDOS GITHUB

**git status** 	– Mostra o status da sua branch, lista os arquivos modificados, deletados ou criados.

**git add - A** - Adiciona todos as alterações (elege elas a serem fazerem parte do commit).

**git commit -m “primeiro commit”** – Commita os arquivos (salva eles na sua branch).

**git checkout -b nome-da-sua-nova-branch** – Cria uma nova branch.

**git checkout nome-outra-branch** - Troca de Branch.

**git merge nome-da-branch** – Mescla a branch especificada com a atual.

**git pull origin nome-da-branch** – Baixa todos os arquivos diferentes da branch remota especificada para sua máquina.

**git push origin nome-da-branch** – Envia os arquivos commitados para o servidor.

**git remote add origin link-do-repositorio** – Adiciona um repositório remoto.

**git reset –hard origin/nome-da-branch** – Descarta todas as alterações locais e deixa como no repositório remoto.
