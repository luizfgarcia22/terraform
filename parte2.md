Descrição do cenário

O usuário acessa a aplicação web que distribui o conteúdo estático do bucket S3 via Cloudfront. Após isso as informações são filtradas pelo API Gateway para serem direcionadas a função Lambda que acessa diretamente o Banco DynamoDB. Ambos recursos estão alocados na VPC que após a verificação da NACL ( Ntwork Access Control List) são acessados com sucesso.