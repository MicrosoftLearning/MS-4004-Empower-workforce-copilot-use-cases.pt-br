
# Gerenciar ativos de TI usando o Microsoft 365 Copilot no Excel
---
Um gerente de TI é responsável por gerenciar um grande inventário de hardware, licenças de software e outros ativos dentro de uma organização. Cada ativo deve ser acompanhado, atualizado e relatado regularmente para garantir que a infraestrutura de TI permaneça operacional e em conformidade. O gerente tem a tarefa de analisar dados de ativos, identificar lacunas e tomar decisões orientadas por dados para melhorar a alocação de recursos.

O Microsoft 365 Copilot no Excel é uma ferramenta popular para ajudar gerentes a simplificar a análise de dados, gerar insights e automatizar tarefas repetitivas, tornando o processo mais eficiente e menos propenso a erros. Neste exercício, você assume a função de um gerente de TI que planeja usar o Copilot no Excel para ajudar no gerenciamento de ativos e relatórios.

### Exercício

Como gerente de TI da Contoso Ltd., você supervisiona a infraestrutura de TI crítica da empresa, incluindo o gerenciamento de ativos de hardware, como laptops, impressoras, servidores, roteadores e comutadores. Esses ativos são essenciais para a produtividade dos funcionários e garantir sua disponibilidade, desempenho e segurança é crucial. Uma de suas principais tarefas é acompanhar e gerenciar o ciclo de vida desses ativos, incluindo informações de garantia, histórico de reparos e status atual.

No entanto, atualmente esse processo é realizado manualmente e é demorado e propenso a erros. Você conta com várias planilhas para acompanhar as informações sobre os ativos, como datas de compra, datas de validade da garantia, históricos de reparo e alocação departamental. Apesar de seus esforços, está se tornando cada vez mais difícil monitorar todos os dados com eficiência. É fácil esquecer datas críticas de validade de garantia, levando a custos de reparo inesperados, e o processo manual de analisar tendências de ativos deixa pouco espaço para tomada de decisões rápidas.

Reconhecendo a necessidade de uma abordagem mais eficiente e precisa, você planeja usar o Copilot no Excel para:

Analisar rapidamente um arquivo que contém uma lista de ativos da empresa para identificar as principais tendências e problemas relacionados aos seus ativos de TI e suas garantias.

Gerar automaticamente gráficos e relatórios informativos para visualizar dados de ativos e identificar padrões de garantia que exigem atenção imediata.

Execute as etapas a seguir para realizar essas tarefas usando o Copilot no Excel.

