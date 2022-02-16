# leap-year
def is_leap(n):   
  
      leap=False   
  
      if year%4==0 year%100!=0 year%400==0: 
        
           return True    

       else:           

           return False 

year=int(input()) 

print(is_leap(year))
