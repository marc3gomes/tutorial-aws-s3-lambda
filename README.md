# Tutorial: Criar um gatilho do Amazon S3 para acionar uma função do AWS Lambda

Este repositório contém os arquivos gerados no tutorial "Criar um gatilho do Amazon S3 para acionar uma função do AWS Lambda" fornecido pela AWS. Este tutorial demonstra como configurar um gatilho no Amazon S3 que aciona uma função do AWS Lambda quando um novo arquivo é adicionado a um bucket do S3.

## Estrutura do diretório

- **lambda_function.py**: Este arquivo contém o código Python da função do AWS Lambda que será acionada quando um arquivo é adicionado ao bucket do S3.
- **event.json**: Este arquivo contém um exemplo de evento de gatilho que é enviado para a função do AWS Lambda quando um arquivo é adicionado ao bucket do S3.
- **README.md**: Este arquivo README fornece uma visão geral do conteúdo deste repositório.

## Pré-requisitos

- Uma conta da AWS.
- Acesso à AWS Management Console.
- Permissões para criar recursos da AWS, incluindo funções do AWS Lambda e buckets do Amazon S3.

## Como usar este código

1. Clone este repositório para o seu ambiente local.
```bash
git clone https://github.com/marc3gomes/tutorial-aws-s3-lambda.git
```

2. Acesse o diretório clonado:
```bash
    cd tutorial-aws-s3-lambda
```


3. Siga as instruções detalhadas no tutorial fornecido pela AWS:
[Tutorial: Criar um gatilho do Amazon S3 para acionar uma função do AWS Lambda](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/with-s3-tutorial.html).

## Contribuindo

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.
