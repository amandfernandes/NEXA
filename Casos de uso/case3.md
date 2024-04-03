## ⚡ **3º Caso de Uso:  Envio de relatório**:  

### Descrição: 
→ Envio do relatório, realizado pelo software interno da empresa, para o cliente

### Ator Principal: 
→ Usuário: Funcionarios da empresa

### Pré-condições:
- Usuário está logado no sistema.
- O relatório deverá está completo, contendo todos os dados importantes

### Fluxo Principal: 
- **Passo 1**: O Usuário navegar até a seção do serviço desejado.
- **Passo 2**: O sistema exibe uma lista com todas as solicitações em andamento.
- **Passo 3**: O funcionário seleciona a solicitação que deseja visualizar detalhadamente.
- **Passo 4**: Usuário seleciona o botão `"Enviar Relatório"`
- **Passo 5**: O Usuário verificar se o arquivo do relatório (`".pdf"`) já está disponível, se sim, o anexa.
- **Passo 6**: Funcionário aperta o botão `"enviar"`.
- **Passo 7**: O sistema envia o relatório para o cliente, através da API

### Pós-condições:
- As alteraçoes ficam salvas na API
- O cliente terá acesso ao download do relatório completo
