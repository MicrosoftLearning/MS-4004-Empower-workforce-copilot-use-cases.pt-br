#  Analise uma planilha financeira usando o Microsoft 365 Copilot no Excel
---
Para os profissionais de finanças, o Microsoft 365 Copilot no Excel oferece vários benefícios, como a capacidade de fazer perguntas sobre seu conjunto de dados em linguagem natural, em vez de apenas fórmulas. A ferramenta pode revelar correlações, sugerir cenários de teste de hipóteses e criar visualizações avançadas com base em suas consultas. Por exemplo, você pode usar o Microsoft 365 Copilot no Excel para dividir os dados de vendas por tipo e canal. Ou você pode projetar o impacto de uma alteração de variável em seus dados e, em seguida, gerar um gráfico para ajudar a visualizá-lo. Você também pode modelar como uma alteração na taxa de crescimento de uma variável afetaria a margem bruta.

Em resumo, ao automatizar as tarefas repetitivas, o Microsoft 365 Copilot no Excel desbloqueia abordagens mais criativas e inovadoras na força de trabalho, acelerando o progresso em várias linhas de negócios. É uma ferramenta valiosa para os profissionais de finanças que queiram otimizar seus processos diários e tomar decisões mais informadas.

Ao usar o Microsoft 365 Copilot no Excel, você deve ter uma tabela do Excel que inclua dados em uma planilha. Você pode transformar rapidamente um intervalo de células em uma tabela do Excel seguindo estas etapas:

1.  Selecione a célula ou o intervalo nos dados.
2.  Selecione **Página Inicial &gt; Formatar como Tabela**.
3.  Na caixa de diálogo **Formatar como Tabela**, marque a caixa de seleção ao lado de **Minha tabela tem cabeçalhos** se você quiser que a primeira linha do intervalo seja a linha de cabeçalho.
4.  Selecione **OK**.

Nesse exercício, você usará o Microsoft 365 Copilot no Excel para analisar uma planilha de tendência de mercado que já está em uma tabela do Excel. “Esse exercício examina muitas das funções e prompts predefinidos do Copilot.

### Exercício

Como diretor de finanças da Fabrikam, você quer analisar a eficácia das campanhas de marketing do primeiro trimestre da empresa. Seu diretor de marketing lhe forneceu uma planilha que identifica cada uma das campanhas de marketing realizadas pela empresa no primeiro trimestre. A planilha fornece valores básicos de orçamento e receita e o número de usuários direcionados e engajados. Agora é seu trabalho analisar os números para determinar a eficácia de cada tipo de campanha.

Execute as etapas a seguir para usar o Microsoft 365 Copilot no Excel para analisar os dados que aparecem na planilha de campanhas de marketing do primeiro trimestre:

