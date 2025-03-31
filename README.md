# Analise-o-comportamento-dos-clientes-de-uma-fintech-com-SQL



### Analise o comportamento dos clientes de uma fintech

> Criar dashboards e analisar indicadores para definir o melhor momento para lançar um produto na jornada dos clientes de um serviço financeiro. Para isso, você colocará a mão na massa utilizando conhecimentos em SQL para desenvolver um painel gerencial com os principais indicadores dos usuários a partir de uma base de dados disponibilizadas. Afinal de contas, produtos de sucesso precisam ser orientados a dados.
> 

## **Contexto - Introdução**

A Bankverse é uma *fintech* especializada em transferências bancárias que opera nos EUA. Ela será a responsável por lançar um serviço de transferência instantânea nos Estados Unidos da América (PS: eles não têm PIX por lá…). Mas para garantir o sucesso do lançamento, seu GPM gostaria de levantar algumas informações para definir a melhor data de lançamento dessa nova funcionalidade!

Ele quer atingir o maior número de usuários possível e para isso, gostaria de lançar o produto no dia e horário com maior engajamento. Além disso, gostaria de saber qual sistema operacional deve ser priorizado no desenvolvimento, para garantir que na data esteja disponível para o maior número de usuários possível.

## Contexto - **Como começar?**

Você vai precisar analisar as informações presentes no banco de dados e criar um painel no *Metabase* para tomar essa decisão. A base de dados contém informações entre 21 de abril de 2023 e 29 de abril de 2023.

Esse painel (dashboard) precisa conter 4 gráficos solicitados pelo seu chefe:

- Gráfico de ‘meta’ do faturamento da Semana 17 (23 até 29 de abril). Sendo que a meta do período era de $400.000,00.
- Gráfico de linha do faturamento total por dia da Semana 17 (23 até 29 de abril).
- Gráfico do perfil de uso por hora dos usuários
- Gráfico de ‘pizza’ da proporção de usuários Android e IOS

Para construir esses gráficos você deverá usar as tabelas:

- Interaction
- Tax
- Transactions
- User
