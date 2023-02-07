# terraform init

O comando acima vai inicializar o diretório de trabalho atual e configurar o backend com os providers que foram disponibilizados no arquivo provider.tf.

# terraform fmt

Com esse comando iremos formatar o códido dentro dos arquivos para deixar tudo mais elegante.

# terraform validate

# Podemos usar o comando acima para validar nossas configurações. 
Se estiver tudo ok, uma será exibida uma mensagem informando que as configurações são válidas.

# terraform plan

Com esse comando, podemos ter uma prévia da infraestrutura que será criada.

# terraform apply --auto-approve

Com esse outro comando, finalmente subimos a infra para a AWS.

# terraform destroy --auto-approve

Esse comando destroi/exclui tudo que foi criado e subido para a AWS.
