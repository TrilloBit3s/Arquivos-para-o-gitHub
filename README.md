# Arquivos-para-o-gitHub

Enviar arquivos ao github, para isso precisa baixar o https://git-scm.com/        
abrir a pasta do arquivo e selecionar Git Bash here                                    
                                                                                
 ### Para subir Arquivos para o GuitHub
                                                                                       
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
										                                               
*************************************************************************************************************
           	           PARA ATUALIZAR HEADME NO GITHUB			                        
       										                                           
emogis:    https://emojipedia.org/                                                     
Guia básico de Markdown: https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open
*************************************************************************************************************

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

*************************************************************************************************************

				LISTA DE COMANDOS GITHUB			       
                                                                                       
    -v, --verbose         be more verbose                                              
    -q, --quiet           be more quiet                                                
    --progress            force progress reporting                                     
    --recurse-submodules[=<on-demand>]                                                                                                      
    -r, --rebase[=(false|true|merges|preserve|interactive)]                        
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --signoff[=...]       add a Signed-off-by trailer
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --cleanup <mode>      how to strip spaces and #comments from message
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after
    -s, --strategy <strategy>                    
    -X, --strategy-option <option=value>                       
    -S, --gpg-sign[=<key-id>]                       
    --allow-unrelated-histories  
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --shallow-since <time>                     
    --shallow-exclude <revision>                      
    --deepen <n>          deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap
    -o, --server-option <server-specific>                    
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --negotiation-tip <revision>                         
    --show-forced-updates                          
    --set-upstream        set upstream for git pull/fetch
