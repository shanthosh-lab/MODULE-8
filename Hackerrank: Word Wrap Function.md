Hackerrank : # 📦 count the number of vowels and consonants
## 🎯 Aim
To Develop a python program to count the number of vowels and consonants from the given string

## 🧠 Algorithm
1. Start Input a string s.
2.  Convert the string to lowercase (to handle both uppercase and lowercase letters).
3.  Initialize two counters: vowel_count = 0, consonant_count = 0. Define the set of vowels → {A, E, I, O, U, a, e, i, o, u}.
4.  For each character ch in the string: If ch is an alphabet: If ch is in vowels, increment vowel_count.
5.   Else, increment consonant_count. Display vowel_count and consonant_count. Stop

## 🧪 Program
def fun(s):

v,c=0,0

for i in s:

if i in ['A','E','I','O','U','a','e','i','o','u']:

    v+=1

else:

    c+=1
print("Number of Vowels:",v)

print("Number of Consonants:",c) s=input()

## Sample Output
![491457768-1cf8ed22-3bed-410b-b6fa-ce3bcffe4b84](https://github.com/user-attachments/assets/522335dc-690b-4941-ac0a-cc2bd379ad34)


## Result
Thus, the program is excuted and verified.
