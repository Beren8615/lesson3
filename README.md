import random

elements = "+-/*!&$#?=@<>"
password = ""
pass_length = int(input("Enter pass length: "))

for i in range(pass_length):
    password += random.choice(elements)

print(password)
import random

def gen_pass(pass_length):
    elements = "+-/*!&$#?=@<>"
    password = ""
    for i in range(pass_length):
        password += random.choice(elements)
    return password
