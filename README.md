b) NameNode é o no mestre do HDFS, responsável por gerenciar o namespace do sistema, controlar o acesso dos clientes aos arquivos e armazenas metadados em todos os arquivos.<br>
DataNode é um nó slave que armazena em blocos reais de dados de um ficheiro e processa as solicitações de leitura e escrita. <br>
Se o nameNode falhar o cluster inteiro fica indisponivel, pois o namenode é o ponto unico que gerencia os metadados. <br>

c)Em comparação ao SGBD o hadoop tem como vantagem: <br>
Custo: É economico por usar um hardware comum e de baixo custo, para grande volumes de dados. <br>
Suporta diversos tipos de dados, estruturados e não estruturados <br>
Tolerancia a falhas: replica os dados em multiplos nós, recuperando automaticamente de falhas.
Análise de Big Data: Excelente para grandes conjuntos de dados e processos ETL  (extrair, transformar e carregar) 

Desvantagens:
Latencia: acessa o disco com frequencia, resultando em tarefas mais lentas.
Complexidade do mapReduce: a curva de aprendizado do mapReduce para escrever e gerenciar dados pode ser ingreme.
Segurança: Não possui uma segurança muito robusta.
gerenciamento de recursos: a otimização de tarefas e gerenciamento de recursos pode ser ineficiente em cluster grandes.
