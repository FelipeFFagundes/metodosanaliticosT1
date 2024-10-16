# Simulador de filas
## Configuração do projeto:
### Abra um terminal e vá ao diretório dos arquivos

Para executar: python main.py


## CONFIGURAÇÕES:  
    G/G/1/3
    G/G/3/5

## OUTPUT:
    ========================================================
    ============   QUEUEING NETWORK SIMULATOR   ============
    ===================    ====================
    ================    Flávia Webster  =================
    =========================================================
    Simulation: #1
    ...simulating with random numbers (seed '1')...
    =========================================================
    =================    END OF SIMULATION   ================
    =========================================================
    
    =========================================================
    ======================    REPORT   ======================
    =========================================================
    *********************************************************
    Queue:   Q1 (G/G/1)
    Arrival: 2 ... 4
    Service: 1 ... 2
    *********************************************************
       State               Time               Probability
          0           2.5374                0.01%
          1           4.3938                0.02%
          2           130.4041                0.54%
          3           6901.8609                28.38%
          4           17284.0828                71.06%
    
    Number of losses: 30289
    *********************************************************
    *********************************************************
    Queue:   Q2 (G/G/2/5)
    
    Service: 4.0 ... 8.0
    *********************************************************
       State               Time               Probability
          0           3.6394                0.01%
          1           1.2232                0.01%
          2           1.7561                0.01%
          3           2.7632                0.01%
          4           4.6934                0.02%
          5           3.1257                0.01%
          6           2.1990                0.01%
          7           3.0926                0.01%
          8           560.0778                2.30%
          9           6752.6123                27.76%
          10           16988.0964                69.84%
    
    Number of losses: 8045
    *********************************************************
    *********************************************************
    Queue:   Q3 (G/G/2/10)
    
    Service: 5.0 ... 10.0
    *********************************************************
       State               Time               Probability
          0           10.3462                0.04%
          1           0.2041                0.00%
          2           4.3869                0.02%
          3           0.4702                0.00%
          4           14.6243                0.06%
          5           10.2077                0.04%
          6           5.2246                0.02%
          7           9.5996                0.04%
          8           5.3350                0.02%
          9           9.1852                0.04%
          10           8.6565                0.04%
          11           6.0723                0.02%
          12           10.1983                0.04%
          13           1632.3623                6.71%
          14           8490.1259                34.91%
          15           14105.8668                57.99%
    
    Number of losses: 3270
    *********************************************************
    =========================================================
    Simulation average time: 0.7297
    =========================================================
    
    =========================================================
    Média de Tempo por Fila:
    Média de Tempo para Fila 1: 1.5021
    Média de Tempo para Fila 2: 2.9889
    Média de Tempo para Fila 2: 5.0119
    
    =========================================================
    Média Total de Todas as Filas: 3.1676
    =========================================================
    
    =========================================================
    Perdas de Clientes por Fila:
    Perdas na Fila 1: 30289
    Perdas na Fila 2: 8045
    Perdas na Fila 3: 3270
    =========================================================
    
    =========================================================
    Tempo Global da Simulação: 72969.4243
    =========================================================
    
    =========================================================
    Distribuição de Probabilidades dos Estados das Filas:
    
    Fila 1:
      Estado 0: 0.01%
      Estado 1: 0.02%
      Estado 2: 0.54%
      Estado 3: 28.38%
      Estado 4: 71.06%
    
    Fila 2:
      Estado 0: 0.01%
      Estado 1: 0.01%
      Estado 2: 0.01%
      Estado 3: 0.01%
      Estado 4: 0.02%
      Estado 5: 0.01%
      Estado 6: 0.01%
      Estado 7: 0.01%
      Estado 8: 2.30%
      Estado 9: 27.76%
      Estado 10: 69.84%
    
    Fila 3:
      Estado 0: 0.04%
      Estado 1: 0.00%
      Estado 2: 0.02%
      Estado 3: 0.00%
      Estado 4: 0.06%
      Estado 5: 0.04%
      Estado 6: 0.02%
      Estado 7: 0.04%
      Estado 8: 0.02%
      Estado 9: 0.04%
      Estado 10: 0.04%
      Estado 11: 0.02%
      Estado 12: 0.04%
      Estado 13: 6.71%
      Estado 14: 34.91%
      Estado 15: 57.99%
    =========================================================
    
    =========================================================
    Tempos Acumulados para os Estados das Filas:
    
    Fila 1:
      Estado 0: 2.5374
      Estado 1: 4.3938
      Estado 2: 130.4041
      Estado 3: 6901.8609
      Estado 4: 17284.0828
    
    Fila 2:
      Estado 0: 3.6394
      Estado 1: 1.2232
      Estado 2: 1.7561
      Estado 3: 2.7632
      Estado 4: 4.6934
      Estado 5: 3.1257
      Estado 6: 2.1990
      Estado 7: 3.0926
      Estado 8: 560.0778
      Estado 9: 6752.6123
      Estado 10: 16988.0964
    
    Fila 3:
      Estado 0: 10.3462
      Estado 1: 0.2041
      Estado 2: 4.3869
      Estado 3: 0.4702
      Estado 4: 14.6243
      Estado 5: 10.2077
      Estado 6: 5.2246
      Estado 7: 9.5996
      Estado 8: 5.3350
      Estado 9: 9.1852
      Estado 10: 8.6565
      Estado 11: 6.0723
      Estado 12: 10.1983
      Estado 13: 1632.3623
      Estado 14: 8490.1259
      Estado 15: 14105.8668
    =========================================================
    