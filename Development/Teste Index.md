## Índice
```dataview
table without id
  "[" + heading.text + "](#" + lower(replace(heading.text, " ", "-"))) as "Seções"
from ""
where file.name = this.file.name
flatten file.headings as heading
where heading.level <= 3
sort heading.position

```


---
# Sistema
uau

## Sistema Binário

- **Base numérica de 2 dígitos**: 0 (desligado/falso) e 1 (ligado/verdadeiro).  
- **Fundamento da eletrônica digital**: Representa estados físicos em circuitos (ex: tensão alta/baixa em transistores).  

- Popularizado por Claude Shannon (1937) ao aplicar álgebra booleana em circuitos elétricos.  
- Usado em computadores desde o ENIAC (década de 1940).  
### Sistema Triplo

1. **Lógica Computacional**: Base para operações booleanas (AND, OR, NOT).  
2. **Armazenamento**: Cada bit em memória RAM ou disco ocupa um espaço físico.  
3. **Transmissão de Dados**: Velocidades de rede são medidas em bits por segundo (bps).  
 
#### Systém

- **Menor unidade de informação**: Representa um dígito binário (0 ou 1).  
- **Termo**: Derivado de *binary digit* (dígito binário), cunhado por John Tukey (1947).  


---



