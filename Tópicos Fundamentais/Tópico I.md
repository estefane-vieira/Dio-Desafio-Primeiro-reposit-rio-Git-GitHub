### Tópicos essenciais 



* *Git* init - **iniciar**

* *Git* add - **adicionar**

* *Git* commit - **criar o commit**

  ****

   ### Processo para se gerar uma chave SSH
  
  
  
   Git Bash
   Par de chaves
   ssh-keygen -t ed25519 -c  **"email"**
  
   cd /c/Users/**Sthev**/ .ssh/
   ls
   cat id_ed25519.pub
  
   #### Depois volta no github
  
  eval $(ssh-agent -s)
  ssh-add id_ed25519
  
  
  
