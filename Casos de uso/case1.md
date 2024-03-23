## ⚡ **1º Caso de Uso**:


### Pré-condições:
-	O sistema está em execução.
-	O usuário possui uma conta válida.
-	O usuário tentou fazer login inserindo suas credenciais de usuário (nome de usuário ou e-mail) e senha.

### Modelo: 
- **Passo 1**:O usuário tenta fazer login inserindo suas credenciais de usuário (nome de usuário ou e-mail) e uma senha incorreta.
- **Passo 2**:O sistema verifica as credenciais fornecidas pelo usuário.
- **Passo 3**:O sistema identifica que a senha inserida está incorreta.
- **Passo 4**:O sistema exibe uma mensagem de erro informando ao usuário que a senha está incorreta e fornece uma opção para redefinir a senha.

### Pós-condições:
-	O sistema mantém o estado da sessão de login do usuário.
-	O sistema exibe uma mensagem de erro indicando que a senha fornecida está incorreta.
- 	O sistema fornece ao usuário a opção de redefinir a senha.
-	O estado geral do sistema não é alterado.