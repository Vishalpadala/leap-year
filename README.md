# leap-year
def is_leap(n):  
 
      leap=False   
  
      if year%4==0 and year%100!=0 or year%400==0: 
        
           return True    

       else:           

           return False 

year=int(input()) 

print(is_leap(year))
