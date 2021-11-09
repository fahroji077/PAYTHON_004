# PAYTHON_004

1. Perulangan For

```y
nambers = [1, 2, 3, 4, 5]

for item in nambers:
    print(item * 5)

for item in range(1, 11, 2):
    print(item)
    
```
![image](https://user-images.githubusercontent.com/93015185/140929601-8486d088-9e5c-45d2-a2c6-4a9e07018a26.png)

2. List
```y
namas = ["fahroji", "muhammad", "oji", "aji"]

for nama in namas:
    print(f"nama : {nama}")
```
![image](https://user-images.githubusercontent.com/93015185/140929858-664698e3-4bfa-4847-8b52-1b290b4fd11a.png)

3. List Method

```y
nambers = [5, 6, 7, 8, 1]
print(nambers)

nambers.append(99)
print(nambers)

nambers.insert(2, 100)
print(nambers)

nambers.pop(5)
print(nambers)

nambers.remove(8)
print(nambers)

nambers.sort()
print(nambers)
```
![image](https://user-images.githubusercontent.com/93015185/140930011-22314345-3d63-4788-a649-65f430591e29.png)

4. Menjumlahkan List

```y
numbers = [5, 6, 7, 8, 1]

init_numbers = 0
for numbers in numbers:
    init_numbers = init_numbers + numbers

print(init_numbers)
```
![image](https://user-images.githubusercontent.com/93015185/140930160-53086f96-a996-4a21-8cfa-3928aef47cb5.png)

5. Mencari Angka Max

```y
#soal 1
numbers = [5, 6, 7, 8, 1]

max_numbers = max(numbers)
print(max_numbers)

#soal 2
numbers = [5, 6, 7, 8, 1]

numbers.sort()
max_numbers = numbers[-1]
print(max_numbers)

#soal 3
numbers = [5, 6, 7, 8, 1]

max_number = numbers[0]

for number in numbers:
    if number > max_numbers:
        max_numbers = number

print(max_numbers)
```
![image](https://user-images.githubusercontent.com/93015185/140930253-83fedc88-4830-42c5-9864-381815b9ebeb.png)

6. Tuple

```y
numbers = (5, 6, 7, 8, 1)
print(numbers[4])
```
![image](https://user-images.githubusercontent.com/93015185/140930470-a7d87182-e482-49f0-ae15-0bf9f403b8f2.png)

7. Unpack

```y
numbers = (1, 3, 5,)

# x = nambers(0)
# y = numbers(1)
# y = numbers(2)

x, y, z = numbers
x, _, _ = numbers
print(z)
print(x)

x, *a = numbers

print("")
print(x)
print(a)
10. Dictionary
```

![image](https://user-images.githubusercontent.com/93015185/140930600-e80ce7ab-cc35-492d-9008-8802f0b6cbcf.png)

8. Dictionary

```y
user = {
    "nama": "fahroji", "age": 19, "is_admin" :True 
}

user["username"] = "fahroji_oji"
user["nama"] = "fahroji_ji"

#temp = user.get("username", "oji")
#nama = user["nama"]

temp = user.get("nama")

print("")
print(temp)
```
![image](https://user-images.githubusercontent.com/93015185/140930926-ca9dbd9c-b08b-4337-ae5a-8869e2daf2f0.png)
