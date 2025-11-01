# ☁️ Implementando Infraestrutura Automatizada com AWS CloudFormation

## 📘 Descrição do Projeto
Este repositório foi criado como parte do **Desafio da DIO (Digital Innovation One)**, com o objetivo de implementar uma **infraestrutura automatizada** utilizando **AWS CloudFormation**.  

O projeto documenta todo o processo de criação de Stacks na AWS, servindo como material de apoio para estudo e futuras implementações de **Infrastructure as Code (IaC)**.

---

## 🎯 Objetivos de Aprendizagem

- ✅ Aplicar conceitos de CloudFormation em um ambiente prático;  
- ✅ Criar e implementar Stacks a partir de templates YAML;  
- ✅ Automatizar recursos AWS de forma segura e padronizada;  
- ✅ Documentar processos técnicos e insights adquiridos;  
- ✅ Compartilhar o projeto no GitHub como portfólio técnico.

---

## ⚙️ Tecnologias e Serviços Utilizados

| Serviço | Descrição |
|---------|-----------|
| **AWS CloudFormation** | Criação e automação de infraestrutura como código (IaC) |
| **AWS S3** | Armazenamento de arquivos (opcional para o projeto) |
| **AWS EC2** | Instâncias de servidores virtuais (opcional) |
| **AWS IAM** | Gestão de permissões e papéis |
| **YAML / JSON** | Linguagem usada para criar templates CloudFormation |

---

## 🧠 Conceitos Principais

- **Stack:** conjunto de recursos AWS gerenciados como uma única unidade.  
- **Template:** arquivo YAML ou JSON que define os recursos da Stack.  
- **Parameters, Resources e Outputs:** principais seções de um template CloudFormation.  
- **Infrastructure as Code (IaC):** prática de automatizar recursos de infraestrutura via código.  

---

## 🛠️ Passo a Passo da Implementação

1. Acessar o console **AWS CloudFormation**.  
2. Criar o arquivo de template `template.yml` definindo os recursos desejados.  
3. Fazer upload do template no console ou via **AWS CLI**.  
4. Configurar parâmetros, nome da Stack e permissões (IAM Role).  
5. Criar a Stack e aguardar o provisionamento dos recursos.  
6. Validar os recursos criados (S3, EC2, etc.).  
7. (Opcional) Excluir a Stack após o teste para evitar custos.

---

## 🖼️ Exemplo de Template YAML

```yaml
AWSTemplateFormatVersion: '2010-09-09'
Description: Template de exemplo para criar um bucket S3

Resources:
  MeuBucketS3:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: meu-bucket-exemplo-cloudformation
