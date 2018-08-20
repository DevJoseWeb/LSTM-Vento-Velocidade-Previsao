# LSTM-Wind-Speed-Forecasting
No presente artigo é proposto um modelo híbrido capaz de realizar previsão de velocidade do vento (médias mensais e
horárias) com boa acurácia em regiões do nordeste brasileiro. Este modelo é elaborado a partir da combinação entre dois
modelos, o Auto-Regressivo Integrado de Médias Móveis com entradas de Variáveis Exógenas (ARIMAX) e Redes
Neurais Artificias (RNA). A escolha por estes modelos foi motivada pelo fato de que os mesmos conseguem incorporar
ambas características lineares (ARIMAX) e não-lineares (RNA) comumente existentes em séries temporais. O modelo
híbrido relaciona pressão, temperatura e precipitação com velocidade do vento, a fim de considerar características
meteorológicas locais importantes. É possível constatar a eficiência do modelo híbrido para fornecer bons ajustes aos dados
observados das velocidades dos ventos, sendo esta afirmação baseada nos valores encontrados por medidas de
acurácia, exemplo, com erro percentual médio de aproximadamente 5,0%, e valor do coeficiente de eficiência de
Nash-Sutcliffe de 0,96. Estes resultados confirmam a existência de precisão para as velocidades dos ventos previstas
acompanhando o perfil de suas observações, em especial é possível identificar semelhanças entre ambas as séries
temporais (em termos de valores máximos e mínimos), mostrando assim, a capacidade do modelo em representar
características de sazonalidade.
Palavras-chave: séries temporais, Inteligência artificial, Modelo ARXAN, Energia eólica, Nordeste brasileiro.
