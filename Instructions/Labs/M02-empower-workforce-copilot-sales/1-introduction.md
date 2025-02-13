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
Para os profissionais de vendas, a comunicação efetiva é a pedra angular do sucesso. Neste módulo, você desvenda as proezas do Microsoft 365 Copilot e revela como os profissionais de vendas podem aplicar solicitações estrategicamente para levar as vendas para o próximo nível.

Para profissionais de vendas, aprimorar sua capacidade de usar o Copilot de forma eficaz não é apenas vantajoso, também é transformador no sentido de maximizar a produtividade. Esta proficiência torna-se seu aliado estratégico em vários cenários de vendas envolvendo aplicativos do Microsoft 365 – seja compondo emails de divulgação atraentes no Outlook, gerenciando interações de cliente no Excel, criando apresentações de vendas impactantes no PowerPoint ou colaborando perfeitamente no Teams.<br>

Este módulo equipa profissionais de vendas com técnicas com nuances essenciais para impulsionar o sucesso em seu percurso de vendas. Como profissional no setor de vendas, sua capacidade de usar efetivamente o Microsoft 365 Copilot é crucial para:

 -  **Automatize a entrada de dados**. O Copilot pode ajudar os profissionais de vendas a automatizar tarefas repetitivas, como entrada de dados. Por exemplo, ele pode ajudar você a capturar, acessar e registrar dados em qualquer sistema de gerenciamento de relacionamento com o cliente (CRM).<br>
 -  **Forneça insights**. O Copilot pode ajudar os profissionais de Vendas a fornecer geração de clientes potenciais e obter insights sobre seus dados de vendas. Por exemplo, ele pode ajudar você a analisar tendências de vendas, identificar oportunidades e até mesmo prever resultados futuros.<br>
 -  **Melhore a produtividade**. O Copilot pode ajudar os profissionais de vendas a economizar tempo automatizando tarefas manuais e fornecendo gerenciamento de pipeline. Por exemplo, ele pode ajudar você com agendamento, acompanhamentos e até revisão de texto.<br>
 -  **Colaboração**. O Copilot pode ajudar os profissionais de vendas a colaborar com mais eficiência. Por exemplo, ele pode ajudar você com comunicação de equipe, compartilhamento de documentos e até mesmo fornecer lembretes.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode melhorar a qualidade do seu trabalho. Os exercícios neste módulo de caso de uso foram projetados para ajudar os profissionais de vendas a criarem as seguintes habilidades:<br>

 -  Usar o Microsoft 365 Copilot no Loop para criar um relatório de pesquisa de mercado.
 -  Use o Microsoft 365 Copilot no PowerPoint para criar e personalizar uma apresentação de vendas.
 -  Use o Microsoft 365 Business Chat para resumir seus emails, reuniões e chats de um projeto específico nos últimos 30 dias e, em seguida, gerar uma lista de itens de ação, e itens de ação envolvendo uma pessoa ou tópico específico.
 -  Use o Microsoft 365 Copilot no Word para comparar três contratos de fornecedor, identificar as diferenças e fornecer ações recomendadas.
