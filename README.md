# Análise de Dados da Capital Bike Share com MySQL e SQLAlchemy

## 1. Introdução
A Capital Bikeshare é um serviço de compartilhamento de bicicletas na área metropolitana de DC. Ela oferece uma maneira fácil, acessível e divertida de explorar a cidade.
A Capital Bikeshare oferece opções de transporte acessíveis e divertidas para todos, independentemente da renda. Eles têm mais de 6.000 bicicletas e mais de 700 estações em 7 jurisdições: Washington, DC; Arlington, VA; Alexandria, VA; Montgomery, MD; Condado de Prince George, MD; Condado de Fairfax, VA; e a cidade de Falls Church, VA.
Existem várias opções de planos e preços disponíveis, incluindo uma única viagem, passe diário e associação anual. A Capital Bikeshare também oferece um programa de equidade expandido que permite que aqueles que se qualificam para certos programas de assistência estaduais ou federais se inscrevam individualmente.
(https://capitalbikeshare.com/)

## 2. Objetivo
O objetivo deste projeto é explorar e analisar os dados da Capital Bike Share para entender os hábitos de uso, preferências dos usuários e padrões sazonais de utilização das bicicletas compartilhadas.

## 3. Fonte de Dados
Os dados utilizados neste projeto foram coletados no último trimestre de 2023 e estão disponíveis publicamente no site da Capital Bike Share. O banco de dados MySQL é utilizado para armazenar e gerenciar os dados. (https://s3.amazonaws.com/capitalbikeshare-data/index.html).
Acrescentei uma variável a mais `duracao_segundos`, para facilitar a performance das queries e também substitui os dados ausentes nas variáveis `estacao_inicio` e `estacao_fim` por **'Unknown'**.

## 4. Principais Análises Realizadas
A seguir, são destacadas algumas das principais análises realizadas neste projeto:

* Estações Populares: Identificação das estações mais populares de início e fim de viagens.
* Contagem por Tipo de Veículo: Análise da frequência de uso por tipo de veículo (bicicletas elétricas vs. bicicletas clássicas).
* Análise por Tipo de Membro: Média de tempo de aluguel por tipo de membro (membro vs. casual).
* Padrões Sazonais: Tendências sazonais de utilização das bicicletas ao longo dos meses.
* Horários de Pico: Identificação dos horários de pico com base no número de corridas por hora.
* Duração Total do Aluguel: Cálculo da duração total do aluguel das bicicletas.
* Análise por Estação Específica: Análise detalhada de padrões de uso para estações específicas.

## 5. Conclusão
A análise de dados da Capital Bike Share forneceu insights valiosos sobre o padrão de utilização das bicicletas compartilhadas na região de DC. Esses insights podem ser utilizados para otimizar a operação do serviço, melhorar a disponibilidade das bicicletas e a experiência do usuário, bem como para orientar futuras estratégias de expansão e investimento.

Por meio da utilização de técnicas de análise de dados e visualização, foi possível extrair informações significativas que podem subsidiar tomadas de decisão e aprimorar a oferta de serviços de compartilhamento de bicicletas na área metropolitana de DC.

## Utilização

### Dependências

* Sistema Operacional:
    * Windows 10 ou 11

* MySQL
  
* Bibliotecas Python:
    * Pandas
    * SQLAlchemy
    * Mysql.connector
    * Plotly
    * Bokeh

## Autores

Nomes dos desenvolvedores do projeto e informação para entrar em contato.

Philippe Apolinário    
[@PhilippeApolinario](https://www.linkedin.com/in/philipperapolinario/)

## Histórico de versões.

* 0.1
    * Primeira versão

## Licença de uso

Esse projeto possui licença de uso [MIT] - acesse o arquivo LICENSE.md para mais detalhes
