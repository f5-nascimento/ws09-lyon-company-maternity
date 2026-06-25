# Módulo 02 - CRUD

## Introdução
A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação e especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

> Observação Técnica:
> - Os wireframes fornecidos nesta prova são apenas referências visuais de apoio ao desenvolvimento da solução, não devendo ser interpretados como representação final obrigatória das telas.
> - Toda a implementação visual deverá seguir prioritariamente a Guia de Estilos oficial da competição, respeitando padrões de identidade visual, usabilidade, responsividade e organização dos componentes gráficos.

## Descrição do Projeto e das Tarefas

### 1. Autenticação

Ao rodar o aplicativo, a primeira tela que será apresentada é a tela para entrada do usuário. O usuário deverá preencher o E-mail e a Senha, sobre o campo senha precisa ser mascarado. Caso seja um email não cadastrado na tabela Funcionário, apresenta uma mensagem de aviso (Email Não Cadastrado). Caso contrário, apresentar a tela de cadastro de Pacientes.

<img width="425" height="266" alt="Captura de tela 2026-06-25 112734" src="https://github.com/user-attachments/assets/eb99f2b9-1fe1-4f96-9505-c9849219b04d" />


### 2. Usuário do aplicativo

Ao tentar acessar o sistema o mesmo poderá seguir os caminhos abaixo:
- Digita senha inválida para entrar no sistema: O sistema apresenta uma mensagem (Alerta) e limpa o campo de senha.
- Digita senha válida para entrar no sistema: O sistema apresenta uma mensagem (Informação) de “Boas Vindas” e em seguida, tela principal do aplicativo que será o cadastro de Pacientes.

### 3. Modelo Físico do Banco de Dados
Agora que o modelo lógico está pronto, a próxima etapa é sua implementação no banco de dados. Escreva o código SQL para a criação do banco e das tabelas, considerando a seguinte estrutura:
- Cargos
- Funcionários
- Hospedes
- Guias
- Agendamentos

Crie um script SQL contendo as declarações de criação Do banco e das tabelas (CREATE TABLE), definição de chaves primárias e estrangeiras, além da aplicação de restrições de integridade. (Entregue o documento do Modelo Físico em
SQL no diretório/drive escolhido dos Avaliadores).
Crie e execute um arquivo SQL contendo os comandos INSERT necessários para popular e testar o Banco de Dados da Green Oasis Resorts. O arquivo deverá conter registros para todas as tabelas do projeto físico, respeitando as chaves primárias, chaves estrangeiras e os relacionamentos entre as tabelas.

Quantidade mínima exigida de inserts:  
- Tabela Cargos: Mínimo de 5 registros.
- Tabela Funcionarios: Mínimo de 8 registros.
- Tabela Guias: Mínimo de 3 registros.
- Tabela Hóspedes: Mínimo de 6 registros.
- Tabela Agendamentos: Mínimo de 6 registros.

Entrega: O script de criação das tabelas deve ser salvo como green_oasis.sql. 
O script deverá ser executado no SQL Server Management Studio (SSMS) sem apresentar erros, garantindo que todos os relacionamentos estejam funcionando corretamente. (Entregue o documento do Modelo Físico em SQL no diretório/drive escolhido dos Avaliadores).

### 4. Dicionário de Dados

A equipe de TI da Gaia Horizon precisa transformar o modelo lógico em um Dicionário de Dados, seguindo as boas práticas de normalização. Considerando o MER criado anteriormente, construa Dicionário de dados do banco utilizando o anexo *Dicionário de Dados*, especificando:
- Nome das tabelas
- Atributos e seus tipos de dados
- Chaves primárias e estrangeiras
- Relacionamentos entre tabelas

Explique como a normalização foi aplicada para evitar redundâncias e garantir a integridade dos dados. (Entregue em documento do Excel e salve no diretório/drive escolhido dos Avaliadores).

### 5. Diagrama de Casos de Uso
A arquitetura de segurança do sistema desktop deve delimitar com clareza o escopo de atuação de cada perfil de usuário (Atores), bloqueando acessos indevidos logo na camada de interface. Você deve criar um Diagrama de Casos de Uso baseado nas seguintes regras e restrições da descrição geral do projeto.

Entrega: Salve o arquivo do diagrama em formato PDF/Imagem com o nome useCase_GreenOasisResorts.pdf

### 6. Diagrama de Atividades
Para validar a lógica comportamental e o fluxo de permissões que seu software desktop executará, você deve elaborar um Diagrama de Atividades que represente o processo completo de "Agendamento de Atividade Ecológica". Como o Guia Turístico e o Administrador agora operam essa tela, o fluxo deve cobrir obrigatoriamente os cenários, ramificações e concorrências que envolvem este processo de ponta a ponta.

Entrega: Salve o diagrama em formato PDF/Imagem com o nome activity_GreenOasisResorts.pdf

### 7. Entregas
- Entrega o Modelo entidade Relacionamento em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega o Modelo Lógico (Banco de Dados) em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega o Modelo Físico/INSERTs em SQL no diretório/drive escolhido dos Avaliadores.
- Entrega o Dicionário de Dados em Excel no diretório/drive escolhido dos Avaliadores.
- Entrega do Diagrama de Casos de Uso em PDF/Imagem no diretório/drive escolhido dos Avaliadores.
- Entrega do Diagrama de Atividades em PDF/Imagem no diretório/drive escolhido dos Avaliadores.

