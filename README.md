# coronavirus-stats-italy
Coronavirus - 2019-nCoV stats datasets for Italy and China, labels in English

## Stats Italy 
* Source: [Protezione civile](http://www.protezionecivile.gov.it/attivita-rischi/rischio-sanitario/emergenze/coronavirus)
* 2 files:
  * nationwide_it.csv: nationwide stats by date
  * region_it.csv: positive, dead, cured numbers by region by date

## Stats China
* Source: 
  * https://github.com/canghailan/Wuhan-2019-nCoV/blob/master/Wuhan-2019-nCoV.csv
  * https://github.com/JackieZheng/2019-nCoV/blob/master/Excel/data.xlsx (for nationwide stats)
* 4 files:
  * nationwide_cn.csv: nationwide stats by date
  * wuhan_cn.csv: Wuhan City stats by date (Wuhan was the epicenter of the initial outbreak and the capital city of Hubei province)
  * hubei_non_wuhan_cn.csv: Hubei Province (except Wuhan city) stats by date
  * others_non_hubei_cn.csv: Other Province (except Hubei province) stats by date
  
## Prediction Exercises:
* Time of the prediction 2020-03-12 
  * 2020-03-13: 17380 **(actual: 17660, error -1.6%)**
  * 2020-03-14: 19987
  * 2020-03-15: 26858
* Time of the prediction 2020-03-13 
  * 2020-03-14: 20309 (linear) - 20584 (log) **(actual: 21157, error -4% to -2.7%)**
  * 2020-03-15: 23152 (linear) - 24038 (log) 
  * 2020-03-16: 26162 (linear) - 27474 (log) 
* Time of the prediction 2020-03-14 
  * 2020-03-15: 25422 (linear) - 24734 (log) **(actual: 24747, error -0.05% to 2,7%)**
  * 2020-03-16: 30357 (linear) - 28545 (log) 
  * 2020-03-17: 36035 (linear) - 32502 (log) 
* Time of the prediction 2020-03-15 
  * 2020-03-16: 28707 (linear) - 28562 (log) **(actual: 27980, error 2.1%% to 2,6%)**
  * 2020-03-17: 33013 (linear) - 32527 (log) 
  * 2020-03-18: 37470 (linear) - 37509 (log) 
* Time of the prediction 2020-03-16 
  * 2020-03-17: 31338 (linear) - 31725 (log) 
  * 2020-03-18: 34785 (linear) - 36397 (log) 
  * 2020-03-19: 38264 (linear) - 41275 (log) 
