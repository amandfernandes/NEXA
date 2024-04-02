## ⚡ **2º Caso de Uso**: Download 

### Descrição: 
 → Os funcionários administrativos da DosImagem possuem a capacidade de baixar todas as imagens e dados enviados pelos clientes através do site principal, utilizando a API integrada de forma eficiente e direta.

### Ator Principal: 
  → Usuário: Funcionários da DosImagem

### Pré-condições:
- Os funcionários estão devidamente autenticados no sistema.
- Os clientes já fizeram o envio de imagens e/ou dados através do site principal.
- O sistema está totalmente integrado com a API do site principal, permitindo a comunicação sem falhas.

### Fluxo Principal: 
- **Passo 1**: O sistema avisa ao usuário que o download de uma solicitação está disponível.
- **Passo 2**: Usuário navega até o sininho de notificação no canto superior direito da interface.
- **Passo 3**: O usuário clica na solicitação, que o leva para visualizar a solicitação detalhadamente. 
- **Passo 4**: O funcionário deve clicar no botão `"Download"`.
- **Passo 5**: O sistema confirma a solicitação e inicia o processo de compilação dos dados e imagens.
- **Passo 6**: Uma vez compilados, o sistema cria um arquivo compactado `.zip` e inicializa o processo de download para o dispositivo local.

### Pós-condições:
- O funcionário administraivo tem agora uma cópia local de todas as imagens e dados fornecidos pelos clientes através do site principal.
- Os dados originais permanecem seguros e inalterados no sistema principal, preservando sua integridade.
