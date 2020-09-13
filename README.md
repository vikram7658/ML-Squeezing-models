# ML-Squeezing-models

In the Phd Thesis titles "Predicting Underground Tunnel Hazards using Machine Learning Technique", avialbale freely in the link http://oa.upm.es/48301/1/Ning_Li.pdf .

Author has done anlysis on the Rock brust and Squeezing condition of different rock condition.For Rock brust the fearures taken in consideration is different as compared to squeezing rock condition. Aslo Rock brust has been checked for long terma and short term.

But I have considered only the squezzing part of thesis. I am From Nepal and Squeezing failure is very common in Himalyan Geolgy. Though the parameter value presented in this report are not as common in our parts, but the dependency of the facor to result in squeezing conditons can not be negated. 

Author has choosed models like 

In the report data are divided on the basis of feature combination. I have on other hand taken H, Q, D and SSR which is near to combination A(H, Q, D) and B(H, Q, SSR) by author. where,
    H = Overburden in (m)
    Q = Rock class type
    D = Diamete/width of tunnel (m)
    SSR = stress Strength ratio
In next model I will be using combination of (H, Q, D, K)

#Result:
Report accuracy are as follows:
      model    A          B
      SVM      77.8 %    86.7
      RF       87         90
      

The model I performed gave following result:
     model      A         
      SVM      79.16 %    
      RF       91.6        
      
