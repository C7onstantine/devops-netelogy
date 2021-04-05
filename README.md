# devops-netelogy
# ddd

#Буду игнорироваться *.dll и *.exe и закомпилиный исходники
#Так же старые версии файлов с расширением *.backup

#-- описание файла Terraform.gitignore
#*.tfvars -- убираем файлы с личными данными
#override.tf -- я так понял этот файл используеться одновремнно многими компанентами, перегружен!?
#override.tf.json -- то же самое только файл .json , следует скрипт  с чем!?
# *_override.tf -- то же самое только файл .json
# *_override.tf.json -- то же самое только файл .json
#.terraformrc -- Ignore CLI configuration files
#terraform.rc -- Ignore CLI configuration files