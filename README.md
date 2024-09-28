# Palindromes
Numbers between 1 and 1000 that are palindromes

for i in range(1,1001):
    if str(i)==str(i)[::-1]:
        print(i)
