# CausalContrastStudy
Are doctors underprescribing contrast agent medicine? Via Causal (target trial, AIPW) simulation.  

the main code is in study.ipynb, the code in the other two notebooks can be added at last-cell in study but for different purposes so I put them aside. Code is pretty short and readable!

the env+SQL/data connections is in NIH All of US (hosted on GCP). I've found that ~200GB ram + ~30cores is a sweet spot for a full run, but after Checkpt 2 you can use as low as 10GB RAM easily. 

bless ya 
