## 🎈Requisitos em Linguagem Natural
- O sistema deve ser capaz de identificar os usuários que tenham permissão 
- O sistema deve apresentar uma interface simples e intuitiva 
- O sistema deve ser capaz de enviar os relatórios técnicos para o cliente já finalizados
- O sistema deve pemitir visualização das solicitações recebidas 
- O sistema deve permitir que os usuários façam upload de imagens e dados enviados pelo cliente 
- O sistema deve ser capaz de lidar com erros que possam ocorrer durante o processo de download.
- O sistema deve permitir que os usuários consigam anexar os resultados das analises
- O sistema deve notificar o usuário quando receber novas solicitações

## 🛠 Requisitos Técnicos

### Funcionais
* RF-01: Controle de acesso ao sistema (Login)
O sistema deve controlar o acesso
Como desenvolvedor, quero que o sistema identifique cada usúario e suas permissões dentro do sistema.

* RF-02: Cadastro de usúarios
O sistema deve ter uma interface para cadastrar 
Como desenvolvedor, quero que o sistema mantenha todos os dados dos usuários cadastrados

* RF-03: Geração de relatório
O sistema deve ter a capacidade gerar e armazenar relatórios
Como desenvolvedor, quero que o sistema guarde os arquivos dentro da sua API

* RF-04: Enviar arquivos na API
O sistema deve enviar os arquivos e relatórios e armazenar dentro da API
Como desenvolvedor, quero que o sistema disponibilize o relatório para o cliente

### Não Funcionais
- RNF-01: Utilização de tecnologia Framework Front-End;

    → ***React.js***

* 1. Identificação de Usuários:

O sistema deve identificar os usuários que tenham permissão para acessar o sistema.
Como desenvolvedor, eu quero que o sistema verifique as credenciais do usuário antes de conceder acesso.
Condições:
O usuário deve ter um nome de usuário e senha válidos.
O usuário deve ter permissão para acessar o sistema.
* 2. Interface do Sistema:

O sistema deve apresentar uma interface simples e intuitiva para facilitar o uso.
Como desenvolvedor, eu quero que o sistema seja fácil de navegar e usar.
Condições:
O sistema deve ter menus e ícones claros.
O sistema deve ter instruções e dicas de ajuda.
* 3. Envio de Relatórios:

O sistema deve ser capaz de enviar os relatórios técnicos para o cliente já finalizados.
Como desenvolvedor, eu quero que o sistema envie os relatórios automaticamente por e-mail após a finalização.
Condições:
O cliente deve ter um endereço de e-mail válido.
O relatório técnico deve estar em formato PDF.


* 4.  Regras Adicionais:

O sistema deve permitir que os usuários criem e editem seus perfis.
O sistema deve ter um sistema de backup para garantir a segurança dos dados.
O sistema deve ser acessível em diferentes dispositivos, como computadores, tablets e smartphones.
