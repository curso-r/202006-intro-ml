
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Configuração inicial

    install.packages("remotes")
    
    # instalar pacotes com bases de dados
    remotes::install_github("curso-r/basesCursoR")
    
    # instalar pacote da Curso-R
    remotes::install_github("curso-r/CursoR")
    
    # Baixar ou atualizar material do curso
    CursoR::atualizar_material()
    
    # instalar pacotes que vamos usar durante o curso
    CursoR::instalar_dependencias()

## Lista de arquivos e códigos

| Slides                                                                                                                      |
| :-------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/intro-ml-mestre/slides/00-intro-curso.html'>slides/00-intro-curso.html</a>               |
| <a href='https://curso-r.github.io/intro-ml-mestre/slides/01-intro-ml.html'>slides/01-intro-ml.html</a>                     |
| <a href='https://curso-r.github.io/intro-ml-mestre/slides/03-modelos-de-arvores.html'>slides/03-modelos-de-arvores.html</a> |
| <a href='https://curso-r.github.io/intro-ml-mestre/slides/04-dataprep.html'>slides/04-dataprep.html</a>                     |

| Exemplos                                                                                                                               |
| :------------------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/01-intro-tidymodels-pt1.R'>exemplos/01-intro-tidymodels-pt1.R</a> |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/02-intro-tidymodels-pt2.R'>exemplos/02-intro-tidymodels-pt2.R</a> |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/03-estrategias.R'>exemplos/03-estrategias.R</a>                   |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/04-bases-treino-teste.R'>exemplos/04-bases-treino-teste.R</a>     |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/05-cross-validation.R'>exemplos/05-cross-validation.R</a>         |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/06-regressao-linear.R'>exemplos/06-regressao-linear.R</a>         |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/07-regularizacao.R'>exemplos/07-regularizacao.R</a>               |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/08-regressao-logistica.R'>exemplos/08-regressao-logistica.R</a>   |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/09-exemplo-arvore-pt1.R'>exemplos/09-exemplo-arvore-pt1.R</a>     |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/10-exemplo-arvore-pt2.R'>exemplos/10-exemplo-arvore-pt2.R</a>     |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/11-random-forest.R'>exemplos/11-random-forest.R</a>               |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/12-recipes-adult.R'>exemplos/12-recipes-adult.R</a>               |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/13-recipes-hitters.R'>exemplos/13-recipes-hitters.R</a>           |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/14-xgboost.R'>exemplos/14-xgboost.R</a>                           |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/15-laboratorio-de-steps.R'>exemplos/15-laboratorio-de-steps.R</a> |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/16-diamonds.R'>exemplos/16-diamonds.R</a>                         |
| <a href='https://curso-r.github.io/intro-ml-mestre/exemplos/exemplos/99-misc-xgboost-gif.R'>exemplos/99-misc-xgboost-gif.R</a>         |

| Scripts feitos em aula                                                                                                                                    |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/202006-intro-ml/scripts_feitos_em_aula/scripts_feitos_em_aula/99-ignorar.R'>scripts\_feitos\_em\_aula/99-ignorar.R</a> |

| Exercícios                                                                                                                                       |
| :----------------------------------------------------------------------------------------------------------------------------------------------- |
| <a href='https://curso-r.github.io/intro-ml-mestre/exercicios/exercicios/tarefa-01.R'>exercicios/tarefa-01.R</a>                                 |
| <a href='https://curso-r.github.io/intro-ml-mestre/exercicios/exercicios/tarefa-02.R'>exercicios/tarefa-02.R</a>                                 |
| <a href='https://curso-r.github.io/intro-ml-mestre/exercicios/exercicios/tarefa-1.R'>exercicios/tarefa-1.R</a>                                   |
| <a href='https://curso-r.github.io/intro-ml-mestre/exercicios/exercicios/tarefa-da-aula-4.R'>exercicios/tarefa-da-aula-4.R</a>                   |
| <a href='https://curso-r.github.io/intro-ml-mestre/exercicios/exercicios/tarefa-da-aula4-resolucao.R'>exercicios/tarefa-da-aula4-resolucao.R</a> |

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
  - [Tidymodels (Khun, et al)](https://www.tidymodels.org/)
  - [Feature Engineering and Selection: A Practical Approach for
    Predictive Models (Khun, Kjell)](http://www.feat.engineering/)
  - [Kaggle](https://www.kaggle.com/)

#### Miscelânea

  - [Tidytext (Silges, et al)](https://www.tidytextmining.com/)
