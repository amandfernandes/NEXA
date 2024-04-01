## 🗒️ **4º Caso de Uso: Analise completa**:  

### Descrição: 
* Analise completa do paciente, usando softwares da empresa

### Ator Principal: 
   Usuário: Funcionarios experientes com o sistema oferecido pela empresa

### Pré-condições:
* O formulário ,com os dados, realizado pelo paciente (incluindo as imagens)
* O software interno

### Fluxo Principal: 
- **Passo 1**: Após o download das imagens de calibração, o usuário irá colocar os dados recebido pelo paciente no software interno da propria empresa
- **Passo 2**: Com os dados, a partir do software interno, será realizado um calculo do coeficiente de calibração do paciente
- **Passo 3**: Após os calculos dos coeficientes, será realizado o calculo da dosimetria interna do paciente, utilizando a ferramenta desenvolvida pela propria empresa (Dosimagem 3D), aonde será colocado as imagens, tanto SPECT quanto CT, para realizar uma fusão
- **Passo 4.1**: Com os resultados carregados, é realizado uma simulação por Monte Carlo dos resultados
- **Passo 4.2**: Durante a simulação, é realizado também a segmentação dos orgãos e tumores, de forma automatizada, com ferramentas tanto da IA quanto manualmente
- **Passo 5**: Apos todas essas etapas, é calculado a dose absorvida para compor uma tabela 
- **Passo 6**: Após todos os calculos e resultados, é gerado relatorio em PDF, onde estará todos os resultados (exemplo: histograma, dose, volume) onde será disponibilizado na aba de `"meus serviços"` o download do relatório


### Pós-condições:
*   O cliente terá o acesso do download do relatório completo, em PDF, onde apresentará todos os dados e gráficos dos resultados
