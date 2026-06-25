# #09 - Lyon Company Maternity

Este repositório contém simulados baseados nos padrões da seletiva da WorldSkills para a ocupação **#09 - Soluções de Software para Negócios**.

## 📌 Módulos

* [Módulo 1: Documentação](./Modulo-01-Documentacao/)
* [Módulo 2: CRUD](./Modulo-02-CRUD/) 
* [Módulo 3: Telas de Consulta e Filtros](./Modulo-03-Consultas/) 
* [Módulo 4: Dashboards](./Modulo-04-Dashboards/)
* [CIS](./CIS/)

## ⚙️ Configuração do Ambiente de Desenvolvimento

Antes de iniciar o desenvolvimento do projeto, instale os softwares necessários conforme as instruções abaixo.

## 🗄️ SQL Server Express

### Passo 1: Acessar a página de download
Acesse a página oficial de downloads do SQL Server:

🔗 https://www.microsoft.com/en-us/sql-server/sql-server-downloads

### Passo 2: Baixar o SQL Server Express
Clique em **Download now** no card do **SQL Server 2025 Express**, conforme ilustrado abaixo:

<img width="1457" height="545" alt="sqlserverexpress" src="https://github.com/user-attachments/assets/f8b867bb-35c3-4ea0-a902-4605bb870351" />

### Passo 3: Abrindo o arquivo de instalação do SQL Server Express
Clique em **Abrir arquivo** na guia de Download, conforme ilustrado abaixo:

<img width="1914" height="1027" alt="sqlserver-abriraquivo" src="https://github.com/user-attachments/assets/7c0d4c93-ec38-4c8c-9023-91f5e0818d08" />

### Passo 4: Selecionando o tipo de instalação do SQL Server Express
Clique em **Basic** na tela Seleção do tipo de Instação, conforme ilustrado abaixo:

<img width="998" height="779" alt="sqlserver-selecionando a instalação" src="https://github.com/user-attachments/assets/92aec108-72c2-43d9-8e55-235b7526ce1b" />

### Passo 5: Aceitando os Termos de Licensiamento
Clique em **Accept** na tela Microsoft SQL Server License Terms, conforme ilustrado abaixo:

<img width="862" height="710" alt="sqlserver-license" src="https://github.com/user-attachments/assets/a91cbf4b-ead7-4e9e-97c1-25bcb66a1b4e" />

### Passo 6: Especificando o local de instalação
Clique em **Install** na tela Specify SQL Server install location, conforme ilustrado abaixo:

<img width="879" height="719" alt="sqlserver-localinstalacao" src="https://github.com/user-attachments/assets/20a1692e-ceab-4fec-a21b-9642b6ef9893" />

### Passo 7: Instalação Concluída e String de Conexão
Com a conclusão da instalação exibirá **CONNECTION STRING** que será importante para a conexão com a base de dados. Clique em **Close**, conforme ilustrado abaixo:

<img width="942" height="741" alt="sqlserver-close" src="https://github.com/user-attachments/assets/19ab67e5-10cb-4359-afcd-00c9739eda75" />

## 💾 SQL Server Management Studio (SSMS)

### Passo 1: Acessar a página de download
Acesse a página oficial do SSMS:

🔗 https://learn.microsoft.com/pt-br/ssms/install/install

### Passo 2: Baixar o instalador
Clique em **Baixar o instalador do SQL Server Management Studio**, no botão azul indicado abaixo:

<img width="814" height="454" alt="ssms" src="https://github.com/user-attachments/assets/10f49150-c7c0-49d5-9c69-d2b0908973bb" />

### Passo 3: Abrindo o arquivo de instalação do SSMS
Clique em **Abrir arquivo** na guia de Download, conforme ilustrado abaixo:

<img width="1893" height="927" alt="abrir arquivo" src="https://github.com/user-attachments/assets/3b0bb582-fad0-46ea-95eb-d29e995dd079" />

### Passo 4: Aceitando o termo de instalação do Visual Studio Installer
Clique em **Continuar** na tela do Visual Studio Installer, conforme ilustrado abaixo:

<img width="1869" height="923" alt="instalação" src="https://github.com/user-attachments/assets/560b6566-66c6-4417-a727-0342540e45c3" />

### Passo 5: Realizando a Instalação do SSMS
Para a instalação não é necessário escolher nenhuma das opções, basta clicar em **Instalar** na tela SQL Server Management Studio, conforme ilustrado abaixo:

<img width="1901" height="981" alt="instalar" src="https://github.com/user-attachments/assets/13802a6a-e039-4a18-80af-d415136d14c7" />

### Passo 6: Concluindo a instalação
Clique em **Ok** na tela Instalação Concluída, conforme ilustrado abaixo:

<img width="1916" height="1025" alt="concluido" src="https://github.com/user-attachments/assets/a340bda4-171b-489d-a97c-79c9f8afe48e" />

