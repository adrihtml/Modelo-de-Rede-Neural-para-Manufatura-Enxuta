# Modelo de Rede Neural para Manufatura Enxuta
Este código foi criado como parte de um projeto de eficiência energética para uma fábrica. Apesar de apresentado, não chegou a ser implementado. Para garantir a privacidade dos dados usados no projeto original, todos foram zerados e ajustados. 

Se quiser usar o código, fique à vontade para adaptá-lo às suas necessidades!

O código implementa um modelo de *rede neural* para prever a produção de uma fábrica, com base em diversos dados históricos (consumo de energia, temperatura, taxa de produção, eficiência das máquinas) e comparando com uma meta fixa. 
----------------------------------------------------------------------------------------------------------------------------------
# Funcionalidades

1. Previsão de Produção: O modelo de rede neural prevê a produção para as próximas horas com base em variáveis como consumo de energia, temperatura externa, taxa de produção e eficiência das máquinas.
2. Melhor Horário para Ligar/Desligar Máquinas: Identifica os melhores horários para ligar ou desligar as máquinas com base nas condições externas (como temperatura) e na previsão de produção.
3. Cálculo de Erro: A taxa de erro (MAE) é calculada para comparar a produção prevista com a meta estabelecida.
4. Visualização de Dados: Gráficos gerados com Matplotlib mostram a previsão de produção ao longo do tempo e comparam com a meta, além de indicarem os melhores horários para as ações de produção.

# Exemplo de Saída
O modelo retorna gráficos que indicam:

1. Previsão da Produção ao longo das próximas horas.
2. Meta de Produção.
3. Horários Ideais para ligar/desligar as máquinas com base na previsão e nas condições ambientais.

![image](https://github.com/user-attachments/assets/38770d46-7a66-4007-bf64-e42d908bfd65)

# Personalização
Dados: O modelo pode ser adaptado para usar dados reais, ajustando as variáveis conforme as necessidades do seu projeto.
Parâmetros: Ajuste as variáveis de temperatura, consumo e taxa de produção conforme os requisitos do seu cenário.

# Contribuições
Sinta-se à vontade para contribuir com melhorias ou adaptações no código. Se você tiver sugestões ou quiser personalizar a solução, basta fazer um fork e criar um pull request.

Por fim, agradeço a leitura dos pontos citados. Espero que você esteja claro como usar.

Fico à disposição em qualquer dúvida referente a este relatório. Você pode falar comigo pelo e-mail: adri.bill.cam@gmail.com
