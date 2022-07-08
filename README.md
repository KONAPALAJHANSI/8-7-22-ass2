s=input()
p=""
for i in s:
    
    if i not in p:
       
        if i.isalpha():
            p=p+i
print(p)
k=list(input())