### Passo 7: Iniciando o SSMS
Com a conclusão da instalação clique em **Iniciar**, conforme ilustrado abaixo:

<img width="1913" height="973" alt="iniciar" src="https://github.com/user-attachments/assets/bc07f516-a854-4431-b212-d6a3e29a46c0" />

### Passo 8: Entrando no SSMS
Nesta tela você pode escolher o seu método de entrada, seja com uma conta Microsoft ou GitHub. Se preferir clique em **Ignore e adicione contas mais tarde**, conforme ilustrado abaixo:

<img width="1006" height="523" alt="entrando" src="https://github.com/user-attachments/assets/0c751d80-d571-48db-8725-b37980813591" />

### Passo 9: Conectando o SSMS com o SQL Server Express
Nesta tela você deve indicar o **Nome do Servidor** do SQL Server Express. Geralmente, você utilizará:
- Em Nome do Servidor digite: **localhost\SQLEXPRESS**
- Na criptografia marque a opção **Certificado de Servidor de Confiança**
- Clique em **Conectar**, conforme ilustrado abaixo:

<img width="1881" height="997" alt="CONECTANDO" src="https://github.com/user-attachments/assets/18a14a4c-8034-4b35-9c6c-307fc3885c07" />

### Passo 10: Tela principal do SSMS
Nesta tela você terá acesso aos recursos do SSMS. conforme ilustrado abaixo:

<img width="1918" height="940" alt="done" src="https://github.com/user-attachments/assets/a00f11b6-ac7d-4821-8d81-ea3442a1a373" />


## 💻 Visual Studio

### Passo 1: Acessar a página de download

Acesse a página oficial do Visual Studio:

🔗 https://visualstudio.microsoft.com/pt-br/

### Passo 2: Baixar o Visual Studio Community 2026

Clique em **Baixar gratuitamente** no botão roxo, conforme mostrado na imagem:

<img width="1492" height="450" alt="visualstudio" src="https://github.com/user-attachments/assets/072dad14-ab96-4f6f-a5f5-5c0d7a84336d" />

### Passo 3: Abrindo o arquivo de instalação do Visual Studio Community 2026
Clique em **Abrir arquivo** na guia de Download, conforme ilustrado abaixo:

<img width="1917" height="910" alt="arquivo" src="https://github.com/user-attachments/assets/d7b24fa3-84a3-41f6-a2b9-3bbeb2a1c6db" />

### Passo 4: Aceitando o termo de instalação do Visual Studio Installer
Clique em **Continuar** na tela do Visual Studio Installer, conforme ilustrado abaixo:

<img width="1397" height="878" alt="continuar" src="https://github.com/user-attachments/assets/06245756-5823-4ed1-bc00-e44b06508caf" />

### Passo 5: Realizando a Instalação do Visual Studio Community 2026
Para a instalação do Visual Studio Community 2026 tendo em vista os projetos que estão propostos nesse repositório algumas cargas de trabalho deverão ser selecionadas:
- Desenvolvimento para desktop com .NET (Essa carga de trabalho será utilizada nos módulo de desenvolvimento desktop)
- Desenvolvimento de .NET Multi-Platform App UI (Essa carga de trabalho será utilziada para os módulos Mobile)
- ASP.NET e desenvolvimento Web (Essa carga de tarablho será utilizada para construir API)
Após selecionar as cargas de trabalho, clique em **Instalar**, conforme ilustrado abaixo:

<img width="1910" height="907" alt="cargas de trabalho" src="https://github.com/user-attachments/assets/b8cdbdc6-7085-4207-b0a3-5efe8519af06" />

### Passo 6: Iniciando o Visual Studio Community 2026
Com a conclusão da instalação clique em **Iniciar**, conforme ilustrado abaixo:

<img width="1893" height="926" alt="done" src="https://github.com/user-attachments/assets/c08865f2-ab78-4db2-a859-d3904ecc3386" />

### Passo 7: Entrando no Visual Studio Community 2026
Nesta tela você pode escolher o seu método de entrada, seja com uma conta Microsoft ou GitHub. Se preferir clique em **Ignore e adicione contas mais tarde**, conforme ilustrado abaixo:

<img width="1915" height="911" alt="done done" src="https://github.com/user-attachments/assets/58b78abd-78cc-4783-905a-00f91cbe6649" />


### Passo 8: Iniciando o Visual Studio
Nesta tela você pode escolher o seu tema de cores preferido e depois clique em **Iniciar o Visual Studio**, conforme ilustrado abaixo:

<img width="1906" height="918" alt="tema" src="https://github.com/user-attachments/assets/3664d0bf-52f5-439a-acf8-a552b62a8fe2" />


Pronto! Com o ambiente configurado, você já pode iniciar o desenvolvimento das soluções propostas nos módulos deste repositório.
