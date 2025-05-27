# dio-dashboard
Projeto do bootcamp ofertado pela DIO para criar uma planilha do Excel com o objetivo de demonstrar uma dashboard.<br>
-------------------------------------------------------------------------------------------------------------------
1. Objetivos:
- Manter uma base de dados (aba "Bases") de usuários dos serviços do Xbox online.
- Montar uma tabela dinâmica (aba "Cálculos") para melhor visualizar as informações dos clientes inscritos nos serviços ofertados.
- Demonstrar, visualmente, a síntese de informações da planilha em uma dashboard (aba "Dashboard").
-------------------------------------------------------------------------------------------------------------------
2. Dados utilizados:<br>
- Na aba "Assets", o usuário encontrará os arquivos de imagem e códigos hexadecimais das cores utilizadas na planilha.
- Na aba "Bases", o usuário encontrará uma tabela listando os dados dos usuários dos serviços oferecidos. A lista contém as seguintes informações dos usuários: id; nome completo; plano de assinatura; data de início da assinatura; se autorenova ou não; preço da inscrição; tipo de inscrição; se possui serviços adicionais como "season pass" vinculado aos serviços da EA ou Minecraft; os preços das inscrições nos serviços ofertados pela EA e Minecraft; valor total dos serviços contratados. 
-------------------------------------------------------------------------------------------------------------------
3. Forma de reprodução:
- Aba Assets:
  - Na aba "Assets", o usuário pode adicionar imagens ou códigos hexadecimais, com o intuito de utilizá-los de maneira mais ágil nas demais abas da planilha e manter a coerência visual de elementos.
- Aba Bases:
  - Na aba "Bases", o usuário utilizará uma base de dados (tabela) contendo as informações dos clientes dos serviços do Xbox (vide item 2 sobre os detalhes da tabela). Filtros posicionados no cabeçalho permitirão fácil consulta a detalhes relevantes na ocasião e devem ser mantidos, mesmo que não utilizados constantemente.
- Aba Cálculos:
  - Na aba "Cálculos", o usuário deverá utilizar a tabela da aba anterior ("Bases") para elaborar uma tabela dinâmica baseada no intervalo completo da base de dados. Ele pode montar quantas desejar, mas as pré-estabelecidas neste arquivo respondem a algumas perguntas de negócios exemplificativas.
  - Crie, também, um campo de infodados para extrair o valor total das tabelas dinâmicas criadas (ou outros dados, se o usuário desejar focar em outros aspectos).
- Aba Dashboard:
  - Na aba "Dashboard", o usuário deverá elaborar um menu lateral, contendo as seguintes informações:
    - A imagem de um avatar feminino ou masculino (mantido na aba "Assets"), de acordo com o usuário escolhido para o Dashboard.
    - O nome do usuário, retirado da base de dados dos usuários (aba "Bases")
    - Uma segmentação de dados a partir da tabela dinâmica (aba "Cálculos"), contendo a filtragem por meio do tipo de plano de inscrição (mensal, quarternário ou anual).
  - Nas primeiras linhas do dashboard, reserve um espaço para exibir o logo do Xbox (mantido na aba "Assets") e modifique o estilo do mesmo ao seu gosto (sugerido: Título 1).
  - Abaixo do título, insira duas formas geométricas paralelas e dentro das mesmas adicione um título que informe que aquela forma indica o valor total de inscrições em um determinado serviço (vide as tabelas dinâmicas das perguntas de negócio 3 e 4 na aba "Cálculos"), inserindo dentro de uma das formas o logo da EA e na outra o logo do Minecraft. Ao lado do logo, insira, também, o campo de infodados atrelado a tabela dinâmica.
  - Insira, abaixo dos campos com os valores totais da EA e Minecraft, um gráfico dinâmico de barras que tem como base a tabela dinâmica correspondente às perguntas de negócio 1 e 2 (aba "Cálculos"); elimine os elementos que não sejam as barras do gráfico para reduzir a poluição visual.
  - Mantenha todo o esquema de cores uniforme, utilizando as cores sugeridas na aba Assets.
