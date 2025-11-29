# devops-netology

В файле /Terraform/terraform.gitignore игнорируются:

- .terraform/ - игнорируется папка с именем .terraform
- *.tfstate - все файлы с расширением .tfstate, 
- а так же *.tfstate.* - все файлы, где имя начинается с любого текста, затем .tfstate. и любой текст после
- crash.log - файл с именем crash.log, а так же crash.*.log - файлы, где имя начинается с crash., затем любой текст, и заканчивается на .log
- *.tfvars - все файлы с расширением .tfvars
- *.tfvars.json - все файлы с расширением .tfvars.json
- override.tf - файл с именем override.tf
- override.tf.json - файл с именем override.tf.json
- *_override.tf - файлы, где имя заканчивается на _override.tf
- *_override.tf.json - файлы, где имя заканчивается на _override.tf.json
- .terraform.tfstate.lock.info - файл с именем .terraform.tfstate.lock.info
- .terraformrc - файл с именем .terraformrc
- terraform.rc - файл с именем terraform.rc

Символ * в правилах означает любой текст любой длины (включая пустой)
