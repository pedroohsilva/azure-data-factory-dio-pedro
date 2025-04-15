# 🚀 Azure Data Factory (ADF) | Projeto DIO

Este repositório contém o passo a passo detalhado para criação e configuração de um recurso **Azure Data Factory (ADF)** no Azure, realizado como parte do projeto do Bootcamp Microsoft AI for Tech - Azure Databricks (DIO).

![image](https://github.com/user-attachments/assets/4d10ff8e-2b86-45ae-a7a8-3d4f1647f1e1)


## 📌 Introdução

O Azure Data Factory é uma plataforma de integração de dados na nuvem da Microsoft que permite criar, agendar e orquestrar fluxos de trabalho complexos de movimentação e transformação de dados.

## 🔧 Pré-requisitos

- Uma conta ativa no [Microsoft Azure](https://azure.microsoft.com/pt-br/).
- Uma assinatura válida do Azure (pode ser Azure for Students, Free Trial ou assinatura paga).
- Conhecimento básico sobre serviços em nuvem.

## 📖 Passo a Passo

Siga as etapas abaixo para criar o seu recurso Azure Data Factory:

### Passo 1 - Login no Portal Azure

1. Acesse [portal.azure.com](https://portal.azure.com/) e realize o login com suas credenciais.

### Passo 2 - Criação do Recurso

1. No menu à esquerda, clique em **"Criar um recurso"**.

![image](https://github.com/user-attachments/assets/c617b205-1256-4f48-8e85-e21f059bbde4)
---
3. Pesquise por **"Data Factory"** e selecione o recurso.

  ![image](https://github.com/user-attachments/assets/bd503e5f-495a-45b3-983e-e17425db4291)
---
4. Clique no botão **"Criar"**.

![image](https://github.com/user-attachments/assets/4b7350d7-19b0-4107-b473-0f4b8595b91c)
---
### Passo 3 - Configuração do Recurso

Preencha os seguintes campos:

![image](https://github.com/user-attachments/assets/4695a95d-a42c-4756-b305-5cbdb817bbf1)

- **Assinatura**: Selecione sua assinatura Azure.
- **Grupo de recursos**: Crie um novo ou selecione um existente.
- **Nome da instância**: Digite um nome exclusivo para o recurso. (Consulte: [Recomendações de abreviações para recursos do Azure](https://learn.microsoft.com/pt-br/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations))
- **Região**: Escolha a região mais próxima ou recomendada pela DIO.
- **Versão**: Escolha **V2**.
- Clique em **"Avançar"** até chegar em "Revisar + Criar" e, em seguida, clique em **"Criar"**.

---
### Passo 4 - Verificando a Criação

Após alguns minutos, verifique se o status da implantação é concluído:
- Vá até **"Grupo de recursos"** no menu principal.
- Localize seu grupo e veja se o Data Factory está listado com o status "Executando".

## ✅ Validação

Para validar que seu Azure Data Factory foi criado corretamente:

- Clique no recurso criado e abra o **Azure Data Factory Studio**.
- Certifique-se de que o ambiente esteja disponível e carregue corretamente.

## 🔖 Referências
- [Documentação Oficial Azure Data Factory](https://azure.microsoft.com/pt-br/services/data-factory/)
- [Digital Innovation One (DIO)](https://www.dio.me/)

---

## 📝 Autor

Desenvolvido por Pedro Sivlva como parte do Bootcamp Microsoft AI for Tech - Azure Databricks (DIO).

