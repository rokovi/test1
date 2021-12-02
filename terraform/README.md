### ***Будут проигнорированы все вложенные и скрытые каталоги .terraform:***
```console
**/.terraform/*
```
### ***Будут проигнорированы любые файлы с расширением .tfstate и .tfstate. после символа . :***
```console
*.tfstate
*.tfstate.*
```
### ***Будут проигнорированы файлы(рекурсивно) crash.log:***
```console
crash.log
```
### ***Будут проигнорированы любые файлы с расширением .tfvars:***
```console
*.tfvars
```
### ***Будут проигнорированы файлы(рекурсивно) override.tf, override.tf.json, любое кол-во символов перед _override.tf, любое кол-во символов перед _override.tf.json***
```console
override.tf
override.tf.json
*_override.tf
*_override.tf.json
```

### ***Будут проигнорированы файлы(рекурсивно) terraform.rc и скрытый файл .terraformrc
```console
.terraformrc
terraform.rc
```