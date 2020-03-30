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
  * 2020-03-16: 28707 (linear) - 28562 (log) **(actual: 27980, error 2.1% to 2,6%)**
  * 2020-03-17: 33013 (linear) - 32527 (log) 
  * 2020-03-18: 37470 (linear) - 37509 (log) 
* Time of the prediction 2020-03-16 
  * 2020-03-17: 31338 (linear) - 31725 (log) **(actual: 31506, error -0.5% to 0.7%)**
  * 2020-03-18: 34785 (linear) - 36397 (log) 
  * 2020-03-19: 38264 (linear) - 41275 (log) 
* Time of the prediction 2020-03-17
  * 2020-03-18: 35129 (linear) - 36094 (log) **(actual: 35713, error -1.6% to 1.1%)**
  * 2020-03-19: 38642 (linear) - 40843 (log) 
  * 2020-03-20: 42120 (linear) - 45676 (log) 
* Time of the prediction 2020-03-18
  * 2020-03-19: 39999 (linear) - 40325 (log) **(actual: 41035, error -2.5% to -1.7%)**
  * 2020-03-20: 44399 (linear) - 44980 (log) 
  * 2020-03-21: 48839 (linear) - 49862 (log) 
* Time of the prediction 2020-03-19
  * 2020-03-20: 46164 (linear) - 45934 (log) **(actual: 47021, error -2.3% to -1.8%)**
  * 2020-03-21: 51242 (linear) - 51132 (log) 
  * 2020-03-22: 56622 (linear) - 56218 (log) 
* Time of the prediction 2020-03-20
  * 2020-03-21: 53369 (linear) - 52587 (log) **(actual: 53578, error -0.4% to -1.9%)**
  * 2020-03-22: 59773 (linear) - 58138 (log) 
  * 2020-03-23: 65750 (linear) - 63727 (log) 
* Time of the prediction 2020-03-21
  * 2020-03-22: 60543 (linear) - 59452 (log) **(actual: 59138, error 0.5% to 2.4%)**
  * 2020-03-23: 67203 (linear) - 65451 (log) 
  * 2020-03-23: 73923 (linear) - 71891 (log) 
* Time of the prediction 2020-03-22
  * 2020-03-23: 65939 (linear) - 65039 (log) **(actual: 63927, error 1.7% to 3.1%)**
  * 2020-03-24: 72533 (linear) - 71351 (log) 
  * 2020-03-25: 79061 (linear) - 78088 (log) 
* Time of the prediction 2020-03-23
  * 2020-03-24: 68722 (linear) - 69898 (log) **(actual: 69176, error -0.66% to 1.04%)**
  * 2020-03-25: 73533 (linear) - 76199 (log) 
  * 2020-03-26: 78313 (linear) - 82641 (log) 
* Time of the prediction 2020-03-24
  * 2020-03-25: 74018 (linear) - 75262 (log) **(actual: 74386, error -0.5% to 1.2%)**
  * 2020-03-26: 78829 (linear) - 81434 (log) 
  * 2020-03-27: 83559 (linear) - 87283 (log) 
* Time of the prediction 2020-03-25
  * 2020-03-26: 79221 (linear) - 80307 (log) **(actual: 80539, error -0.29% to 1.64%)**
  * 2020-03-27: 83578 (linear) - 85851 (log) 
  * 2020-03-28: 87757 (linear) - 90761 (log) 
* Time of the prediction 2020-03-26
  * 2020-03-27: 85774 (linear) - 86146 (log) **(actual: 86498, error -0.84% to -0.41%)**
  * 2020-03-28: 90920 (linear) - 91130 (log) 
  * 2020-03-29: 95921 (linear) - 95255 (log) 
* Time of the prediction 2020-03-27
  * 2020-03-28: 92553 (linear) - 91573 (log) **(actual: 92472, error -0.97% to 0.09%)**
  * 2020-03-29: 98569 (linear) - 95804 (log) 
  * 2020-03-30: 104483 (linear) - 99454 (log) 
* Time of the prediction 2020-03-28
  * 2020-03-29: 98205 (linear) - 96920 (log) **(actual: 97689, error -0,79% to 0,53%)**
  * 2020-03-30: 103901 (linear) - 100828 (log) 
  * 2020-03-31: 109408 (linear) - 104385 (log) 
* Time of the prediction 2020-03-29
  * 2020-03-30: 102573 (linear) - 101776 (log) **(actual: 101739, error 0,04% to 0,82%)**
  * 2020-03-31: 107189 (linear) - 105547 (log) 
  * 2020-04-01: 111477 (linear) - 108831 (log) 
* Time of the prediction 2020-03-30
  * 2020-03-31: 104791 (linear) - 105502 (log) 
  * 2020-04-01: 107935 (linear) - 108776 (log) 
  * 2020-04-02: 111173 (linear) - 111513 (log) 
