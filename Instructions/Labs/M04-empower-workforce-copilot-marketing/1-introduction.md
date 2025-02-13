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
O Microsoft 365 Copilot pode ajudar profissionais de Marketing de várias maneiras. Por exemplo, eles podem gerar conteúdo para campanhas, melhorar a produtividade, fornecer insights sobre campanhas, colaborar de maneira mais eficaz, entre outros. O Copilot pode sugerir hashtags relevantes, imagens e até escrever postagens nas redes sociais para você. Da mesma forma, se você estiver criando uma postagem no blog, o Copilot poderá sugerir tópicos, fornecer material de pesquisa e até ajudar você a escrever a postagem.

O Copilot também pode ajudar os profissionais de Marketing a economizar tempo automatizando tarefas repetitivas, como a formatação, a adição de gráficos e grafos e até a revisão de documentos. Além disso, o Copilot pode fornecer análises sobre como suas postagens nas redes sociais estão se saindo, quais postagens estão tendo mais participação e qual é a melhor hora do dia para postá-las. O Copilot também pode ajudar você a colaborar de maneira mais eficaz com sua equipe, auxiliando você a atribuir tarefas, definir prazos e até mesmo sugerir lembretes.

Este módulo equipa os profissionais de Marketing com as habilidades e o conhecimento necessários para que eles aproveitem a ferramenta de preenchimento de código da plataforma IA do Copilot para simplificar o fluxo de trabalho e aumentar a produtividade. Sua aptidão em se comunicar perfeitamente com o Copilot e extrair respostas precisas é fundamental para:

 -  **Gerar conteúdo**: O Copilot pode ajudar profissionais de marketing a gerar conteúdo para campanhas. Por exemplo, se você estiver criando uma postagem nas redes sociais, Copilot poderá sugerir hashtags, imagens e até escrever a postagem para você. Da mesma forma, se você estiver criando uma postagem no blog, o Copilot poderá sugerir tópicos, fornecer material de pesquisa e até ajudar você a escrever a postagem.
 -  **Melhorar a produtividade**: O Copilot pode ajudar os profissionais de marketing a economizar tempo automatizando tarefas repetitivas. Por exemplo, se você estiver criando um relatório, o Copilot poderá ajudar você com a formatação, a adição de gráficos e grafos e até a revisão do documento.
 -  **Fornecer insights**: O Copilot pode ajudar os profissionais de marketing a obter insights sobre as campanhas. Por exemplo, se você estiver realizando uma campanha de mídia social, o Copilot poderá fornecer análises sobre como suas postagens estão se saindo, quais postagens estão tendo mais participação e qual é a melhor hora do dia para postá-las.
 -  **Colaboração**: O Copilot pode ajudar os profissionais de marketing a colaborar com mais eficiência. Por exemplo, se você estiver trabalhando em um projeto com uma equipe, o Copilot poderá ajudar você a atribuir tarefas, definir prazos e até mesmo sugerir lembretes.
 -  **Integração ao Microsoft 365**: O Copilot é integrado a aplicativos do Microsoft 365, como o Teams, o Word, o Outlook, o PowerPoint e o Excel. Isso significa que os profissionais de marketing podem usar o Copilot nesses aplicativos para obter ajuda com o trabalho.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode aprimorar a qualidade do seu trabalho. Os exercícios deste módulo Caso de uso foram criados para ajudar os profissionais de Marketing a desenvolver as seguintes habilidades:

 -  Utilizar o Microsoft 365 Business Chat para analisar tendências de mercado, fornecer previsões de vendas e identificar novas oportunidades de vendas.
 -  Utilizar o Microsoft 365 Copilot no Loop para gerar ideias de campanhas de marketing para uma nova linha de produtos.
 -  Usar o Microsoft 365 Copilot no Word para consolidar três relatórios de marketing de produto em um único relatório de análise de mercado.
 -  Utilizar o Microsoft 365 Copilot no Excel para analisar tendências de mercado em uma planilha.
