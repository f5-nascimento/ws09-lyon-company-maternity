# Módulo 05 - Mobile

## Introdução
A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação e especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação, especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação, especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

> Observação Técnica:
> - Os wireframes fornecidos nesta prova são apenas referências visuais de apoio ao desenvolvimento da solução, não devendo ser interpretados como representação final obrigatória das telas.
> - Toda a implementação visual deverá seguir prioritariamente a Guia de Estilos oficial da competição, respeitando padrões de identidade visual, usabilidade, responsividade e organização dos componentes gráficos.

## Descrição do Projeto e das Tarefas

### 1. Autenticação

Ao rodar o aplicativo, a primeira tela que será apresentada é a tela para entrada do usuário. O usuário deverá preencher o E-mail e a Senha, sobre o campo senha precisa ser mascarado. Caso seja um email não cadastrado na tabela Funcionário, apresenta uma mensagem de aviso (Email Não Cadastrado). Caso contrário, apresentar a tela de cadastro de Pacientes.

<img width="1536" height="2752" alt="lyon-login-mobile" src="https://github.com/user-attachments/assets/b7c25638-e24d-4012-9021-a09a012c9e0e" />



### 2. Usuário do aplicativo

Ao tentar acessar o sistema o mesmo poderá seguir os caminhos abaixo:
- Digita senha inválida para entrar no sistema: O sistema apresenta uma mensagem (Alerta) e limpa o campo de senha.
- Digita senha válida para entrar no sistema: O sistema apresenta uma mensagem (Informação) de “Boas Vindas” e em seguida, tela principal do aplicativo que será o cadastro de Pacientes.

### 3. Telas de Cadastro
O cadastro de Médicos será apresentado com os itens conforme tela abaixo. Outras telas de cadastros como: Pacientes e Recém-nascidos devem seguir o mesmo padrão de tela deste cadastro com os dados conforme pedido na introdução. Crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”, implemente Menus/Guias: | Médicos | | Pacientes | | Recém-Nascidos | | CADASTRAR | | CONSULTAR | |Login|. Neste módulo precisamos deixar todos os formulários de cadastros funcionais, e será necessário cadastrar e testar todas as telas, Ao clicar no Menu: “CADASTRAR” abrirá sub-menus com as seguintes opções(uma abaixo da outra): Médicos, Pacientes, Recém-Nascidos. Uma observação que tanto na Tela de Cadastro de Médicos quanto na Tela de Cadastro de Pacientes será necessario o cadastro de foto de perfil. Funcionários do setor Administrativo poderão realizar todos os cadastros, colaboradores do setor “Saúde” terão permissão de cadastrar apenas: “Pacientes e Recém-Nascidos”.

<img width="440" height="443" alt="image" src="https://github.com/user-attachments/assets/f4d9b507-2a83-4837-a327-b665c5e0ad73" />


### 4. Botoões e Ações

Ao clicar em “CADASTRAR” deverá abrir uma mensagem de informação dizendo “Processo Cadastrado Com Sucesso!”, assim que o cadastro for realizado limpe os campos, caso o cadastro não for realizado exibir uma mensagem “Erro ao Tentar Cadastrar!!!”. Ao clicar em “EDITAR” deverá exibir uma mensagem “Alteração Salva com Sucesso!”, e finalmente clicando em “DELETAR” exibir uma mensagem “Tem Certeza que deseja Excluir ‘Campo_de_Exemplo’ ?” caso resposta da mensagem seja “SIM/YES” deletar a linha do banco de dados conforme a chave primária, caso seja “NÃO/NO” não excluir e voltar a página de cadastro. Faça o mesmo em outros cadastros.

### 5. Ações em Consultas Gerais de Tabela

Uma tela de consulta de dados é uma ferramenta essencial para qualquer sistema de gerenciamento do software e suas aplicações. Neste projeto referente a consulta de Médicos, Pacientes e Recém-nascidos seu resultado deverá aparecer no formato abaixo. As demais telas de Consulta devem seguir o mesmo padrão desta abaixo. 