1.  Selecione o link a seguir para baixar a planilha [Campanhas de marketing do primeiro trimestre da Fabrikam](https://go.microsoft.com/fwlink/?linkid=2269124).
2.  Após a conclusão do download, mova o arquivo para sua conta do OneDrive e, em seguida, abra e feche-o para obtê-lo em sua lista de arquivos MRU (mais usados recentemente).
3.  Se você tiver uma guia do Microsoft 365 aberta no navegador Microsoft Edge, selecione-a agora. Caso contrário, abra uma nova guia e insira a seguinte URL: **https://www.office.com**
4.  Na página inicial do **Microsoft 365**, selecione o ícone do **Excel** no painel de navegação à esquerda.
5.  No **Excel**, na página **Arquivo**, selecione **Campanhas de marketing do primeiro trimestre da Fabrikam** na lista de arquivos.
6.  Selecione a opção **Copilot** no lado direito da faixa de opções.
7.  No painel **Copilot** exibido, observe os prompts predefinidos exibidos acima do campo de prompt. Antes de selecionar qualquer um desses prompts predefinidos para melhorar sua análise, primeiro você quer que o Copilot faça algumas alterações específicas na planilha. Para começar, você quer que o Copilot identifique quais tipos de campanha são mais lucrativos. Para fazer isso, insira o seguinte prompt:
    
    **Criar uma tabela dinâmica para analisar a receita total gerada por cada tipo de campanha**.
8.  Examine os resultados desse prompt. O Copilot exibiu duas janelas de resposta. A primeira resposta incluiu uma tabela dinâmica que resumia a receita total por tipo de campanha. A segunda resposta incluiu uma explicação para o que fez na primeira resposta. Na primeira resposta que contém essa tabela, selecione o botão **+Adicionar a uma nova planilha**. Isso adicionará essa tabela à **Planilha 2** da planilha que o Copilot abriu para você.
9.  Ao examinar **Planilha 2**, você percebeu que o Copilot não criou um gráfico para acompanhar a tabela dinâmica. Ao examinar o prompt enviado, você percebeu que pediu que ele criasse uma tabela dinâmica, mas não mencionou nada sobre um gráfico. Você gostaria de ver uma visualização desses dados, portanto, quer inserir um prompt pedindo que o Copilot gere um gráfico para acompanhar a tabela dinâmica na **Planilha 2**. No entanto, observe que, enquanto você estiver na **Planilha 2**, o campo de prompt estará desabilitado.
    
    > **Observação:** O campo de prompt só estará habilitado na planilha que tem a tabela do Excel. Para esta planilha, essa é a **Planilha 1**. À medida que você prossegue com esse exercício, sempre que o Copilot adicionar dados a uma nova planilha, você deverá retornar à **Planilha 1** para solicitar mais alterações.
10. Selecione **Planilha 1** e, em seguida, insira o seguinte prompt:
    
    **Na Planilha 2, você criou uma tabela dinâmica para analisar a receita total gerada por cada tipo de campanha. Crie um gráfico na Planilha 2 para visualizar esses dados**.
11. Examine o resultado. Se o Copilot criou um gráfico mostrando a receita por tipo de campanha, vá para a próxima etapa. No entanto, se o Copilot exibiu uma mensagem indicando que você não pode pedir que ele funcione em uma planilha diferente da planilha original que tem a tabela do Excel, então você deverá simplificar o prompt anterior. Nesse caso, insira o seguinte prompt:
    
    **Calcule a receita total gerada por cada tipo de campanha**.
12. Examine o gráfico que o Copilot criou mostrando a receita por tipo de campanha. Se esse for o resultado esperado, selecione o botão **+Adicionar a uma nova planilha** na parte inferior da janela. Isso adicionará o gráfico à **Planilha 3** dessa planilha.
13. Ao examinar a **Planilha 3**, você observa como o Microsoft 365 Copilot incluiu a tabela dinâmica junto com o gráfico. Você percebe que a **Planilha 2** tem a mesma tabela dinâmica, enquanto a **Planilha 3** tem a tabela e o gráfico. Como você quer que a **Planilha 3** contenha a tabela e o gráfico, você decide remover a **Planilha 2** para evitar qualquer confusão futura. Para excluir a **Planilha 2**, clique com o botão direito do mouse nela, selecione **Excluir** no menu exibido e, em seguida, selecione **OK** para confirmar a exclusão. Isso deixará você com as Planilhas 1 e 3.
14. Como você quer fazer mais alterações, selecione a **Planilha 1** para retornar à sua planilha com a tabela dinâmica.
15. Agora você quer identificar quais campanhas foram as mais eficazes. Para fazer isso, você quer que a Copilot calcule o ROI (retorno sobre o investimento) de cada campanha. Para calcular o ROI, insira o seguinte prompt:
    
    **Calcule o ROI de cada campanha**.
16. Examine os resultados desse prompt. O Copilot mostrará o cálculo e você poderá selecionar a opção **Explicar fórmula** para obter uma explicação do cálculo ROI. Você quer que o Copilot adicione o ROI à planilha, portanto, selecione o botão **+Inserir coluna** que aparece na parte inferior da janela.
17. Observe os resultados. O Copilot adicionou uma nova coluna que contém o ROI para cada campanha individual. Embora isso seja bom, você quer que ele determine o ROI para cada tipo de campanha. Você percebeu seu erro ao revisar o prompt anterior. Você pediu ao Copilot que calculasse o ROI de cada campanha, quando, na verdade, queria calcular o ROI de cada tipo de campanha. Insira o seguinte prompt para calcular o ROI para cada tipo de campanha:
    
    **Essa alteração parece boa. No entanto, gostaria que você também calculasse o ROI para cada tipo de campanha**.
18. Revise os resultados. O Copilot criou um grafo mostrando o ROI por tipo de campanha. Selecione a opção na parte inferior da janela para **+Adicionar a uma nova planilha**. Isso adicionará essa tabela a uma nova **Planilha 2** da planilha. Além do gráfico de barras clusterizado criado (passe o cursor sobre o gráfico para ver o tipo de gráfico), ele também criou uma tabela dinâmica contendo o ROI por tipo de campanha. Ao concluir a revisão dos dados, selecione a **Planilha 1**.
19. Agora você quer que o Copilot determine quais campanhas foram mais eficazes em engajar os usuários. Você acha que a melhor maneira de visualizar esses dados é fazer com que o Copilot crie um gráfico que mostre a relação entre o total de usuários direcionados e o total de usuários engajados. Para fazer isso, insira o seguinte prompt:
    
    **Crie um gráfico que mostre qual campanha foi mais eficaz em engajar os usuários**.
20. Revise os resultados. O Copilot criou um gráfico de barras **Usuários Engajados por Nome de Campanha**. No entanto, se o Copilot resumiu apenas o total de usuários engajados por campanha, isso não é exatamente o que você queria. Para corrigir esse resultado, insira o seguinte prompt:
    
    **Esse tipo de gráfico não é o que eu estava procurando. Crie um gráfico que mostre a relação entre o total de usuários direcionados e o total de usuários engajados**.
21. Revise os resultados. Em nossos testes, o Microsoft 365 Copilot indicou que não poderia criar um gráfico de dispersão com esses dados. No entanto, ele explicou a tabela dinâmica criada. Se achar que esse resultado está bom o suficiente por enquanto, selecione o botão **+Adicionar a uma nova planilha** na parte inferior da janela da tabela dinâmica. Isso adicionará essa tabela à **Planilha 4** da planilha. Ao concluir a revisão desses dados, selecione a **Planilha 1**.
22. Você tem um último dado que quer que o Copilot forneça. Você gostaria que o Copilot identificasse as campanhas de melhor desempenho com base na receita gerada. Em seguida, você pode usar essas informações para identificar quais campanhas são mais lucrativas. Digite a seguinte solicitação:
    
    **Identificar as campanhas de melhor desempenho com base na receita gerada**.
23. Revise os resultados. O Copilot criou um grafo que mostra a receita por nome de campanha. Selecione a opção na parte inferior da janela para **+Adicionar a uma nova planilha**. Isso adicionará essa tabela à **Planilha** 5 da planilha. Além do gráfico de barras clusterizado criado, ele também criou uma tabela dinâmica exibindo a receita total por campanha. Ao concluir a revisão desses dados, selecione a **Planilha 1**.
24. Isso conclui os dados que você queria que o Copilot analisasse para você. No entanto, você está curioso para saber quais outras sugestões o Copilot pode ter para analisar melhor os dados da campanha. Na lista de prompts predefinidos que aparece acima do campo de prompt, procure uma sugestão intitulada **Mostrar sugestões para colunas de fórmula**. Se você vir essa sugestão, selecione-a agora. No entanto, se você não vir essa sugestão, insira-a manualmente no campo de prompt.
25. Examine a sugestão de coluna. Se você quiser adicioná-la à planilha, selecione o botão **+Inserir coluna**. Se aparecer um prompt predefinido que diz **Dê-me outra sugestão**, selecione-o agora. No entanto, se esse prompt predefinido não for exibido, insira-o manualmente no campo de prompt (em nossos testes, esse prompt predefinido às vezes aparecia antes de inserir a coluna, mas desaparecia depois que a coluna era inserida).
26. Repita a etapa anterior algumas vezes para que o Copilot sugira cálculos diferentes. Insira os que você gosta e ignore os que você não gosta.
27. Agora você quer que o Copilot mostre mais alguns gráficos que visualizam vários tipos de dados. Na lista de prompts predefinidos, selecione o botão **Mostrar insights de dados**.
28. Revise os resultados. Se esse gráfico for de seu interesse, selecione o botão **+Adicionar a uma nova planilha** e, em seguida, volte para **Planilha 1**.
29. Em seguida, selecione o botão **Posso ver outro insight?**. Novamente, se esse gráfico for de seu interesse, selecione o botão **+Adicionar a uma nova planilha** e retorne à **Planilha 1**.
30. Depois de ver esses dois primeiros gráficos, você percebe que gosta dos vários gráficos que o Copilot oferece. Em vez de examinar mais gráficos um a um, você quer que o Copilot adicione à sua planilha todos os insights que ele pode criar com base em seus dados. Nos prompts predefinidos, selecione o prompt **Adicionar todos os insights à grade**.
31. Revise os resultados. O Copilot criou vários gráficos na folha final, juntamente com várias tabelas dinâmicas. Você determinou que sua análise está completa com todos os dados fornecidos pelo Microsoft 365 Copilot no Excel. Como o Excel salvou automaticamente o arquivo, feche a guia do navegador Microsoft Edge.
