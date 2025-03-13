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
Como um líder que navega no cenário dinâmico do mundo corporativo, a comunicação eficaz é fundamental. Neste módulo de caso de uso, você explorará como os executivos podem maximizar a eficácia do Microsoft 365 Copilot, elevando sua capacidade de criar prompts, perguntar e articular ideias sem complicações.<br>

Como alguém que está em uma posição de liderança executiva, refinar sua capacidade de usar efetivamente o Copilot é crucial para aproveitar todo o seu potencial. Você pode usar essa habilidade em várias tarefas executivas envolvendo todos os aplicativos do Microsoft 365. Por exemplo, desde a elaboração de relatórios no Microsoft Word até a análise de dados no Excel, a criação de apresentações no PowerPoint e muito mais.<br>

Este módulo o orientará no desenvolvimento das técnicas de solicitação diferenciadas necessárias para usar o Copilot de forma eficiente, economizando tempo e aumentando a produtividade em suas responsabilidades diárias. Como executivo, sua capacidade de usar efetivamente o Microsoft 365 Copilot é crucial para:

 -  **Produtividade**. O Copilot pode ajudar os executivos a economizar tempo automatizando tarefas repetitivas. Por exemplo, ele pode ajudar com agendamento, gerenciamento de email e até revisão de textos.<br>
 -  **Insights**. O Copilot pode ajudar os executivos a obter insights sobre seus negócios. Por exemplo, ele pode ajudar a analisar dados financeiros, identificar tendências e até mesmo prever resultados futuros.<br>
 -  **Colaboração**. Copilot pode ajudar os executivos a colaborar com mais eficiência. Por exemplo, ele pode ajudar com o gerenciamento de projetos, a comunicação da equipe e até mesmo o compartilhamento de documentos.<br>
 -  **Personalização**. O Copilot pode ser personalizado para atender às necessidades exclusivas dos executivos. Por exemplo, ele pode ajudar com planejamento estratégico, gerenciamento de riscos e até gerenciamento de crises.<br>
 -  **Integração ao Microsoft 365**. O Copilot é integrado a aplicativos do Microsoft 365, como o Teams, o Word, o Outlook, o PowerPoint e o Excel. Isso significa que os executivos podem usar o Copilot nesses aplicativos para obter ajuda com seu trabalho.<br>

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode aprimorar a qualidade do seu trabalho. Os exercícios neste módulo de Caso de Uso foram projetados para ajudar os executivos a criar as seguintes habilidades:<br>

 -  Use o Microsoft 365 Business Chat para sintetizar seus insights de comunicação envolvendo um tópico específico.
 -  Usar o Microsoft 365 Copilot no Word para criar uma fala que você planeja entregar aos acionistas da empresa.<br>
 -  Usar o Microsoft 365 Copilot no PowerPoint para criar uma apresentação com base na fala que você criou.
 -  Usar o Microsoft 365 Copilot no Teams para resumir uma reunião na qual você participou e listar os pontos-chave.