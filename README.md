# Pairs Trading
## Performance comparada em períodos de crise e não crise

## Recursos

### /data

- `operations.csv`: resultado do pais trading por método da distância ([bkalil7/tcc](https://github.com/bkalil7/tcc)).
- `bear_markets.csv`: classificação dos períodos de bear market baseado em [Hartford Funds (Ned Devis Research)](https://www.hartfordfunds.com/dam/en/docs/pub/whitepapers/CCWP045.pdf).

### /assets

- `hatford_bear_markets`: resultada da comparação de performance de bear market com normal market, utilizando a classificação de bear market por Hartford

![plot](./assets/hartford_ber_markets.png)

## Próximos passos

1. Aumentar precisão na definição do momento de crise ou não crise, utilizando período de dias da operação e não apenas semestre (utilizar `distance_gate.py`)
2. Buscar outras formas de classificação de períodos de crise
3. Utilizar outros parâmetros na comparação entre períodos de crise e não crise, como Sharpe ratio