1. Selecione o seguinte link para baixar a planilha de gerenciamento de ativos da Contoso: [Dados de ativos da Contoso](https://go.microsoft.com/fwlink/?linkid=2320505)
1. Depois que o download for concluído, abra o **Explorador de Arquivos** e copie o arquivo da pasta **Downloads** para a pasta **Microsoft - OneDrive**.
1. Neste exercício, você acessa o documento na lista de arquivos mais usados recentemente no Excel. Para que o arquivo apareça na lista de MRU, abra e feche o documento. 
1. Abra seu navegador Edge (se necessário) e vá para a página inicial do **Microsoft 365** inserindo a seguinte URL: **https://www.office.com**  
1. Na página inicial do **Microsoft 365**, selecione o ícone do **Excel** no painel de navegação à esquerda. Se o ícone não aparecer, selecione **Aplicativos** no painel de navegação e selecione **Excel** na página **Aplicativos**.
1. No **Excel**, role para baixo até a lista de todos os arquivos na lista de arquivos recém-usados. A guia **Todos** é exibida por padrão. Selecione o arquivo **Dados de ativos da Contoso**.
1. Com a planilha aberta no **Excel**, selecione a opção **Copilot** no lado direito da faixa de opções (se a faixa de opções não for exibida, passe o mouse sobre a guia **Início**). Fazer isso abre o painel do **Copilot**. 
1. Você quer começar fazendo o Copilot identificar os ativos cujas garantias estão vencidas ou devem expirar nos próximos 30, 60 e 90 dias. Enquanto ele faz isso, você quer que o Copilot realce garantias vencidas em vermelho, garantias que devem expirar em 30 dias (0-30 dias) em amarelo, garantias que devem expirar em 60 dias (31-60 dias) em cinza, e garantias que devem expirar em 90 dias (61-90 dias) em verde. Para concluir essa tarefa, o Copilot deve criar regras de formatação condicional para realçar os ativos dessa maneira. Depois de definir essas regras, você poderá instruir o Copilot a aplicá-las. <br><br>Para que o Copilot crie essas regras de formatação condicional, insira o seguinte prompt no campo de prompt na parte inferior do painel Copilot: **Crie as 4 seguintes regras de formatação condicional que se aplicam à coluna "Data de validade da garantia". Se a data for anterior à data de hoje, realce-a em vermelho. Se a data estiver nos próximos 30 dias, realce-a em amarelo.  Se a data estiver de 31 a 60 dias a partir de agora, realce-a em cinza. Se a data estiver de 61 a 90 dias a partir de agora, realce-a em verde**.
1. Revise cada uma das regras de formatação condicional criadas pelo Copilot. Observe especialmente a regra de 60 dias. Embora você tenha pedido ao Copilot para realçar esses ativos em cinza, nossos testes geralmente observaram que o Copilot atribuiu branco como a cor de preenchimento. Se isso acontecer com você, insira o seguinte prompt: **Na terceira regra que você criou, você atribuiu branco como a cor de preenchimento. Em vez disso, atribua cinza**. Quando o Copilot responder a esse prompt, verifique se a cor de preenchimento agora é cinza (ou cinza-claro).
1. Se as regras parecerem corretas, selecione o botão **Aplicar** exibido após as regras condicionais. Verifique se as regras são aplicadas corretamente.
1. Agora, vamos dar uma olhada em como o Copilot no Excel pode analisar os dados nesta planilha e criar vários gráficos que representam a solicitação de dados. Vamos começar inserindo o seguinte prompt: **Crie um gráfico de barras que mostra o número de laptops ativos por departamento**.
1. Revise o gráfico de barras. Agora, vamos fazer com que o Copilot crie um gráfico de pizza com base nesses mesmos dados. Digite a seguinte solicitação: **Crie um gráfico de pizza que mostra o número de laptops ativos por departamento**.
1. Observe como o gráfico de pizza exibido no painel do Copilot não inclui uma legenda. No entanto, selecione o botão **+Adicionar a uma nova planilha** que aparece abaixo do gráfico de pizza. Por sua vez, o Copilot adiciona o gráfico de pizza à **Planilha 2** e exibe a lista de laptops ativos por departamento e uma legenda abaixo do gráfico de pizza. 
1. Na **Planilha 2**, selecione o gráfico de pizza. Isso abre um painel detalhado da tabela dinâmica usada para criar esse gráfico. 
1. Selecione **Planilha 1**. Você deve estar na planilha real para fazer uma solicitação do Copilot que analise os dados da planilha. Às vezes, o Copilot exibe uma mensagem de erro se você permanece na Planilha 2 e envia um prompt com base nos dados na Planilha 1. Outras vezes, ele fornece instruções sobre como concluir sua solicitação de prompt considerando os dados limitados na tabela dinâmica da planilha atual. Em ambos os casos, você deve selecionar a planilha que contém os dados da planilha antes de prosseguir. 
1. No **Planilha 1**, repita as etapas 11 a 14, mas desta vez use os dois prompts a seguir (em que o gráfico de pizza é adicionado à Planilha 3):
   - **Crie um gráfico de barras que mostra o número de laptops ativos cuja garantia expirou por departamento**. 
      > [!NOTE]
      > Em nossos testes, às vezes, o Copilot não consegue criar esse gráfico. Se esse for o caso com sua solicitação, altere o prompt para: **Crie um gráfico de barras que mostra o número de laptops ativos cuja data de validade da garantia é anterior à data de hoje por departamento**. Se você precisar reescrever o prompt dessa maneira, isso só mostrará que, às vezes, o Copilot precisa de uma explicação mais detalhada para entender sua solicitação.
   - **Crie um gráfico de pizza que mostra o número de laptops ativos cuja garantia expirou por departamento**.
1. Selecione **Planilha 1**.
1. No **Planilha 1**, vamos ver como o Copilot no Excel pode gerar um relatório com base nos dados da planilha. Envie o seguinte prompt: **Crie um relatório que mostra o número de laptops ativos cuja garantia expirará nos próximos 90 dias por departamento**.
1. Observe como o relatório gerado no painel do Copilot é difícil de entender, dado o espaço limitado disponível nele. Para ver o relatório em sua totalidade, selecione o botão **+Adicionar a uma nova planilha** que aparece abaixo dos dados do relatório. Ao fazer isso, o Copilot adiciona o relatório à **Planilha 4**. Examine o relatório e observe o nível de detalhes que o Copilot no Excel fornece. 
