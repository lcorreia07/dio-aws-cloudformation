# Minha Primeira Stack com AWS CloudFormation

## 📌 Descrição da Stack

Este projeto tem como objetivo a criação de uma stack simples utilizando o AWS CloudFormation.  
A stack implementa um único recurso:

- Um bucket S3 privado chamado `lauane-bucket-exemplo-2025-09-28`

A proposta faz parte de um desafio da DIO para aplicar, na prática, os conceitos aprendidos sobre infraestrutura como código (IaC) com AWS.

---

## ▶️ Como Executar

Para criar esta stack na sua conta AWS, siga os passos abaixo:

1. Certifique-se de ter o AWS CLI instalado e configurado com suas credenciais.
2. Execute o comando abaixo no terminal, dentro da pasta onde está o arquivo `template-cloudformation.yaml`:

```bash
aws cloudformation create-stack --stack-name MinhaStack --template-body file://template-cloudformation.yaml


## 🧱 Estrutura da Stack
        Arquivo: template-cloudformation.yaml
        Este template define os seguintes recursos:

     ✅ Bucket S3
      Nome: lauane-bucket-exemplo-2025-09-28
      Permissões: Privado (Private)

     ✅ Output
      Retorna o nome do bucket criado ao final da execução da stack

## 🎓 Aprendizados

Durante a realização deste desafio, pude colocar em prática os seguintes conhecimentos:

 - Criação da minha primeira stack com AWS CloudFormation.
 - Estruturação de um template em formato YAML.
 - Compreensão de recursos como Resources e Outputs.
 - Uso do GitHub para versionamento e documentação de um projeto técnico.

## 🔗 Referências
https://docs.aws.amazon.com/cloudformation/
https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
