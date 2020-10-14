## Get the Year and check whether it is leap year or not
- **A year is leap year if the following conditions are satisfied:**
  - Year is multiple of 400.
  - Year is multiple of 4 and not multiple of 100.
## Sample Code 
```
if year%4==0:
        if year%100==0:
            if year%400==0:
               print(year,'is a Leap Year')
            else:
               print(year, "is not a Leap Year")
        else:
            print(year,'is a Leap Year')
    else:
        print(year, "is not a Leap Year")
 ```
 ## Example Ouput:
 ```
Enter year:2000
2000 is a Leap Year
```