Na tela de consultas abaixo crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”. Vamos entender melhor como funcionará a ação de invocar esta tela de consultas: Na tela pricincipal “Cadastro de Pacientes” ao clicar nos Menus/Guias: “| Médicos | | Pacientes | | Recém-Nascidos |” esta tela de consultas gerais será exibida de forma centralizada automaticamente com consultas de todos os atributos e dados da tabela invocada conforme o seu Menu/Guia. 

Funcionários do setor “Administrativo” poderão realizar todas as consultas, colaboradores do setor “Saúde” terão permissão de acessar apenas consultas de: “Pacientes e Recém-Nascidos”. Atenção ao fechar tela de consultas gerais a tela principal “Cadastro de Pacientes” deve ser exibida novamente.ntes.

<img width="387" height="318" alt="image" src="https://github.com/user-attachments/assets/cfda93a9-5e4a-4d43-91a2-dd7d3e01c40a" />


### 6. Ações em Pesquisas de Consultas

Na tela de consultas abaixo crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”. Vamos entender melhor como funcionará a ação de invocar esta tela pesquisas de consultas específicas: Na tela pricincipal “Cadastro de Pacientes” ao clicar no Sub-Menu : “| CONSULTAR |” esta tela de pesquisa de consulta será exibida de forma centralizada, com consultas de todos os atributos e dados da tabela invocada conforme o seu Sub-Menu escolhido “Médicos, Pacientes, Recém-nascidos”.

Funcionários do setor Administrativo poderão realizar todas as consultas, colaboradores do setor “Saúde” terão permissão de acessar apenas consultas de: “Pacientes e Recém-Nascidos”. Atenção ao fechar a janela de pesquisas de consultas a tela principal “Cadastro de Pacientes” deve ser exibida novamente.

<img width="433" height="335" alt="image" src="https://github.com/user-attachments/assets/990f5d55-a43c-488c-8cff-adab21cab3c9" />

Ao clicar no botão com nome “CONSULTAR” deverá buscar no banco segundo a chave primária da tabela indicada do cadastro e mostrar os dados daquela linha de registro solicitada pela consulta. Caso não encontre nenhum registro com aquela chave primária exibir a mensagem “Consulta Não Localizada!”. As demais telas de Consulta devem seguir o mesmo padrão deta abaixo. 

Para otimizar o processo de consulta vamos criar outro botão com nome “LIMPAR”, este terá a função de limpar todos os dados digitados em uma primeira consulta, implemente este botão com uma cor diferente do botão “Consultar”, lembre-se sempre de utilizar apenas nossas paletas de cores indicadas em anexo no “DataFiles/Guias de Estilos”. As demais telas de Consulta devem seguir o mesmo padrão deta abaixo.

### 7. Detalhamento do Projeto Desktop

A Lyon Company iniciará o desenvolvimento de uma plataforma desktop independente voltada ao gerenciamento e monitoramento de informações hospitalares da rede de maternidades da empresa. O sistema terá como principal objetivo centralizar dados administrativos, indicadores médicos e registros relacionados aos recém-nascidos, proporcionando maior controle, organização e apoio estratégico para os gestores da instituição.

A aplicação contará com dashboards interativos e gráficos dinâmicos capazes de apresentar informações em tempo real sobre setores administrativos e da saúde, além de indicadores estatísticos relacionados aos tipos de parto realizados, como partos normais e cesáreas. Essas informações permitirão que os administradores acompanhem métricas importantes da maternidade de forma simples, visual e eficiente.

Além dos dashboards, o sistema disponibilizará consultas completas dos registros de recém-nascidos, permitindo visualizar dados relevantes como médico responsável, nome da mãe, peso do recém-nascido, tamanho, data e hora de nascimento, bem como observações médicas importantes para acompanhamento hospitalar.

