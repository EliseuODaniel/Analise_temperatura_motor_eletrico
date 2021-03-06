# Análise da temperatura do motor elétrico

  Análise de um conjunto de dados acerca da temperatura de um motor elétrico, disponível no site Kaggle. Tal conjunto compreende uma amostra de dados de vários sensores de um motor síncrono (motor elétrico cuja velocidade de rotação é proporcional à frequência de sua alimentação) de ímã permanente, implantados em uma bancada de teste, que representa o protótipo de um motor de uma fabricante alemã não mencionada. As medições foram realizadas no Laboratório de Eletrônica de Potência e Acionamentos Elétricos da Paderborn University na Alemanha.

  Os dados coletados foram armazenados em um arquivo csv contendo 13 colunas que descrevem as variáveis medidas e 1330816 linhas, onde cada linha representa um instantâneo dos dados dos sensores em um determinado intervalo de tempo. A taxa de amostragem é de 2 Hz, ou seja, uma linha a cada 0,5 segundos. A coleta desses dados consistiu em várias sessões de medição, que podem ser distinguidas umas das outras pela coluna "profile_id". Uma sessão de medição pode durar de uma a seis horas. O total de horas das sessões foi de 185. 

  Como especialmente a temperatura e o torque do motor não são mensuráveis de forma confiável e econômica em um veículo comercial, ser capaz de ter estimadores fortes para essas variáveis ajuda a indústria automotiva a fabricar motores com menos custo e permite gerar estratégias de controle para utilizar o motor em sua capacidade máxima, reduzindo as perdas de potência e o aumento de calor (Kirchgässner, W., Wallscheid, O. e Böcker, J., 2021).

Link do dataset: https://www.kaggle.com/wkirgsn/electric-motor-temperature

Kirchgässner, W., Wallscheid, O. e Böcker, J. (2021) "Estimating Electric Motor Temperatures With Deep Residual Machine Learning", Em: IEEE Transactions on Power Electronics, vol. 36, nº 7, p. 7480-7488.
