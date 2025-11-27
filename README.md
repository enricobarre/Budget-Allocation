# OECD Budget Optimizer 🇮🇹

Questo progetto crea un'app che:
- prende una o più regioni italiane  
- un budget totale  
- e calcola la migliore allocazione per ridurre i deficit negli indicatori OECD

##  Come funziona
1. I dati finali sono in `data/final_investment_table.csv`
2. L’algoritmo usato è **greedy** (prioritizza investimenti con costo minore per punto OECD)
3. Il risultato mostra:
   - budget allocato
   - gap prima/dopo
   - residuo totale