A plataforma será desenvolvida com foco em usabilidade, desempenho e segurança da informação, garantindo que os dados sensíveis armazenados possam ser acessados de maneira organizada e confiável. O sistema também deverá oferecer uma estrutura moderna e intuitiva, auxiliando os profissionais da maternidade na análise de dados, no acompanhamento clínico e na tomada de decisões administrativas.

### 8. Autenticação

Você deve implementar uma tela de login independente da outra tela de login que será carregada sempre que o usuário abrir a aplicação: ControleMaternidades. Essa tela deve permitir que o usuário insira credenciais para acessar a aplicação:

1. Essa tela de login deve possuir um campo para inserção de Email e outro para a senha do usuário.
- Somente usuários do tipo “Administrativo” poderão acessar a aplicação.
- Você deve implementar validações para login e senha, além de mensagens adequadas informando para o usuário caso ele tenha digitado informações incorretas ou não possua acesso à aplicação por não ser “Administrativo”.
2. O usuário só poderá entrar na aplicação caso insira login e senha válidos (presentes nos dados originais fornecidos).
3. Quando o usuário inserir credenciais válidas, então ele deverá ser direcionado para a tela “Controle Maternidades”, descrita mais abaixo.

<img width="391" height="268" alt="image" src="https://github.com/user-attachments/assets/3809a410-fdf5-4cac-b695-80e810bd5b45" />

### 9. Tela de Controle
Você deve implementar uma tela que permita ao usuário visualizar dados de setores e de recem nascidos, bem como informações em um pequeno dashboard, conforme layout a seguir (todas as informações devem consumir dados do banco de dados atual):

<img width="592" height="400" alt="image" src="https://github.com/user-attachments/assets/69b8aad0-31ec-45a9-9996-ff633397d53f" />

### 10. Entregas
- Telas de Login (Funcional com comunicação com o banco de dados) entregue no diretório indicado pelos avaliadores, salvar o projeto e criar uma pasta /bin com executável do aplicativo desktop.
- Telas de cadastro de Médicos (Cadastrando funcionalmente no banco de dados).
- Telas de cadastro de Paceinte (Cadastrando funcionalmente no banco de dados).
- Telas de cadastro de Recém-Nascidos (Cadastrando funcionalmente no banco de dados).
- - Telas de Consulta de Médicos funcional, de acordo com o descritivo da prova.
- Telas de Consulta de Pacientes funcional, de acordo com o descritivo da prova.
- Telas de Consulta de Recém-Nascidos funcional, de acordo com o descritivo da prova.
- Açoes e funcionalidades das Telas de consultas. de acordo com o descritivo da prova.
- Tela de Login funcional, independente da tela principal, com validação de e-mail, senha e permissão apenas para usuários do tipo Administrativo, integrada ao banco de dados.
- Tela Principal “Controle Maternidades”, carregada somente após autenticação válida do usuário administrativo.
- Dashboard de Funcionários por Setor, exibindo gráfico de barras com a quantidade de funcionários dos setores Administrativo, Saúde e outros setores cadastrados no banco.
- Dashboard de Partos dos Recém-Nascidos, exibindo gráfico de pizza com a porcentagem de partos Normal e Cesárea, consumindo dados reais do banco.
- Tabela de Consulta de Recém-Nascidos, exibindo médico responsável, nome da mãe, peso, tamanho, data de nascimento, hora de nascimento e observações relevantes.
- Integração completa com o Banco de Dados, garantindo que todos os gráficos, tabelas e consultas sejam alimentados pelos dados cadastrados.
- Validações e mensagens ao usuário, informando erros de login, senha incorreta, usuário inexistente ou ausência de permissão administrativa.
- Projeto Desktop completo, salvo no diretório indicado pelos avaliadores, contendo todos os arquivos-fonte organizados.
- Pasta /bin com o executável da aplicação desktop, permitindo a execução do sistema sem necessidade de abrir o ambiente de desenvolvimento.




