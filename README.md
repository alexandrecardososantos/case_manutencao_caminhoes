# **Case - Manutenção de caminhões**
**OBJETIVO:** Diminuir os custos de manutenção.

O custo com manutenção deste
sistema específico é mostrado abaixo em dólar:

<img src="https://github.com/alexandrecardososantos/case_manutencao_caminhoes/blob/main/gr%C3%A1fico.JPG">

**Premissas**:


1. O veículo que não precisa de manutenção e é levado à manutenção possui custo 10 (**FALSO POSITIVO**);
2. O veículo que precisa de manutenção e é levado à manutenção possui custo 25 (**VERDADEIRO POSITIVO**);
3. O veículo que precisa de manutenção, porém quebra antes da manutenção possui custo 500 (**FALSO NEGATIVO**).

As principais métricas de avaliação do modelo serão a **Precisão** e o **Recall** (Sensibilidade). A alta precisão ajudará a prever os veículos que precisam de manutenção, porém mais importante ainda será o recall, pois errar por falso negativo é o mais caro.

A base de **treino** consta no arquivo **air_system_previous_years.csv**.

A base de **teste** consta no arquivo **air_system_present_year.csv**.
