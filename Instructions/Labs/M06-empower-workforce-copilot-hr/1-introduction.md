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
O objetivo deste módulo é equipar os profissionais de RH com as habilidades e os conhecimentos necessários para aplicar a ferramenta de conclusão de código da plataforma AI do Copilot para simplificar seu fluxo de trabalho e aumentar sua produtividade. Para os profissionais de RH, a capacidade de usar efetivamente o Microsoft 365 Copilot é crucial para:

 -  **Recrutamento**. O Copilot pode ajudar os profissionais de RH a simplificar o processo de recrutamento. Por exemplo, ele pode ajudar você a criar descrições de trabalho, fazer triagem de currículos e até mesmo agendar entrevistas.
 -  **Integração.** O Copilot pode ajudar os profissionais de RH a integrar novos funcionários. Por exemplo, ele pode ajudar você a criar planos de integração, fornecer materiais de treinamento e até mesmo responder a perguntas comuns.
 -  **Gerenciamento de desempenho**. O Copilot pode ajudar os profissionais de RH a gerenciar o desempenho dos funcionários. Por exemplo, ele pode ajudar você a definir metas, acompanhar o progresso e fornecer comentários.
 -  **Participação do funcionário**. O Copilot pode ajudar os profissionais de RH a melhorar o envolvimento dos funcionários. Por exemplo, ele pode ajudar você a criar pesquisas, analisar resultados e até sugerir maneiras de melhorar o envolvimento.
 -  **Conformidade**. O Copilot pode ajudar os profissionais de RH a garantir a conformidade com as regulamentações. Por exemplo, ele pode ajudar você a criar políticas, acompanhar a conformidade e até mesmo fornecer materiais de treinamento.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode melhorar a qualidade do seu trabalho. Os exercícios neste módulo de caso de uso foram projetados para ajudar os profissionais de RH a criarem as seguintes habilidades:

 -  Usar o Microsoft 365 Copilot no Word para criar uma descrição de trabalho para uma nova função.
 -  Utulizar o Microsoft 365 Copilot no Word para analisar vários currículos e fornecer um relatório comparando os pontos fortes e fracos de cada candidato, classificar os candidatos dos mais qualificados para o mínimo e fazer uma recomendação.
 -  Utilizar o Microsoft 365 Copilot no Loop para criar um conjunto de perguntas de entrevista para entrevistar candidatos a esta função.
 -  Utilizar o Microsoft 365 Copilot no Outlook para criar uma carta de oferta por email para o candidato selecionado para esta função.
