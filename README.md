# 📊 Passos realizados-
- primeiro acessei o arquivo onde contém os datasets que foram disponibilizados pelo professor;
- Baixei o dataset chamado: "dataset 500-curso-sagemaker-canvas-dio";
- apliquei o dataset ao sagemaker canvas;
- após fazer o upload do arquivo no canvas, selecionei o item no qual eu gostaria de realizar a análise(quantidade de estoque);
- aguardei 10 minutos para que a análise fosse feita.


## 🎯 DADOS COLETADOS 
![Captura de tela 2024-07-29 175955](https://github.com/user-attachments/assets/e0ddf696-8fa3-4e76-ab6d-c610222c2eee)

Avg.wQL 0.860= representa a média ponderada de perdas, quanto mais próximo de zero for o valor, mais precisa será a previsão, o valor foi relativamente bom, já que o tempo de preparo da máquia foi de mais ou menos 10 minutos 
MAPE 0.290= representa o erro percentual médio absoluto, ou seja, é a diferença entre as porcentagens médias do  valor previsto/esperado e valor real. caso o valor seja 0, o modelo é perfeito, sem margens de erro.
WAPE 0.152= representa o erro percentual absoluto ponderado, leva em consideração a importância de cada item no estoque, itens de maior importãncia causarão um maior impacto na métrica, um WAPE menor é mais desejado pois significa que o modelo está prevendo com mais precisão para os itens mais críticos.
RMSE 1.535= representa a rais do erro quadrático médio, mede a diferença média entre os valores da previsão e os valores reais, com um RMSE menor, a previsão fica mais próxima do valor real.
MASE 0.180= representa o erro escalao médio absoluto, compara o erro da previsão com um moelo simples. Com MASE menor que 1 signfica que o modelo está fazendo previsões mais precisas. (no caso do meu modelo, deu 0.180) isso não é um bom sinal pois o modelo não está com uma precisão boa.
   Mesmo que o valor da MASE não tenha sido muito boa, o restante do modelo não houve nenhum erro ou algo fora do comum, foi importante para identificar e definir se o modelo atende a expectativa esperada para seu próprio negócio.



## 🚀 PREVISÕES
- previsões pessimitas representada por P10
- previsões conservadoras ou neutras representadas por P50
- previsões otimistas são representadas por P90


   Essas previsões são importantes para observar quando, por exemplo, algum produto terá pouca demanda, muita ou com um valor próximo do habitual.
