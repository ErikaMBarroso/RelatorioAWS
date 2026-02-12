# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 12/02/2026

Empresa: Abstergo Industries

Responsável: Erika

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Erika. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:
Nome da ferramenta: AWS Cost Explorer

Foco da ferramenta: Monitoramento e análise detalhada dos custos da AWS.

Descrição do caso de uso:
O AWS Cost Explorer será utilizado para analisar os gastos da empresa em serviços AWS, permitindo identificar quais recursos estão gerando maiores despesas e onde há desperdício. Com ele, é possível acompanhar padrões de uso, visualizar tendências e tomar decisões estratégicas sobre otimização de custos. Essa ferramenta auxilia a empresa a priorizar ações de redução de despesas, garantindo maior eficiência financeira.

### Etapa 2:

Nome da ferramenta: AWS Trusted Advisor

Foco da ferramenta: Otimização de recursos e economia automática.

Descrição do caso de uso:
O AWS Trusted Advisor identifica instâncias EC2 ociosas, volumes de armazenamento não utilizados, balanceadores de carga sem tráfego e outros recursos que podem estar gerando gastos desnecessários.

### Etapa 3:

Nome da ferramenta: S3 Intelligent-Tiering

Foco da ferramenta: Reduzição automática dos custos de armazenamento ao mover dados entre camadas mais baratas conforme o padrão de acesso.

Descrição do caso de uso:
A ferramenta divide os dados em camadas diferentes conforme a frequência que esses dados são acessados. Os mais acessados ficam em "Frequent Acess" e os menos acessados em "Deep Archive Acess". A economia é gerada pois o usuário paga menos quando os dados deixam de ser acessados, evita superdimensionamento de armazenamento. Essa ferramenta é ideal para dados com padrão de acesso imprevisível.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado redução de despesas, ao mesmo tempo que mantém desempenho, escalabilidade e confiabilidade da infraestrutura, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

### Anexos

**Manuais(PDF):**

- Para o [AWS Cost Explorer](https://docs.aws.amazon.com/pdfs/cost-management/latest/userguide/cost-management-guide.pdf#ce-getting-started)
- Para o [AWS Trusted Advisor](https://docs.aws.amazon.com/pt_br/awssupport/latest/user/support-ug.pdf#trusted-advisor)
- Para o [S3 Intelligent-Tiering](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/s3-userguide.pdf#using-intelligent-tiering)

**Documentações(PDF):**

- Para o [AWS Cost Explorer](https://docs.amazonaws.cn/en_us/aws/latest/userguide/aws-ug.pdf#services)
- Para o [AWS Trusted Advisor](https://docs.aws.amazon.com/pdfs/awssupport/latest/user/support-ug.pdf#trusted-advisor)
- Para o [S3 Intelligent-Tiering](https://docs.aws.amazon.com/pdfs/AmazonS3/latest/userguide/s3-userguide.pdf#intelligent-tiering)

<img width="1430" height="713" alt="image" src="https://github.com/user-attachments/assets/52a0e4da-b287-43df-9d70-e130396afc5c" />

> *Interface do AWS Cost Explorer*

<img width="910" height="455" alt="image" src="https://github.com/user-attachments/assets/95ac1441-2237-42bc-ac90-52ea7a2b0fef" />

> *Interface do AWS Trusted Advisor*



Assinatura do Responsável pelo Projeto:

*Erika*
