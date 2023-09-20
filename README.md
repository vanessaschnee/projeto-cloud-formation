# Projeto Cloud Formation - Ada Tech

Implantação de WordPress com Amazon ECS usando AWS CloudFormation

Criação de uma pilha do AWS CloudFormation para implantar um ambiente altamente disponível do WordPress usando o Amazon ECS (Elastic Container Service).

O ambiente inclui um cluster ECS, uma definição de tarefa, um serviço, um balanceador de carga, dimensionamento automático e um sistema de arquivos EFS para armazenar dados persistentes do WordPress.

- No template do CloudFormation, estão definidos os seguintes recursos:
  Um cluster ECS para hospedar os containers do WordPress.
  Uma definição de tarefa que especifica como os containers do WordPress serão configurados.
  Um serviço ECS para garantir que a tarefa do WordPress seja sempre executada.
  Um balanceador de carga para distribuir o tráfego entre os containers.
  Configurações de dimensionamento automático para ajustar automaticamente o número de containers com base na carga.
  Um sistema de arquivos EFS para armazenar dados persistentes do WordPress.

  - No template, utilizei parâmetros para permitir a personalização durante a criação da pilha e coloquei comentários sobre cada funcionalidade.  
  - A implantação da pilha foi através do Console.  
