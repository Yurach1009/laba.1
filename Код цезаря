alphabet = "ABCDEFGHIJKLMNOPQRSUVWXYZABCDEFGHIJKLMNOPQRSUVWXYZabcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzабвгґдеєжзиіїйклмнопрстуфхцчшщьюяАБВГҐДЕЄЖЗИІЇЙКЛМНОПРСТУФХЦЧШЩЬЮЯ012345678901234567890"
encrypt = input("Введіть текст:")
key = int(input("Ключ:"))
encrypted = ""
for letter in encrypt:
    position = alphabet.find(letter)
    newPosition = position + key
    if letter in alphabet:
        encrypted = encrypted + alphabet[newPosition]
    else:
        encrypted = encrypted + letter
print(encrypted)
