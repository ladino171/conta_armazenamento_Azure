# conta_armazenamento_Azure
Este repositorio contem um resumo do aprendido durante o devenvolvimento do lab na DIO.

Seguindo pelo training do microsoft.

https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/1-introduction

## Criando um blob de armazenamento

# Criar uma conta de armazenamento

Nesta tarefa, você criará uma nova conta de armazenamento.

Entre no portal do Microsoft Azure em https://portal.azure.com

Selecione Criar um recurso.

Em Categorias, selecione Armazenamento.

Em Conta de armazenamento, selecione Criar.

Na guia Básica do painel Criar conta de armazenamento, preencha as informações a seguir. Mantenha os padrões para todo o resto.

![image](https://github.com/user-attachments/assets/2b4df444-5013-4b2c-ab42-7834a19764de)

Na guia Avançado da folha Criar uma conta de armazenamento, preencha o seguinte informações. Mantenha os padrões para todo o resto.

![image](https://github.com/user-attachments/assets/d56a0e57-5fe3-4821-abb3-4a6032317664)

Selecione Examinar para examinar as configurações da conta de armazenamento e permitir que o Azure valide a configuração.

Após a validação, selecione Criar. Aguarde a notificação de que a conta foi criada com sucesso.

Selecione Ir para o recurso.

## Trabalhar com o armazenamento de blobs

Nesta seção, você criará um contêiner de Blob e carregará uma imagem.

Em Armazenamento de dados, selecione Contêineres.

![image](https://github.com/user-attachments/assets/df45c7c0-bcd1-4510-85ed-beb8d5ef18c2)

Selecione + Contêiner e preencha as informações.

![image](https://github.com/user-attachments/assets/e7469fd3-1b71-4132-9c08-6f16edfc2ef9)

Selecione Criar.

De volta ao portal do Azure, selecione o contêiner que você criou e clique em Carregar.

Procure o arquivo de imagem que você quer carregar. Selecione-a e depois carregue.

## Observação

# Você poderá carregar quantos blobs quiser dessa maneira. Novos blobs serão listados no contêiner.

Selecione o Blob (arquivo) que você acabou de carregar. Você deve estar na guia propriedades.

Copie a URL do campo de URL e cole-a em uma nova guia. Você receberá um uma mensagem de erro semelhante à mostrada a seguir.

![image](https://github.com/user-attachments/assets/f099d695-7995-45aa-b170-517b2661b72a)

## Altere o nível de acesso do blob

Retorne ao portal do Azure.

Selecione Alterar nível de acesso.

Defina o nível de acesso anônimo como Blob (acesso de leitura anônimo somente para blobs).

![image](https://github.com/user-attachments/assets/126b529b-28e2-484b-9038-ca7b480e31cc)

Selecione OK.

Atualize a guia em que você tentou acessar o arquivo anteriormente.

Parabéns, você concluiu este exercício. Você criou uma conta de armazenamento, adicionou um contêiner a ela e depois carregou blobs (arquivos) no contêiner. Depois, você alterou o nível de acesso para poder acessar o arquivo pela Internet.


# Essa e uma simples demonstracao de um item dos servicos do armazenamento do Azure. 





