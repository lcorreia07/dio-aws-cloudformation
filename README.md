# 🚀 Minha Primeira Stack com AWS CloudFormation

## Introdução
Este repositório documenta a implementação da minha primeira stack utilizando AWS CloudFormation, conforme o desafio proposto na plataforma DIO. Compartilho aqui o passo a passo, insights e aprendizados obtidos durante a prática.

## Objetivos do Projeto
- Aplicar os conceitos aprendidos sobre AWS CloudFormation.
- Construir uma stack simples e funcional na AWS.
- Documentar o processo de forma clara e estruturada.
- Compartilhar o material no GitHub para futuras referências.

## Descrição da Stack
Nesta implementação, criei uma stack que inclui:
- Um bucket S3 com acesso privado.
- Configurações principais aplicadas.

## Passo a Passo da Implementação
1. Criação do arquivo `template-cloudformation.yaml`.
2. Validação do template com AWS CLI.
3. Deploy da stack via Console AWS e AWS CLI.
4. Verificação dos recursos criados.
5. Análise dos resultados e ajustes finais.

## Aprendizados e Insights
- Importância da infraestrutura como código para automação e repetibilidade.
- Cuidados na definição de parâmetros e outputs no template.
- Desafios enfrentados e soluções encontradas.

## Como Executar
Para criar a stack na sua conta AWS, utilize o comando AWS CLI:

```bash
aws cloudformation create-stack --stack-name MinhaStack --template-body file://template-cloudformation.yaml --parameters ParameterKey=KeyName,ParameterValue=meu-keypair
