# Downloaded these specific files or only one folder from github repo with Git Sparse

           git clone --filter=blob:none --no-checkout https://github.com/CloudWithVarJosh/Jenkins-Basics-To-Production.git
           cd Jenkins-Basics-To-Production
           git sparse-checkout init --cone
           git sparse-checkout set "Project 01/project_files"
           git checkout main
