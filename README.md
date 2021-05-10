# не будут проигнорированы файлы .terraform во всех директориях
**/.terraform/* 

# файл с данным расширением будет проигнорирован во всех директориях
*.tfstate

# файл с данным расширением будет проигнорирован во всех директориях. Последний символ говорит, что после точки может быть сколько угодно символов.
*.tfstate.*

# игнорирование файла во всех директориях
crash.log

# файл с данным расширением будет проигнорирован во всех директориях
*.tfvars

# игнорирование файла во всех директориях
override.tf

# игнорирование файла во всех директориях
override.tf.json

# игнорирование файлов во всех директориях которые заканчиваются на _override.tf
*_override.tf

# игнорирование файлов во всех директориях которые заканчиваются на _override.tf.json
*_override.tf.json

# игнорирование данного файла во всех директориях
.terraformrc

# игнорирование данного файла во всех директориях
terraform.rc
