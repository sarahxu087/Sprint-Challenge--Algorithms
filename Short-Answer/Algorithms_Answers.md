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
so it is n floor , I choose the mid the floor start to drop,and I only need to know if it breaks then I go down, if not break Then I go up,  then find another mid, then check if it breaks or not. so i can use binary search.
o(logn)
