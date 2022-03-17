# Ass-1-17-03-2022
to remove vowels from string


s = input()
vowels = ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']
for c in s:
    if c in vowels:
        s = s.replace(c, "")
print( s)

o/p:
this is aditya college
ths s dty cllg
