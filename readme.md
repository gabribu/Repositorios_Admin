#!/usr/bin/python3

#Te ayuda a calcular tu rfc

print("******ESCRIBE CON MAYUSCULAS :)********")
x=""
v =  ["a","e","i","o","u","A","E","I","O","U"]
n = input("Ingresa tu nombre(s):")
a = input("Ingresa tu apellido PATERNO: ")
am = input("Ingresa tu apellido MATERNO: ")
f = input("Ingresa tu fecha de nacimiento de la forma AA/MM/DD, SIN ESPACIOS: ")

for x in a:
    if x in v and a.index(x) != 0:
        rfc2=(a[0])+(x)+(am[0])+(n[0])+(f)
        break
print (rfc2)





