# devops-netology-zhukov-s-a
First edit

.terraform/ создается при использовании команды terraform init, имеет большой вес

*.tfstate
*.tfstate.* создаются при terraform apply, могуи содержать секреты

crash.log
crash.*.log логи, не нужно в репозитории

*.tfvars
*.tfvars.json хранятся значения переменных, могут содержать пароли

override.tf
override.tf.json
*_override.tf
*_override.tf.json переопределение ресурсов

.terraformrc
terraform.rc настройки пользователя


