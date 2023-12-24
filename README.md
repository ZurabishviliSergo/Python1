import random

ltrs = 'QWERTYUIOPASDFGHJKLZXCVBNM1234567890qwertyuiop4asdfghjklzxcvbnm'
num = input('Ввести количество паролей: ')
lng = input('Ввести длину пароля: ')
num = int(num)
lng = int(lng)

for n in range(num):
 password = ''
for i in range(lng):
 password = password + random.choice(ltrs)
print(password)
