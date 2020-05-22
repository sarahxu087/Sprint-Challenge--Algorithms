#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) if a >b:
      return True
   else:
      return False
o(1)


b) for i in range(0,len(x),2):
       return x[i]
o(log n)


c)  for value in date:
        print(value)
o(n)
## Exercise II
if we have one egg, then we need to drop,the worst case would be drop every floor, so it will return floor, if we only have one floor,then we only need drop one time, it will return floor too.


for current in range(1, floor+1):
        #worst case
    max(drop(egg,floor-curren),drop(egg-1,current-1))
             egg don't break    egg break


real case need to be worset case +=1
o(2**n)
