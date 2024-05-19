# Prever o preço do petróleo Brent (U$D)

*FIAP: Pós Tech - Data Analytics Tech Challenge #04*

[**Link para Streamlit app**](https://brent-forecasting.streamlit.app)

**🛸 Modelos**:
- [XGBoost](https://xgboost.readthedocs.io/en/stable/)
- [Prophet](https://facebook.github.io/prophet/)

Os modelos foram treinados com dados de 20/05/1987 a 13/05/2024.

**📡 Fontes de dados**:
- [IPEA](http://www.ipeadata.gov.br/Default.aspx)
- [FRED](https://fred.stlouisfed.org/series/DCOILBRENTEU)
- [Yahoo Finance](https://finance.yahoo.com/quote/CL=F?p=CL=F)

**🧑🏻‍🚀 Autor**: [Vinícius Prado Lima](https://www.linkedin.com/in/viniplima/)

---

### Contexto
O petróleo Brent é uma classificação de petróleo extraído do Mar do Norte. Assim como o petróleo West Texas Intermediate (WTI), 
o petróleo Brent é um dos principais tipos de petróleo cru negociados no mercado internacional. 
Ambos são usado como referência para o preço do petróleo em todo o mundo e amplamente negociados em mercados de futuros.

**O problema:** criar um dashboard que apresente a construição de um modelo de Machine Learning para a previsão diária do preço do petróleo Brent.

---

### Arquivos Importantes

**main/**

- `1_data_cleanning-eda.ipynb`: coleta e análise dos dados
- `2_xgboost_model.ipynb`: construção do modelo XGBoost
- `3_prophet_model.ipynb`: construção do modelo Prophet
- `app.py`: dashboard no streamblit
- `utils.py`: funções úteis
