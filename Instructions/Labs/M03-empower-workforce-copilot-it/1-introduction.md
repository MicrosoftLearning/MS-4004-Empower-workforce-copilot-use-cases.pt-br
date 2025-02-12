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
Introdução
---
O Microsoft 365 Copilot capacita os profissionais de TI a aprimorar sua eficiência, simplificar tarefas complexas e otimizar fluxos de trabalho técnicos. Com o Copilot, os profissionais de TI podem gerenciar perfeitamente as operações de TI, solucionar problemas técnicos, garantir a segurança do sistema e aplicar insights controlados por dados para a tomada de decisões estratégicas.

O Microsoft 365 Copilot serve como uma ferramenta valiosa para profissionais de TI, permitindo que eles naveguem pela complexidade do gerenciamento de tecnologia com facilidade. Com o Copilot, eles podem identificar e resolver rapidamente problemas técnicos para otimizar o desempenho do sistema. Dessa forma, o Copilot torna-se um aliado indispensável no kit de ferramentas do profissional de TI. Ao utilizar o Copilot, os profissionais de TI podem economizar tempo e se concentrar em aspectos críticos de sua função, como melhorar a confiabilidade do sistema, implementar soluções inovadoras e abordar proativamente os desafios de TI.

Este módulo equipa os profissionais de TI com as habilidades e o conhecimento necessários para aplicar a ferramenta de conclusão de código do Copilot da plataforma AI para simplificar os fluxos de trabalho e aumentar a produtividade. Como profissional de TI, sua capacidade de usar efetivamente o Microsoft 365 Copilot é fundamental para:

 -  **Automação**. O Copilot pode ajudar os profissionais de TI a automatizar tarefas repetitivas. Por exemplo, ele pode ajudar você com gerenciamento de patch, implantação de software e até monitoramento de rede.
 -  **Segurança**. O Copilot pode ajudar os profissionais de TI a garantir a segurança de seus sistemas. Por exemplo, ele pode ajudar você com detecção de ameaças, gerenciamento de vulnerabilidades e até resposta a incidentes.
 -  **Solução de problemas**. O Copilot pode ajudar os profissionais de TI a solucionar problemas com mais eficiência. Por exemplo, ele pode ajudar você com análise de causa raiz, análise de log e até sugerir soluções para problemas comuns.
 -  **Colaboração**. O Copilot pode ajudar os profissionais de TI a colaborar com mais eficiência. Por exemplo, ele pode ajudar você com o gerenciamento de projetos, a comunicação da equipe e até mesmo o compartilhamento de documentos.
 -  **Integração com o Microsoft 365**. O Copilot é integrado a aplicativos do Microsoft 365, como Teams, Word, Outlook, PowerPoint e Excel. Isso significa que os profissionais de TI podem usar o Copilot nesses aplicativos para obter ajuda com o trabalho.

O Microsoft 365 Copilot funciona como um assistente de escrita com IA. Ele entende o contexto, sugere frases e ajuda a gerar conteúdo, o que pode melhorar a qualidade do seu trabalho. Os exercícios neste módulo de caso de uso foram projetados para ajudar os profissionais de TI a construir as seguintes habilidades:

 -  Use o Microsoft 365 Business Chat para resumir as informações em uma especificação de produto e criar um plano de projeto para implementá-lo.
 -  Use o Microsoft 365 Copilot no PowerPoint para criar uma apresentação com base no plano de projeto que você criou.
 -  Usar o Microsoft 365 Copilot no Word para modificar um relatório de especificação técnica.
 -  Use o Microsoft 365 Copilot no Outlook para elaborar um email que forneça destaques do relatório de especificação técnica.
