# timeSeries-RICE
Tentativa de treinar um modelo com ARIMA e PROPHET para analisar preço futuro de arroz.

# O que são séries temporais?
Séries temporais são conjuntos de dados ordenados por datas e horários específicos, geralmente coletados em intervalos regulares. Na programação, as séries temporais são frequentemente usadas para modelar e prever padrões ao longo do tempo. As séries temporais podem ser usadas em várias áreas, incluindo finanças, meteorologia, sensoriamento remoto, tráfego, análise de redes sociais, entre outras. Os dados de séries temporais geralmente incluem informações sobre o valor de uma determinada variável em um determinado momento, como preço de ações, temperatura, tráfego de rede, entre outros. Os desenvolvedores de software usam algoritmos específicos para analisar esses dados e identificar padrões, o que pode ajudar a prever comportamentos futuros ou identificar anomalias.<\br>

# O que é ARIMA e Prophet?
ARIMA (AutoRegressive Integrated Moving Average) é uma técnica estatística que utiliza modelos matemáticos para modelar séries temporais. Ele tenta capturar a dependência de séries temporais em seus próprios valores passados, erros passados e diferenças dos valores passados. O ARIMA é amplamente utilizado em finanças, economia, engenharia e outras áreas para prever preços, vendas, demanda, entre outras coisas.<\br>

Por outro lado, Prophet é uma técnica de modelagem de séries temporais desenvolvida pelo Facebook. Ele é projetado para ser fácil de usar e pode ser aplicado a uma ampla variedade de séries temporais, incluindo dados com feriados, tendências sazonais e mudanças em longo prazo. O Prophet é capaz de lidar com dados faltantes, bem como mudanças repentinas em tendências e sazonalidade.<\br>

Em resumo, ambos ARIMA e Prophet são técnicas poderosas para modelar e prever séries temporais. A escolha entre eles dependerá das necessidades específicas do projeto, bem como da familiaridade do usuário com cada uma das técnicas.<\br>

# Quais dados foram usados?

A análise será feita em cima dos preços de arroz liso tipo 1. Os dados foram retirados do IPEAdata.<\br>

Link de acesso: http://ipeadata.gov.br/beta3/#/dados-serie ascOrder=&base=&busca=arroz&columnOrdering=&fonte=&last=0&metaindex=1&serid=DERAL12_ATARPO12&skip=0&tema=&territoriality= <\br>

Informações dos dados: Preço médio - atacado - arroz (polido tipo 1) - 30 kg - PR.<\br>

Frequência: Mensal Fonte: Secretaria da Agricultura e do Abastecimento do Estado do Paraná, Departamento de Economia Rural (Seab-PR)<\br>

Unidade: R$<\br>

Atualizado em: 4/4/2023<\br>

Comentário: Os preços das vendas no atacado derivam de um levantamento dos preços pagos pelos varejistas ou industriais junto aos atacadistas, cerealistas, cooperativas e distribuidoras, ponderado pela comercialização regional. Os preços são calculados com base na média mensal paranaense nos últimos 12 meses e médias anuais, ambas médias simples.<\br>

Nota: O Departamento de Economia Rural (Deral), integra a Secretaria de Estado da Agricultura e do Abastecimento (Seab) e é responsável, dentre outras atividades, pela geração de dados, análise e acompanhamento do desenvolvimento de diversas cadeias da produção rural e agrícola de importância para o estado do Paraná, os quais dão suporte à propostas de políticas agrícolas.<\br>

Mais Informações: Departamento de Economia Rural - Deral<\br>
