# Desafio de Projeto 2
Criar uma ferramenta no Excel que ajude a organizar e reunir informações essenciais para a declaração de imposto de renda

## 📋 Descrição
Projeto visando aplicar conhecimentos práticos para a criação de uma planilha para organizar e reunir informações para a declaração do imposto de renda.

## 🧱 Estrutura
As informações foram organizadas em quatro abas ou planilhas que são: 1. Contribuinte, 2. Rendimentos, 3. Despesas e 4. Bens e Direitos.

Também foram utilizadas tabelas auxiliares com as faixas de retenção do INSS e do IRRF, mas apenas estimar os valores retidos para o exemplo ficar mais real. 

Alem disso, foram utilizadas tabelas auxiliares com os códigos de despesas e de bens e direitos utilizados nas declarações, mas neste caso possuem funcionalidade, pois serviram como Lista suspensa na validação de dados.

### 🏷 Identificação do Contribuinte
Planilha com informações do contribuinte, como nome, CPF, etc

### 💰 Rendimentos Tributáveis
Planilha com informações da fonte pagadora, rendimentos recebidos e valores retidos.

### 💸 Despesas e Pagamentos Efetuados
Planilha com informações sobre os gastos do contribuinte. 

Foi utilizada a ferramenta de validação de dados para a seleção do código através de uma lista, em seguida foi utilizada a função PROCV para trazer a descrição de acordo com o código.

Observação: Valor Reembolsado é o valor recebido de volta através da fonte pagadora como forma de auxílio para a financiar a despesa, tal valor se refere a uma parcela não dedutível do imposto de renda e assim reduz o valor que pode ser deduzido com a respectiva despesa.

### 🏰 Bens e Direitos
Planilha com informações sobre os bens e direitos do contribuinte.

Foi utilizada a ferramenta de validação de dados para a seleção do grupo de bens através de uma lista, assim como também foi utilizada para a seleção da descrição, só não foi possível limitar a escolha dentro do respectivo grupo, pelo menos não com o conhecimento atual e com o tempo escasso para terminar o desafio.

## ⚙ Outras informações e configurações utilizadas
Foram criados menus interativos na lateral esquerda das planilhas, sendo inseridos links que fazem com que os botões naveguem entre as planilhas ou abas. Também foram protegidas as planilhas, de modo a limitar o usuário a interagir apenas com as células necessárias. 

Futuramente a pasta de trabalho pode ser melhorada, sendo disponibilizada assim por conta do prazo para encerramento do curso e da conciliação do tempo com outras atividades.
