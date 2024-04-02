## 🗒️ **3º Caso de Uso:  Envio de relatório**:  

### Descrição: 
* Envio do relatório, realizado pelo software interno da empresa, para o cliente

### Ator Principal: 
   Usuário: Funcionarios com o sistema oferecido pela empresa

### Pré-condições:
* Usuário está logado no sistema.
* O relatório devera está completo, com todas os dados importantes


### Fluxo Principal: 
- **Passo 1**: O Usuário entrar no sistema
- **Passo 2**: O Usuário verificar se o relatório já está disponível
- **Passo 3**: Se tiver disponível, o usuário salvar o relatório
- **Passo 4**: O Usuário deve entra na aba especifica de `"Clinic Dosimetrics"`
- **Passo 5**: O Usuário entrar no número do cliente que deseja enviar o relatório
- **Passo 6**: O Usúario colocar as informações necessárias na primeira aba e o status
- **Passo 7**: O Usúario colocar o relatório na aba de `"Arquivos"`
- **Passo 8**: O Usúario atualizar, enviando os dados para a API do website

### Pós-condições:
*   As alteraçoes ficam salvas na API
*   O cliente terá o acesso do download do relatório completo, em PDF
