# Configuração do Laboratório:

No restante do módulo, criaremos prompts para o Microsoft 365 Copilot que fazem referência a arquivos. Primeiro, vamos carregar todos os arquivos necessários no OneDrive para garantir que eles estejam acessíveis em todo o laboratório.


### Carregar arquivos no OneDrive

Siga as etapas abaixo para carregar todos os arquivos necessários no **OneDrive**:

1. Faça logon na máquina virtual fornecida pelo provedor de locatários como a conta de **administrador** local com a senha `Pa55w.rd`.
2. Na barra de tarefas do Windows, selecione **Microsoft Edge**.
3. Na barra de endereços, insira `https://www.office.com` .
4. Em **Bem-vindo ao Microsoft 365**, selecione **Entrar**.
5. Na **solicitação de logon**, insira `userx@yourtenant.onmicrosoft.com` (nome de usuário e locatário fornecidos pelo provedor de locatário) e selecione **Avançar**.
6. Na tela **Inserir senha**, insira a senha (fornecida pelo provedor de locatário) para a conta de usuário e selecione **Entrar**.
7. Se solicitado a **Permanecer conectado**, selecione **Não mostrar isso novamente** e, em seguida, **Sim**.
8. No **Microsoft 365**, selecione **Aplicativos**.
9. Em **Aplicativos**, selecione **OneDrive**.
10. No **OneDrive**, no canto superior esquerdo, selecione **+** (adicionar novo) > **Upload de arquivo**.
11. No **Explorador de Arquivos**, selecione **Este PC** > **Disco Local (C:)** e abra a pasta **ResourceFiles.**
12. Selecione todos os arquivos na pasta **ResourceFiles** e selecione **Abrir** para carregá-los no **OneDrive**.
13. Quando o upload for concluído, você deverá ver **Carregado 29 itens para Meus arquivos** na parte inferior central da tela.
14. Deixe o **Edge** aberto e passe para a próxima tarefa.

### Referenciando arquivos no Copilot

Ao usar o Copilot, você pode descobrir que alguns arquivos não estão imediatamente disponíveis nas sugestões. Isso ocorre porque algumas experiências do Copilot apenas fazem referência a arquivos da lista **MRU (Usados Mais Recentemente)**, enquanto outras permitem que você navegue diretamente no **OneDrive**. Para garantir que um arquivo apareça na lista **MRU**, basta abri-lo no aplicativo Microsoft 365 relevante e ele será adicionado automaticamente.

> [!IMPORTANT]
> O Microsoft 365 Copilot só funcionará com arquivos salvos no **OneDrive**. Os arquivos armazenados localmente em seu computador precisarão ser movidos para o **OneDrive** para o Copilot poder acessá-los.

À medida que avança no módulo, você terá oportunidades de experimentar vários prompts nesses arquivos. Sinta-se à vontade para experimentar diferentes abordagens para aprimorar suas habilidades com o Copilot.

# Introdução
---
Este módulo equipa os gerentes de operações com as habilidades e o conhecimento necessários para usar a ferramenta de conclusão de código da Copilot habilitada para IA para simplificar fluxos de trabalho e aumentar a produtividade. Como gerente de operações, sua capacidade de usar efetivamente o Microsoft 365 Copilot é crucial para:<br>

 -  **Gerenciamento de projetos**. O Copilot pode ajudar os gerentes de operações a gerenciar projetos com mais eficiência. Por exemplo, ele pode ajudá-los com atribuição de tarefas, agendamento e até mesmo fornecer insights sobre o desempenho do projeto.
 -  **Automação de processos**. O Copilot pode ajudar os gerentes de operações a automatizar tarefas repetitivas. Por exemplo, ele pode ajudá-los com entrada de dados, geração de relatórios e até revisão de texto.
 -  **Colaboração**. O Copilot pode ajudar os gerentes de operações a colaborar com mais eficiência. Por exemplo, ele pode ajudá-los com comunicação de equipe, compartilhamento de documentos e até mesmo fornecer lembretes.
 -  **Personalização**. O Copilot pode ser personalizado para atender às necessidades exclusivas dos gerentes de operações. Por exemplo, ele pode ajudá-los com o gerenciamento de inventário, a otimização da cadeia de suprimentos e até mesmo o controle de qualidade.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode melhorar a qualidade do seu trabalho. Os exercícios neste módulo de Caso de Uso foram projetados para ajudar os gerentes de operações a criar as seguintes habilidades:

 -  Usar o Microsoft 365 Copilot no Whiteboard para debater ideias de plano de projeto para instalar um novo sistema de caldeira.
 -  Usar o Microsoft 365 Copilot no Outlook para resumir uma thread de emails real e gerar uma resposta.
 -  Use o Microsoft 365 Copilot no Word para criar um relatório que analisa as diferenças entre sistemas de aquecimento de caldeira e de forno, ao mesmo tempo em que compara os tipos de saída que o Copilot pode gerar.
 -  Use o Microsoft 365 Copilot no PowerPoint para criar uma apresentação com base no relatório criado que analisa sistemas de aquecimento de caldeira e forno.
