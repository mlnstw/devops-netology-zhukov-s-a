# devops-netology-zhukov s a
First edit

.terraform/ - будут проигнорированы все файлы в дирректории .terraform/

*.tfstate - будут проигнорированы все файлы имеющие 0 или несколько символов, а после .tfstate

\*.tfstate.\* - будут проигнорированы все файлы имеющие 0 или несколько символов, после .tfstate. и после 0 или несколько символов

*.tfvars - будут проигнорированы все файлы имеющие 0 или несколько символов, а после на конце .tfvars

*.tfvars.json - будут проигнорированы все файлы имеющие 0 или несколько символов, а после на конце .tfvars.json

override.tf - все файлы с таким именем

override.tf.json - все файлы с таким именем 

*_override.tf - будут проигнорированы все файлы имеющие 0 или несколько символов, а после на конце _override.tf

*_override.tf.json - будут проигнорированы все файлы имеющие 0 или несколько символов, а после на конце _override.tf.json

.terraform.tfstate.lock.info - все файлы с таким именем

.terraformrc - все файлы с таким именем (скрытые)

terraform.rc - все файлы с таким именем

