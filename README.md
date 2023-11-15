operarios = ["1"]
dicc = {"1": "hola"}
print("ingrese nombre de operario:")
nombre = input()
op = dicc.get(nombre)
x = 0
while x < 3:
    print("ingrese password:")
    psw = input()
    if psw == op:
        print("pass correcta")
        x = 3
    else:
        print("pass incorrecta")
        norden = ["1"]
        dicc = {"1": "12345678"}
        print("ingrese numero orden")
        numero = input()

        print("seguimos mostrando")

        print("ingrese solo datos de la fecha")
        var1 = int(input("ingrese el dia"))
        var2 = int(input("ingrese mes"))
        var3 = int(input("ingrese año"))
        print(f"la fecha que ingresaste es:", var1, "delmes", var2, "delaño", var3)

        print("ingrese solo datos del kilometraje")
        var1 = int(input("ingrese el km"))
        print(f"el kilometraje es{var1}")
        print("el kilometraje que ingresaste es:", var1)

        print("ingrese solo datos de litros petroleo consumido")
        var1 = int(input("ingrese litros consumido petroleo"))
        print(f"litros de petroleo consumido es{var1}")
        print("litros de petroleo que ingresaste es:", var1)

        i_ruta = {}
        continuar = True
        while continuar:
            print("vamos a anotar hora de inicio i_ruta")
            clave = input("ingresa la ruta")
            valor = int(input("ingresa la hora"))
            i_ruta[clave] = valor
            print(i_ruta)
            continuar = input("quieres ingresar otra ruta SI o NO") == "SI"
        print("la hora de inicio fue")
        print(i_ruta)

        f_ruta = {}
        continuar = True
        while continuar:
            print("vamos a anotar hora final de f_ruta")
            clave = input("ingrese la ruta")
            valor = int(input("ingrese la hora"))
            f_ruta[clave] = valor
            print(f_ruta)
            continuar = input("quieres ingresar otra ruta SI o NO") == "SI"
        print("la hora final fue")
        print(f_ruta)

        print("datos ingresados listos, ahora volveremos al menu principal")

        supervisores = ["1"]
        dicc = {"1": "rojo"}
        print("ingrese nombre de supervisor")
        nombre = input()
        op = dicc.get(nombre)
        y = 0
        while y < 3:
            print("ingrese pasword:")
            psw = input()
            if psw == op:
                print("pass correcta")
                y = 3
            else:
                print("pass incorrecta")
                y = y + 1
                if y == 3:
                    break
        print("seguimos avanzado")
        print("clave correcta mostar datos")

        print("ingrese total kilometraje")
        var1 = int(input("ingrese el total km"))
        print(f"el kilometraje total es {var1}")
        print("el kilometraje total ingresado es:", var1)

        print("avanzamos, ya se mostro el total de pertroleo consumido")

        print("ingrese el total de litros petroleo")
        var1 = int(input("ingrse el total litros petroleo"))
        print(f"litros totales ingreasdos es:", var1)

        print("avanzamos, ya se mostro el total de petroleo consumido")

        print("ingrese el total de hora inicio")
        var1 = int(input("ingrese total de horas inicio"))
        print(f"horas inicio totales ingresadas son:", var1)

        print("ingrese el total hora final")
        var1 = int(input("ingrese total de hora final"))
        print(f"horas final totales ingresadas son", var1)

        print("avanzamos, horas totales iniciales y finales listas")

        print("menu principal operario")

        lista = ["fecha", "kilometraje", "petroleo", "inico r", "fin r"]
        dicc = {lista[0]: "11_11_2023", lista[1]: "600", lista[2]: "69", lista[3]: "12", lista[4]: "20"}
        print(operarios)
        print(dicc)

        print("fin del codigo")
        x = x + 1
        if x == 3:
            break
print("seguimos avanzado")
print("clave correcta, mostrar datos")

