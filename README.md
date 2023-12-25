# First-and-Last-number

def FirstDigit(n):
    while n>10:
         n=n/10;
    return int(n)
def LastDigit(n):
    return (n%10)
n=145398;
# end=" " means to givea a spcae between 2 numbers printed(here first and last number)
print(Firstdigit(n), end=" ")

print(LastDigit(n))
    
