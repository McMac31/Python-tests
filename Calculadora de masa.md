simbolo= input("Teclea k si quieres pasar kilos a libras/ teclea l si quieres pasar de libras a kilos ")
if simbolo == "k":
    k= float(input("ingresa los kilogramos"))
    print(f"Su resultado en libras es {k*2.2046}")
elif simbolo == "l":
    l= float(input("Ingresa las libras"))
    print(f"Su resultado en kilogramos es{l/2.2046}")
else:
    print("Ingrese una letra valida")
