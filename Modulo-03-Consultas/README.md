# Módulo 03 - Consultas

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

### 3. Telas de Cadastro
O cadastro de Médicos será apresentado com os itens conforme tela abaixo. Outras telas de cadastros como: Pacientes e Recém-nascidos devem seguir o mesmo padrão de tela deste cadastro com os dados conforme pedido na introdução. Crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”, implemente Menus/Guias: | Médicos | | Pacientes | | Recém-Nascidos | | CADASTRAR | | CONSULTAR | |Login|. Neste módulo precisamos deixar todos os formulários de cadastros funcionais, e será necessário cadastrar e testar todas as telas, Ao clicar no Menu: “CADASTRAR” abrirá sub-menus com as seguintes opções(uma abaixo da outra): Médicos, Pacientes, Recém-Nascidos. Uma observação que tanto na Tela de Cadastro de Médicos quanto na Tela de Cadastro de Pacientes será necessario o cadastro de foto de perfil. Funcionários do setor Administrativo poderão realizar todos os cadastros, colaboradores do setor “Saúde” terão permissão de cadastrar apenas: “Pacientes e Recém-Nascidos”.

<img width="440" height="443" alt="image" src="https://github.com/user-attachments/assets/f4d9b507-2a83-4837-a327-b665c5e0ad73" />


### 4. Botoões e Ações

Ao clicar em “CADASTRAR” deverá abrir uma mensagem de informação dizendo “Processo Cadastrado Com Sucesso!”, assim que o cadastro for realizado limpe os campos, caso o cadastro não for realizado exibir uma mensagem “Erro ao Tentar Cadastrar!!!”. Ao clicar em “EDITAR” deverá exibir uma mensagem “Alteração Salva com Sucesso!”, e finalmente clicando em “DELETAR” exibir uma mensagem “Tem Certeza que deseja Excluir ‘Campo_de_Exemplo’ ?” caso resposta da mensagem seja “SIM/YES” deletar a linha do banco de dados conforme a chave primária, caso seja “NÃO/NO” não excluir e voltar a página de cadastro. Faça o mesmo em outros cadastros.

### 5. Entregas
- Telas de Login (Funcional com comunicação com o banco de dados) entregue no diretório indicado pelos avaliadores, salvar o projeto e criar uma pasta /bin com executável do aplicativo desktop.
- Telas de cadastro de Médicos (Cadastrando funcionalmente no banco de dados).
- Telas de cadastro de Paceinte (Cadastrando funcionalmente no banco de dados).
- Telas de cadastro de Recém-Nascidos (Cadastrando funcionalmente no banco de dados).


