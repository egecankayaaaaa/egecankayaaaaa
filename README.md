import random 


karakterler =  "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
neistiyo = input('kaç tane istiyosun :')
for i in range (neistiyo):
    x = random.randint(karakterler)
    print(x)
