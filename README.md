# devops-netology

В файле /Terraform/terraform.gitignore игнорируются:

- Директории .terraform/ и их содержимое
- Файлы состояний Terraform (*.tfstate, *.tfstate.*)
- Логи аварийных завершений (crash.log, crash.*.log)
- Файлы переменных (*.tfvars, *.tfvars.json) - так как могут содержать секреты
- Файлы переопределений (override.tf, *_override.tf)
- Файлы локов Terraform (.terraform.tfstate.lock.info)
- Конфигурационные файлы CLI (.terraformrc, terraform.rc)
