
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Configuração inicial

#### Passo 1: Instalar pacotes

``` r
install.packages("remotes")

# instalar pacotes com bases de dados
remotes::install_github("curso-r/basesCursoR")

# instalar pacote da Curso-R
remotes::install_github("curso-r/CursoR")

# instalar pacotes que vamos usar durante o curso
CursoR::instalar_dependencias()
```

#### Passo 2: Criar um projeto do RStudio

Faça um projeto do RStudio para usar durante todo o curso e em seguida
abra-o.

#### Passo 3: Baixar o material

Certifique que você está dentro do projeto criado no passo 2 e rode o
código abaixo.

OBS: Assim que rodar o código abaixo, o programa vai pedir uma escolha
de opções. Escolha o número correspondente ao curso de Machine Learning
com R\!

``` r
# Baixar ou atualizar material do curso
CursoR::atualizar_material()
```

## Lista de arquivos e códigos

| Slides                                                                                                                    |
| :------------------------------------------------------------------------------------------------------------------------ |
| <a href='https://curso-r.github.io/main-intro-ml/slides/00-intro-curso.html'>slides/00-intro-curso.html</a>               |
| <a href='https://curso-r.github.io/main-intro-ml/slides/01-intro-ml.html'>slides/01-intro-ml.html</a>                     |
| <a href='https://curso-r.github.io/main-intro-ml/slides/03-modelos-de-arvores.html'>slides/03-modelos-de-arvores.html</a> |
| <a href='https://curso-r.github.io/main-intro-ml/slides/04-dataprep.html'>slides/04-dataprep.html</a>                     |

| Exemplos                                                                                                                                              |
| :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/01-tidymodels.R'>exemplos/01-tidymodels.R</a>                                               |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/02-overfitting.R'>exemplos/02-overfitting.R</a>                                             |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/03-cross-validation.R'>exemplos/03-cross-validation.R</a>                                   |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/04-hiperparametros.R'>exemplos/04-hiperparametros.R</a>                                     |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/05-regressao-linear.R'>exemplos/05-regressao-linear.R</a>                                   |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/06-regressao-logistica.R'>exemplos/06-regressao-logistica.R</a>                             |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/07-regressao-linear-com-lasso-na-mao.R'>exemplos/07-regressao-linear-com-lasso-na-mao.R</a> |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/08-normalizacao-lasso-recipes.R'>exemplos/08-normalizacao-lasso-recipes.R</a>               |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/09-exemplo-arvore-pt1.R'>exemplos/09-exemplo-arvore-pt1.R</a>                               |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/10-exemplo-arvore-pt2.R'>exemplos/10-exemplo-arvore-pt2.R</a>                               |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/11-report-credit-data.Rmd'>exemplos/11-report-credit-data.Rmd</a>                           |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/12-xgboost.Rmd'>exemplos/12-xgboost.Rmd</a>                                                 |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/13-adult.R'>exemplos/13-adult.R</a>                                                         |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/13-xgboost-sql.R'>exemplos/13-xgboost-sql.R</a>                                             |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/14-adult-exemplo-submissao.R'>exemplos/14-adult-exemplo-submissao.R</a>                     |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/15-steps.R'>exemplos/15-steps.R</a>                                                         |
| <a href='https://curso-r.github.io/main-intro-ml/exemplos/15-steps.Rmd'>exemplos/15-steps.Rmd</a>                                                     |

| Scripts feitos em aula                                                                                                                               |
| :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/01-tidymodels.R'>scripts\_feitos\_em\_aula/01-tidymodels.R</a>             |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/02-overfitting.R'>scripts\_feitos\_em\_aula/02-overfitting.R</a>           |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/03-cross-validation.R'>scripts\_feitos\_em\_aula/03-cross-validation.R</a> |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/05-regressao-linear.R'>scripts\_feitos\_em\_aula/05-regressao-linear.R</a> |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/99-ignorar.R'>scripts\_feitos\_em\_aula/99-ignorar.R</a>                   |

| Exercícios                                                                                                                    |
| :---------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/01-tidymodels.R'>exercicios/01-tidymodels.R</a>                   |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/02-overfitting.R'>exercicios/02-overfitting.R</a>                 |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/03-cross-validation.R'>exercicios/03-cross-validation.R</a>       |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/04-regressao-linear.R'>exercicios/04-regressao-linear.R</a>       |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/05-regressao-logistica.R'>exercicios/05-regressao-logistica.R</a> |
| <a href='https://curso-r.github.io/main-intro-ml/exercicios/06-random-forest.R'>exercicios/06-random-forest.R</a>             |

| Gabaritos                                                                                                                   |
| :-------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/main-intro-ml/gabaritos/01-tidymodels.R'>gabaritos/01-tidymodels.R</a>                   |
| <a href='https://curso-r.github.io/main-intro-ml/gabaritos/02-overfitting.R'>gabaritos/02-overfitting.R</a>                 |
| <a href='https://curso-r.github.io/main-intro-ml/gabaritos/03-cross-validation.R'>gabaritos/03-cross-validation.R</a>       |
| <a href='https://curso-r.github.io/main-intro-ml/gabaritos/04-regressao-linear.R'>gabaritos/04-regressao-linear.R</a>       |
| <a href='https://curso-r.github.io/main-intro-ml/gabaritos/05-regressao-logistica.R'>gabaritos/05-regressao-logistica.R</a> |

## Referências externas

#### Programação em R

  - [Livro da Curso-R (Curso-R)](https://livro.curso-r.com/)
  - [Tidyverse (Wickham H)](https://www.tidyverse.org/)
  - [R for Data Science (Wickham H)](https://r4ds.had.co.nz/)
  - [Advanced R (Wickham H)](https://adv-r.hadley.nz/)

#### Machine Learning

  - [Introduction to Statistical Learning (Hastie, et
    al)](http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)
  - [Elements of Statistical Learning (Hastie, et
    al)](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
  - [Computer Age Statistical Inference (Hastie,
    Efron)](https://web.stanford.edu/~hastie/CASI_files/PDF/casi.pdf)
  - [Tidymodels (Kuhn, et al)](https://www.tidymodels.org/)
  - [Feature Engineering and Selection: A Practical Approach for
    Predictive Models (Kuhn, Kjell)](http://www.feat.engineering/)
  - [Kaggle](https://www.kaggle.com/)

#### Miscelânea

  - [Tidytext (Silges, et al)](https://www.tidytextmining.com/)
