# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 10/09/2025  
Empresa: Abstergo Industries  
Responsável: Jorge Luís Torres  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Jorge Luís Torres. O objetivo do projeto foi implementar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- AWS Cost Explorer
- Monitoramento e análise de custos na nuvem
- A equipe de TI da Abstergo Industries implementou o AWS Cost Explorer para realizar uma análise mensal aprofundada dos gastos na nuvem. Com este serviço, conseguimos identificar rapidamente recursos subutilizados, entender os padrões de consumo e gerar relatórios detalhados de custos por serviço e departamento. Essa visibilidade granular nos permitiu tomar decisões informadas e aplicar medidas corretivas, resultando em uma redução imediata das despesas.

Etapa 2:
- AWS Lambda
- Execução de processos sob demanda sem necessidade de gerenciar servidores
- Para otimizar a execução de tarefas rotineiras, configuramos funções AWS Lambda. Essas funções são acionadas automaticamente sempre que novos dados são adicionados ou eventos específicos ocorrem, realizando backups de dados e processando logs. Ao utilizar o Lambda, eliminamos a necessidade de manter instâncias EC2 em execução contínua para essas tarefas, o que trouxe uma significativa redução nos custos operacionais e aumentou a eficiência na gestão de recursos.

Etapa 3:
- AWS S3 Intelligent-Tiering
- Armazenamento otimizado para redução de custos
- Dados históricos e backups foram migrados para buckets S3 configurados com o Intelligent-Tiering. Esse recurso move automaticamente os dados entre camadas de armazenamento de menor custo (como Standard-IA e Glacier Instant Retrieval) conforme a frequência de acesso. Dessa forma, garantimos economia substancial nos custos de armazenamento, sem comprometer a disponibilidade ou o desempenho, mantendo os dados facilmente acessíveis sempre que necessário.
