## Projeto de Sistema Bancário v1.0


Este projeto é uma simulação simples de um sistema bancário com operações básicas, desenvolvido para praticar a lógica de programação e a manipulação de dados em memória.


📜 Descrição


O sistema oferece uma interface de console onde o usuário pode interagir com uma conta bancária fictícia. As funcionalidades implementadas permitem ao usuário realizar depósitos, saques, consultar o extrato de transações e encerrar a sessão de forma segura.


✨ Funcionalidades


O sistema possui 4 ações principais que o usuário pode escolher:



##### [ 1 ] - Depositar
##### [ 2 ] - Sacar
##### [ 3 ] - Extrato
##### [ 0 ] - Sair

💵 Depósito


Ao escolher a opção Depositar, o sistema solicita ao usuário que insira o valor a ser depositado.
O valor deve ser positivo.
Após a confirmação, o valor é creditado na conta e uma mensagem de sucesso é exibida, informando o montante depositado.

##### ✅ Depósito de R$250,00 realizado com sucesso!
##### Valor depositado: R$ 250,00

🏧 Saque


Ao escolher a opção Sacar, o sistema solicita ao usuário o valor que deseja retirar.
Esta operação possui as seguintes regras de negócio:
Limite de 3 saques diários.
Valor máximo de R$ 500,00 por operação.
O usuário deve ter saldo suficiente em conta para realizar o saque.
Se todas as condições forem atendidas, o valor é debitado da conta e uma mensagem de sucesso é exibida.

##### ✅ Saque de R$480,00 realizado com sucesso!
##### Valor do saque: R$ 480,00

Caso alguma das regras não seja cumprida, o sistema informará o usuário com uma mensagem de erro apropriada (ex: "Operação falhou! Você não tem saldo suficiente.", "Operação falhou! O valor do saque excede o limite.").

📄 Extrato


A opção Extrato exibe um histórico de todas as movimentações financeiras realizadas na conta (depósitos e saques).
As transações são listadas em ordem de execução.
Ao final do extrato, é apresentado o saldo atual da conta.
Caso não haja movimentações, uma mensagem informativa será exibida.
Exemplo de extrato:

#### ================ EXTRATO ================
#### Depósito: R$ 1200,00
#### Saque:    R$ 500,00
#### Saque:    R$ 150,00

#### Saldo atual: R$ 550,00
#### =========================================

🚪 Sair


Ao selecionar a opção Sair, o sistema exibe uma mensagem de agradecimento e finaliza sua execução.
Obrigado por utilizar nossos serviços!

🚀 Como Executar


Clone este repositório.
Execute o arquivo principal do projeto em um terminal (Sistema_Bancario_Python.py, por exemplo).
O menu principal será exibido.
Digite a letra correspondente à operação desejada e pressione Enter.
Siga as instruções na tela para cada operação.

🛠️ Tecnologias Utilizadas


Este projeto foi concebido para ser implementado em qualquer linguagem de programação que suporte operações de entrada e saída no console, como:

#### Python
