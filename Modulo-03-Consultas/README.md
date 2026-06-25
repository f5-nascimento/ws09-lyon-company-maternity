# Módulo 03 - Telas de Consulta e Filtros

## Introdução
A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação, especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

> Observação Técnica:
> - Os wireframes fornecidos nesta prova são apenas referências visuais de apoio ao desenvolvimento da solução, não devendo ser interpretados como representação final obrigatória das telas.
> - Toda a implementação visual deverá seguir prioritariamente a Guia de Estilos oficial da competição, respeitando padrões de identidade visual, usabilidade, responsividade e organização dos componentes gráficos.

## Descrição do Projeto e das Tarefas

### 1. Ações em Consultas Gerais de Tabela

Uma tela de consulta de dados é uma ferramenta essencial para qualquer sistema de gerenciamento do software e suas aplicações. Neste projeto referente a consulta de Médicos, Pacientes e Recém-nascidos seu resultado deverá aparecer no formato abaixo. As demais telas de Consulta devem seguir o mesmo padrão desta abaixo. 

Na tela de consultas abaixo crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”. Vamos entender melhor como funcionará a ação de invocar esta tela de consultas: Na tela pricincipal “Cadastro de Pacientes” ao clicar nos Menus/Guias: “| Médicos | | Pacientes | | Recém-Nascidos |” esta tela de consultas gerais será exibida de forma centralizada automaticamente com consultas de todos os atributos e dados da tabela invocada conforme o seu Menu/Guia. 

Funcionários do setor “Administrativo” poderão realizar todas as consultas, colaboradores do setor “Saúde” terão permissão de acessar apenas consultas de: “Pacientes e Recém-Nascidos”. Atenção ao fechar tela de consultas gerais a tela principal “Cadastro de Pacientes” deve ser exibida novamente.ntes.

<img width="387" height="318" alt="image" src="https://github.com/user-attachments/assets/cfda93a9-5e4a-4d43-91a2-dd7d3e01c40a" />


### 2. Ações em Pesquisas de Consultas

Na tela de consultas abaixo crie um título centralizado na janela com a descrição “Plataforma – Lyon Company Maternidades”. Vamos entender melhor como funcionará a ação de invocar esta tela pesquisas de consultas específicas: Na tela pricincipal “Cadastro de Pacientes” ao clicar no Sub-Menu : “| CONSULTAR |” esta tela de pesquisa de consulta será exibida de forma centralizada, com consultas de todos os atributos e dados da tabela invocada conforme o seu Sub-Menu escolhido “Médicos, Pacientes, Recém-nascidos”.

Funcionários do setor Administrativo poderão realizar todas as consultas, colaboradores do setor “Saúde” terão permissão de acessar apenas consultas de: “Pacientes e Recém-Nascidos”. Atenção ao fechar a janela de pesquisas de consultas a tela principal “Cadastro de Pacientes” deve ser exibida novamente.

<img width="433" height="335" alt="image" src="https://github.com/user-attachments/assets/990f5d55-a43c-488c-8cff-adab21cab3c9" />

Ao clicar no botão com nome “CONSULTAR” deverá buscar no banco segundo a chave primária da tabela indicada do cadastro e mostrar os dados daquela linha de registro solicitada pela consulta. Caso não encontre nenhum registro com aquela chave primária exibir a mensagem “Consulta Não Localizada!”. As demais telas de Consulta devem seguir o mesmo padrão deta abaixo. 

Para otimizar o processo de consulta vamos criar outro botão com nome “LIMPAR”, este terá a função de limpar todos os dados digitados em uma primeira consulta, implemente este botão com uma cor diferente do botão “Consultar”, lembre-se sempre de utilizar apenas nossas paletas de cores indicadas em anexo no “DataFiles/Guias de Estilos”. As demais telas de Consulta devem seguir o mesmo padrão deta abaixo.


### 3. Entregas
- Telas de Consulta de Médicos funcional, de acordo com o descritivo da prova.
- Telas de Consulta de Pacientes funcional, de acordo com o descritivo da prova.
- Telas de Consulta de Recém-Nascidos funcional, de acordo com o descritivo da prova.
- Açoes e funcionalidades das Telas de consultas. de acordo com o descritivo da prova.


