# Módulo 01 - Documentação

## Introdução
A Lyon Company iniciará um novo projeto, um software para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação, especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

## Descrição do Projeto e das Tarefas

### 1. Modelo Entidade-Relacionamento (MER)

A estrutura do banco de dados da Lyon Company Maternidades deve garantir a integridade dos dados e os relacionamentos entre as entidades. Considerando os seguintes requisitos:
- Uma Médico poderá ter várias pacientes, mas uma paciente pertencerá apenas um médico.
- Um cargo pode ter vários funcionários, e cada funcionário terá apenas um cargo na empresa.
- Um recém-nascido deve pertencer apenas a uma paciente, e uma paciente poderá ter nenhum ou vários recém-nascidos.

Com base nessas relações, elabore um Modelo Entidade-Relacionamento (MER) utilizando a notação adequada, indicando cardinalidades e chaves identificadoras, contrua também outras entidades necessárias segundo a introdução do módulo caso for preciso. (Entregue a imagem do Modelo Entidade-Relacionamento em PDF/WORD no diretório/drive escolhido dos Avaliadores).

### 2. Modelo Lógico do Banco de Dados

A equipe de TI da Lyon Company Maternidades precisa transformar o MER em um modelo lógico, seguindo as boas práticas de normalização. Considerando o MER criado anteriormente, construa o Modelo Lógico do banco de dados, especificando:
- Nome padronizado das tabelas.
- Atributos com seus respectivos tipos de dados
- Chaves Primárias e Estrangeiras.
- Relacionamentos entre tabelas.

Explique como a normalização foi aplicada para evitar redundâncias e garantir a integridade dos dados. (Entregue a imagem do Modelo Lógico em PDF/WORD no diretório/drive escolhido dos Avaliadores).

### 3. Modelo Físico do Banco de Dados
Agora que o modelo lógico está pronto, a próxima etapa é sua implementação no banco de dados. Escreva o código SQL para a criação do banco e das tabelas, considerando a seguinte estrutura:
- MÉDICOS;
- PACIENTES;
- RECÉM-NASCIDOS;
- FUNCIONÁRIOS;
- CARGOS;

Crie um script SQL contendo as declarações de criação Do banco e das tabelas (CREATE TABLE), definição de chaves primárias e estrangeiras, além da aplicação de restrições de integridade. (Entregue o documento do Modelo Físico em SQL no diretório/drive escolhido dos Avaliadores).

Crie e execute um arquivo SQL contendo os comandos INSERT necessários para popular e testar o Banco de Dados da Maternidade Boa Ventura.

O arquivo deverá conter registros para todas as tabelas do projeto físico, respeitando as chaves primárias, chaves estrangeiras e os relacionamentos entre as tabelas.

Quantidade mínima de registros por tabela:
- Tabela cargos: Inserir no mínimo 5 registros de cargos.
- Tabela funcionarios: Inserir no mínimo 8 registros de funcionários.
- Tabela medicos: Inserir no mínimo 3 registros de médicos.
- Tabela pacientes: Inserir no mínimo 6 registros de pacientes.
- Tabela nascimentos: Inserir no mínimo 6 registros de nascimentos.

Entrega: O script de criação das tabelas deve ser salvo como lyon_company-maternity.sql. 
O script deverá ser executado no SQL Server Management Studio (SSMS) sem apresentar erros, garantindo que todos os relacionamentos estejam funcionando corretamente. (Entregue o documento do Modelo Físico em SQL no diretório/drive escolhido dos Avaliadores).

### 4. Dicionário de Dados

A equipe de TI da Lyon Company Maternidades precisa transformar o modelo lógico em um Dicionário de Dados, seguindo as boas práticas de normalização. Considerando o MER criado anteriormente, construa Dicionário de dados do banco utilizando o anexo “Modelo de Dicionário de Dados 2026”, especificando:
- Nome das tabelas
- Atributos e seus tipos de dados
- Chaves primárias e estrangeiras
- Relacionamentos entre tabelas

Explique como a normalização foi aplicada para evitar redundâncias e garantir a integridade dos dados. (Entregue em documento do Excel e salve no diretório/drive escolhido dos Avaliadores).

### 5. Diagrama de Casos de Uso
A arquitetura de segurança do sistema desktop deve delimitar com clareza o escopo de atuação de cada perfil de usuário (Atores), bloqueando acessos indevidos logo na camada de interface. Você deve criar um Diagrama de Casos de Uso baseado nas seguintes regras e restrições da descrição geral do projeto.

Entrega: Salve o arquivo do diagrama em formato PDF/Imagem com o nome useCase_LyonCompanyMaternity.pdf

### 6. Diagrama de Atividades
Para validar a lógica comportamental e o fluxo de permissões que seu software desktop executará, você deve elaborar um Diagrama de Atividades que represente o processo completo de Médicos. Como o Pacientes e o Recém-Nascido agora operam essa tela, o fluxo deve cobrir obrigatoriamente os cenários, ramificações e concorrências que envolvem este processo de ponta a ponta.

Entrega: Salve o diagrama em formato PDF/Imagem com o nome activity_LyonCompanyMaternity.pdf

### 7. Entregas
- Entrega o Modelo entidade Relacionamento em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega o Modelo Lógico (Banco de Dados) em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega o Modelo Físico/INSERTs em SQL no diretório/drive escolhido dos Avaliadores.
- Entrega o Dicionário de Dados em Excel no diretório/drive escolhido dos Avaliadores.
- Entrega do Diagrama de Casos de Uso em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega do Diagrama de Atividades em PDF/Imagem no diretório/drive escolhido dos Avaliadores.

