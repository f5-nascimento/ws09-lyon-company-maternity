# Módulo 04 - Dashboard

## Introdução
A Lyon Company iniciará um novo projeto, uma plataforma desktop para a Maternidade "Boa Ventura" que deseja modernizar seu sistema interno, otimizando o controle de cadastros de pacientes, médicos, recém-nascidos, cargos e funcionários. Eles estão buscando uma solução eficiente para armazenar e gerenciar os dados relacionados ao seu hospital. O seu objetivo é criar um banco de dados bem estruturado que possibilite à maternidade gerenciar eficientemente seus dados de acordo com atributos especificados aqui, como por exemplo, nossas pacientes precisam ser cadastradas com: cpf, nome, sobrenome, idade, altura, peso, tipo de parto (Normal/Cesárea), foto de perfil, e médico responsável. Sobre os médicos, vamos registrar: CRM, nome completo, formação, especialidade, foto de perfil, lembrando que todo médico é um funcionário contratado. Cada nascimento precisa ser registrado para o acompanhamento e controle hospitalar, guardando: número de registro, cpf da mãe, peso do recém-nascido, tamanho, data de nascimento, hora de nascimento e observações relevantes. Fora nosso relacionamento com pacientes, médicos e recém-nascidos, temos a necessidade de cadastrar nossos funcionários e cargos, a fim de gerenciar pagamentos e funções dentro da maternidade. Sobre cargos vamos registrar: código do cargo, descrição e salário. Sobre nossos funcionários vamos registrar: matrícula do funcionário, nome, sobrenome, código do cargo, setor (Administrativo/Saúde), CPF, RG, telefone, e-mail, senha, endereço e data de contratação. Ao final do projeto, você deve ser capaz de apresentar um modelo que atenda às necessidades da maternidade e que seja fácil de entender e implementar.

> Observação Técnica:
> - Os wireframes fornecidos nesta prova são apenas referências visuais de apoio ao desenvolvimento da solução, não devendo ser interpretados como representação final obrigatória das telas.
> - Toda a implementação visual deverá seguir prioritariamente a Guia de Estilos oficial da competição, respeitando padrões de identidade visual, usabilidade, responsividade e organização dos componentes gráficos.

## Descrição do Projeto e das Tarefas

### 1. Detalhamento do Projeto Desktop

A Lyon Company iniciará o desenvolvimento de uma plataforma desktop independente voltada ao gerenciamento e monitoramento de informações hospitalares da rede de maternidades da empresa. O sistema terá como principal objetivo centralizar dados administrativos, indicadores médicos e registros relacionados aos recém-nascidos, proporcionando maior controle, organização e apoio estratégico para os gestores da instituição.

A aplicação contará com dashboards interativos e gráficos dinâmicos capazes de apresentar informações em tempo real sobre setores administrativos e da saúde, além de indicadores estatísticos relacionados aos tipos de parto realizados, como partos normais e cesáreas. Essas informações permitirão que os administradores acompanhem métricas importantes da maternidade de forma simples, visual e eficiente.

Além dos dashboards, o sistema disponibilizará consultas completas dos registros de recém-nascidos, permitindo visualizar dados relevantes como médico responsável, nome da mãe, peso do recém-nascido, tamanho, data e hora de nascimento, bem como observações médicas importantes para acompanhamento hospitalar.

A plataforma será desenvolvida com foco em usabilidade, desempenho e segurança da informação, garantindo que os dados sensíveis armazenados possam ser acessados de maneira organizada e confiável. O sistema também deverá oferecer uma estrutura moderna e intuitiva, auxiliando os profissionais da maternidade na análise de dados, no acompanhamento clínico e na tomada de decisões administrativas.

### 2. Autenticação

Você deve implementar uma tela de login independente da outra tela de login que será carregada sempre que o usuário abrir a aplicação: ControleMaternidades. Essa tela deve permitir que o usuário insira credenciais para acessar a aplicação:

1. Essa tela de login deve possuir um campo para inserção de Email e outro para a senha do usuário.
- Somente usuários do tipo “Administrativo” poderão acessar a aplicação.
- Você deve implementar validações para login e senha, além de mensagens adequadas informando para o usuário caso ele tenha digitado informações incorretas ou não possua acesso à aplicação por não ser “Administrativo”.
2. O usuário só poderá entrar na aplicação caso insira login e senha válidos (presentes nos dados originais fornecidos).
3. Quando o usuário inserir credenciais válidas, então ele deverá ser direcionado para a tela “Controle Maternidades”, descrita mais abaixo.

<img width="391" height="268" alt="image" src="https://github.com/user-attachments/assets/3809a410-fdf5-4cac-b695-80e810bd5b45" />

### 3. Tela de Controle
Você deve implementar uma tela que permita ao usuário visualizar dados de setores e de recem nascidos, bem como informações em um pequeno dashboard, conforme layout a seguir (todas as informações devem consumir dados do banco de dados atual):

<img width="592" height="400" alt="image" src="https://github.com/user-attachments/assets/69b8aad0-31ec-45a9-9996-ff633397d53f" />



### 4. Entregas
- Tela de Login funcional, independente da tela principal, com validação de e-mail, senha e permissão apenas para usuários do tipo Administrativo, integrada ao banco de dados.
- Tela Principal “Controle Maternidades”, carregada somente após autenticação válida do usuário administrativo.
- Dashboard de Funcionários por Setor, exibindo gráfico de barras com a quantidade de funcionários dos setores Administrativo, Saúde e outros setores cadastrados no banco.
- Dashboard de Partos dos Recém-Nascidos, exibindo gráfico de pizza com a porcentagem de partos Normal e Cesárea, consumindo dados reais do banco.
- Tabela de Consulta de Recém-Nascidos, exibindo médico responsável, nome da mãe, peso, tamanho, data de nascimento, hora de nascimento e observações relevantes.
- Integração completa com o Banco de Dados, garantindo que todos os gráficos, tabelas e consultas sejam alimentados pelos dados cadastrados.
- Validações e mensagens ao usuário, informando erros de login, senha incorreta, usuário inexistente ou ausência de permissão administrativa.
- Projeto Desktop completo, salvo no diretório indicado pelos avaliadores, contendo todos os arquivos-fonte organizados.
- Pasta /bin com o executável da aplicação desktop, permitindo a execução do sistema sem necessidade de abrir o ambiente de desenvolvimento.


