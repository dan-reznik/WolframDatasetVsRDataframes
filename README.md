# WolframDatasetVsRDataframes
1. compares size and creation times for wolfram Datasets[] vs tidyverse 0.8.0 "tibbles" (dataframes)
2. creating 2-column datasets containing 1,10,100,...,1M,10M rows take 35x more time in mathematica 10 than R 3.5.2
3. w/ 2 simple columns, the above datasets have 33x larger memory footprint in mathematica than tidyverse tibbles

# Conclusion
Until mathematica's datasets are not redesigned to be columnar (so names don't repeat in associations) and that functions relevant to dataframes can take datasets directly, mathematica won't be used as a serious platform for scalable, expressive, data wrangling / science (the fact that it is not free doesn't exactly help it)
