# Cheatsheet DevOps Lab

## Vagrant
vagrant up          # Démarrer la VM
vagrant ssh         # Se connecter à la VM
vagrant halt        # Éteindre la VM
vagrant destroy     # Supprimer la VM

## Git
git clone <url>                    # Cloner un repo
git add .                          # Ajouter tous les fichiers
git commit -m "message"            # Commiter
git push                           # Pousser sur GitHub
git status                         # Voir l'état du repo

## Docker
docker ps                          # Lister les conteneurs actifs
docker run <image>                 # Lancer un conteneur
docker stop <id>                   # Arrêter un conteneur
docker images                      # Lister les images

## Ansible
ansible --version                  # Vérifier la version
ansible-playbook playbook.yml      # Lancer un playbook

## Terraform
terraform init                     # Initialiser
terraform plan                     # Prévisualiser
terraform apply                    # Appliquer
terraform destroy                  # Supprimer
