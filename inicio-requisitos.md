## 🎈Requisitos em Linguagem Natural
- **Controle Interno Apropriado**: Apenas as pessoas da empresa devem ter acesso.
- **Interface Interativa**: Desenvolver uma interface gráfica intuitiva e fácil de usar, criando uma nova UX/UI que se adapte ao perfil de usuários não técnicos.
- **Download Simplificado**: Local onde será possível que todos as imagens e dados enviados pelos cliente possam ser baixados de uma única vez.
- **Gerenciamento de Exames**: Tornar possivél a criação de relatórios técnicos dos serviços realizados e gerênciamento dos clientes da DosImagem.

## 🛠 Requisitos Técnicos

### Funcionais
- RF-01: Identificação do usuário;

    → O sistema deve ser capaz de identificar os usuários que solicitam acesso.
- RF-02: Bloqueio de acessos indesejáveis;

    → O sistema deve ser capaz de bloquear acessos indesejáveis
- RF-03: Busca e filtragem de dados;

    → O sistema deve ter a habilidade de pesquisar, filtrar e vizualizar os dados da DosImagem
- RF-04: Geração de Relatório;

    → O sistema deve ser capaz de gerar relatórios técnicos detalhados com base nas análises realizadas
- RF-05: Integração com API;

    → O sistema deve ser capaz de se integrar com a API para troca de dados
- RF-06: Upload de imagens e dados;

    → O sistema deve permitir que os usuários façam upload de imagens e dados enviados pelo cliente
- RF-07: Gerenciamento de erros;

    → O sistema deve ser capaz de lidar com erros que possam ocorrer durante o processo de download.
- RF-08: Seleção de arquivos;

    → O sistema deve permitir que os usuários selecione os arquivos que desejam baixar 
- RF-09: Notificação de conclusão;

    → O sistema deve notificar o usuário quando o arquivo estiver pronto para download

### Não Funcionais
- RNF-01: Utilização de tecnologia Framework Front-End;

    → ***React.js***: uma biblioteca JavaScript popular para criar interfaces de usuário interativas
- RNF-02: Usabilidade → Interface projetada de forma a aumentar a eficiência da DosImagem e minimizar as curvas de aprendizagem para novos usuários;
  
    → O sitema deve apresentar um help online para auxiliar os usuários.
  
    → O sistema deve realizar tarefas como upload, visualização e análise de imagens de forma eficiente.
- RNF-03: Escalacidade;

    → O sistema deve ser capaz de lidar com o aumento de volume de dados sem degradação do desempenho
- RNF-04: Confiabilidade;

    → O sistema deve ser capaz de recuperar falhas durante o processo de download, sem perdas de dados
