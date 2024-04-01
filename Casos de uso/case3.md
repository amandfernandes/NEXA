## **3ºCaso de Uso**: Recuperação de Senha

### Descrição:
  → Este caso de uso descreve o processo pelo qual o usuário pode recuperar sua senha caso a tenha esquecido, utilizando um método de recuperação de senha.

### Ator Principal:

  → Usuário: Funcionários da DosImagem, especificamente o administrativo

### Pré-condições:

- O sistema está em execução.
- O usuário possui uma conta válida.
- O usuário esqueceu sua senha e deseja recuperá-la.

### Fluxo Principal:

- **passo 1**: O usuário acessa a opção de recuperação de senha na página de login.
- **passo 2**: O sistema apresenta opções para o usuário escolher o método de recuperação de senha.
- **passo 3**: O usuário seleciona um método de recuperação de senha disponível, como e-mail, SMS ou pergunta de segurança.
- **passo 4**: O usuário fornece as informações necessárias de acordo com o método escolhido, como endereço de e-mail, número de telefone ou respostas às perguntas de segurança.
- **passo 5**: O sistema valida as informações fornecidas pelo usuário.
- **passo 6**: Se as informações forem válidas, o sistema envia um link de redefinição de senha para o usuário por e-mail, SMS ou apresenta uma página para definir uma nova senha.
- **passo 7**: O usuário acessa o link enviado pelo sistema ou insere a nova senha na página apresentada.
- **passo 8**: O sistema valida a nova senha conforme os critérios de segurança estabelecidos.
- **passo 9**: Se a nova senha for válida, o sistema atualiza a senha na base de dados e confirma a recuperação da senha.
- **passo 10**: O sistema redireciona o usuário para a página de login.

### Pós-condições:

- O sistema permite que o usuário recupere sua senha utilizando um método de recuperação de senha.
- A senha do usuário é alterada com sucesso.
- O usuário é capaz de fazer login com a nova senha.

### Extensão (Fluxo Alternativo):

- Se as informações fornecidas pelo usuário não forem válidas, o sistema exibe uma mensagem de erro e permite que o usuário tente novamente.
- Se o usuário cancelar o processo de recuperação de senha, o sistema redireciona o usuário de volta para a tela de login.
