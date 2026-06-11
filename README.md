"""Elabore um script que dado alguma coisa no input, devolva como output:"""
texto = input("digite algo:")
# tipo primitivo;
print(type(texto))

#É um número?
print(f"É um número? {texto.isnumeric()}")

#É alfanumérico?

print(f"É alfanumerico? {texto.isalnum()}")

#É alfabético?
print(f"É alfabetico? {texto.isalpha()}")

#Está em maiúsculas?
print(f"É maiusculas? {texto.isupper()}")

#Está em minúsculas?
print(f"Éstar minuscula? {texto.islower()}")

#Está capitalizada?
print(f"estar em capitalizada? {texto.istitle()}")
