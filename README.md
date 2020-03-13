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
  * 2020-03-13: 17380 <span style="color:orange">**(actual: 17660)**<span>
  * 2020-03-14: 19987
  * 2020-03-15: 26858
* Time of the prediction 2020-03-13 
  * 2020-03-14: 20309 (linear) - 20584 (log) 
  * 2020-03-15: 23152 (linear) - 24038 (log) 
  * 2020-03-16: 26162 (linear) - 27474 (log) 

