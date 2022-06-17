## Soru:  '[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.'

-> Root 5 olsun 
-> [7] rootun soluna yazılır.
-> [1] sağına yazılır.
-> [8] rootun sol tarafına ve [7]den büyük olduğu için [7]nin altına yazılır.
-> [3] sağ tarafa ve [1]den büyük olduğundan rootun altına [1]in üstüne yazılır.
-> [6] rootun soluna ve [7]nin üstüne rootun altına yazılır.
-> [0] sağ tarafa en alta yazılır.
-> [9] sol tarafa ve en alta yazılır.
-> [4] rootun altına sağ tarafa yazılır.
-> [2] rootun sağ tarafına ve [3] ile [1]in arasına yazılır.

```

 Sağındakiler          Root [5]       Solundakiler
 
                  [4]             [6]        
                  
             [3]                      [7]
             
         [2]                              [8]
         
    [1]                                       [9]   
    
[0]

```
