Ator Diretor:
Usuário: Cliente da Dosimagem (paciente ou médico)

Pré-condições:

O usuário deve ter acesso à internet.
O usuário deve ter um login e senha no site da Dosimagem.
O usuário deve ter um exame de imagem recente (PET-CT ou SPECT) em formato digital.
Fluxo Principal:

Passo 1: O usuário acessa o site da Dosimagem e faz login em sua conta.

Passo 2: O usuário seleciona a opção "Solicitar Dosimetria".

Passo 3: O usuário preenche um formulário com seus dados pessoais, informações sobre o seu tumor e anexa o exame de imagem.

Passo 4: A Dosimagem calcula a dose de radiação ideal para o paciente e envia o plano de tratamento personalizado para o médico do paciente.

Pós-condições:

O paciente recebe um plano de tratamento personalizado para o seu tumor.
O médico do paciente tem acesso à informação necessária para tomar as melhores decisões sobre o tratamento do paciente.
Extensão (Fluxo Alternativo):

Passo 1: O usuário acessa o site da Dosimagem e faz login em sua conta.

Passo 2: O usuário seleciona a opção "Acompanhar Processo de Dosimetria".

Passo 3: O usuário digita o número do seu pedido de dosimetria.

Passo 4: O usuário visualiza o status do seu pedido de dosimetria, incluindo a data de envio, a data de conclusão e o plano de tratamento personalizado.
### Pós-condições:
-	O sistema mantém o estado da sessão de login do usuário.
-	O sistema exibe uma mensagem de erro indicando que a senha fornecida está incorreta.
- 	O sistema fornece ao usuário a opção de redefinir a senha.
-	O estado geral do sistema não é alterado.

### Extensão(Fluxo Alternativo):
- Se o usuario optar por redefinir senha, o sistema deve iniciar o caso de uso de Recuperação de senha.
- Se o usuário optar por tentar novamente, o sistema permanece na tela de login, permitindo que o usuário insira as credenciais novamente.
