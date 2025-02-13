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
Usando o Microsoft 365 Copilot, os profissionais de finanças podem economizar tempo e esforço, simplificar o trabalho deles e tomar decisões informadas com base em insights de dados. Este módulo equipa os profissionais de finanças com as habilidades e o conhecimento necessários para usar a ferramenta de conclusão de código do Copilot da plataforma de IA para simplificar os fluxos de trabalho e aumentar a produtividade. Como profissional de finanças, sua capacidade de usar efetivamente o Microsoft 365 Copilot é crucial para:

 -  **Automatizar tarefas financeiras**: O Copilot pode ajudar os profissionais de finanças a automatizar tarefas financeiras repetitivas. Por exemplo, ele pode ajudar você com orçamento, previsão e até preparação de impostos.
 -  **Fornecer insights**: O Copilot pode ajudar os profissionais de finanças a obter insights sobre os dados financeiros deles. Por exemplo, ele pode ajudar você a analisar demonstrações financeiras, identificar tendências e até mesmo prever resultados futuros.
 -  **Melhorar a produtividade**: O Copilot pode ajudar os profissionais de finanças a economizar tempo automatizando tarefas manuais. Por exemplo, ele pode ajudar você com entrada de dados, geração de relatórios e até revisão de texto.
 -  **Colaboração**: O Copilot pode ajudar os profissionais de finanças a colaborar com mais eficiência. Por exemplo, ele pode ajudar você com o gerenciamento de projetos, a comunicação da equipe e até mesmo o compartilhamento de documentos.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode melhorar a qualidade do seu trabalho. Os exercícios neste módulo de caso de uso foram projetados para ajudar os profissionais de finanças a desenvolverem as seguintes habilidades:

 -  Use o Microsoft 365 Copilot no Outlook para criar um email para a operadora de seguros da empresa para discutir os aumentos exorbitantes em seus prêmios de seguro médico.
 -  Use o Microsoft 365 Copilot no Excel para analisar uma planilha que contém a receita projetada para campanhas de marketing do primeiro trimestre e, em seguida, adicione novos cálculos e gráficos para visualizar os dados.
 -  Use o Microsoft 365 Copilot no Word para criar um relatório de campanha de marketing com base na planilha da campanha de marketing do primeiro trimestre da empresa.
 -  Utilizar o Microsoft 365 Copilot no Word para resumir os resultados financeiros de uma empresa nos últimos cinco anos.
