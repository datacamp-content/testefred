---
title: 'Reproduzindo Playfair'
description: 'Nesse capítulo vamos aprender a reproduzir o clássico gráfico de William Playfair, considerado por muitos como o pai de todos os gráficos.'
---

## Reproduzindo Playfair

```yaml
type: NormalExercise
key: 5ce4ea026e
xp: 100
```

A história da visualização de dados, de certa forma, está ligada a própria história da visualização de dados em finanças. Considerado por muitos como o maior pioneiro nesse ofício\arte, William Playfair, criou a maior parte dos gráficos que usamos hoje. 

E um dos gráficos mais famosos de todos os tempos, devido ao seu pioneirismo, já nasceu em finanças: Uma representação da balança comercial escocesa. Vamos observar esse gráfico e o que podemos aprender com ele ainda nos dias atuais. Além disso, vamos plotá-lo no nosso ambiente. 

Você não deve ficar preocupado com a sintaxe que vamos usar aqui. O objetivo é mostrar o potencial do ggplot e fazer uma homenagem ao Playfair.
![](https://s3-sa-east-1.amazonaws.com/storagecursosfra/Screen+Shot+2019-01-21+at+12.53.13.png)



`@instructions`
Vamos carregar nosso conjunto de dados playfair.csv usando os comandos tradicionais do R.

`@hint`
Lembre-se do comando read.csv e use ele para ler o dataset playfair.csv

`@pre_exercise_code`
```{r}
library(ggplot2)		
```

`@sample_code`
```{r}
________ <- read.___("________.___")
```

`@solution`
```{r}
playfair <- read.csv("playfair.csv")
```

`@sct`
```{r}

```
