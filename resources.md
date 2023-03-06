_Made by_ [@David Adarme](https://www.github.com/davidadarme)

**Links**
- [Drive de @EstebanJaniot](https://soysena-my.sharepoint.com/:f:/g/personal/david_adarme_soy_sena_edu_co/EgXGuvrcRI1Psid60hALD0sBy0tjccP9RTa-JeTuOWfzpg?e=VOtEgJ) 
- [Tutorías SENA virtual by](https://www.youtube.com/playlist?list=PLUzHPkQscM7LlaUa4qEd9sILxfghSo0jC) por [@EstebanJaniot](https://github.com/SrJaniot)
- [Google Drive de lenguajes de programacion](https://soysena-my.sharepoint.com/:f:/g/personal/david_adarme_soy_sena_edu_co/ErD0kyDwKrZOh3R2h70ASbMBDPogwrBYHp5MOw4DKH8h1w?e=4iPFLW)
- [BOOTCAMP SANTANDER 2022](https://soysena-my.sharepoint.com/:f:/g/personal/david_adarme_soy_sena_edu_co/EtGDeu0AKyBHsCBle2_DhD0Bk-sfszaI1cXrI4dIczmIoQ?e=K4PqC1)



---
# Contenido 
_Da click en los siguientes enlaces para redigirir al contenido que deseas_
1. [Libros PDF](#libros-pdf)
2. [Ejercicios](#ejercicios)
    - [Python](#ejercicios-python)
    - [C++](#c)
4. [Javascript](#javascript)
5. [Drive](#drive)

## Libros PDF
- [Manual - LPP](https://soysena-my.sharepoint.com/:b:/g/personal/david_adarme_soy_sena_edu_co/ESsmRoUOStdHu9fLgvwZgL8BfaaKQ5vbw0y8O7orgKvYLg?e=WO7dw6)
- [El gran libro de HTML5, CSS3 y Javascript](https://soysena-my.sharepoint.com/:b:/g/personal/david_adarme_soy_sena_edu_co/EdqLRFjP819KvvOl_N2I3AoB8iD7x7cytWY96HgNB_ygAQ?e=i4xtG0)
- [Node.JS - JavaScript en el lado del servidor - Manual práctico avanzado](https://soysena-my.sharepoint.com/:b:/g/personal/david_adarme_soy_sena_edu_co/ER-gLEcgDhNPt7qdEl2ZDakBqo0KZem5d8lvyUSa7x-G0g?e=JTujSn)


- [Algoritmos Basicos 2023.docx](https://soysena-my.sharepoint.com/:w:/g/personal/david_adarme_soy_sena_edu_co/EXNkY3nLFVNBiSn6sEEnfkkBmx4bsVawNH4sA2nIuTIQXw?e=YCiPDb)




# Ejercicios

## Ejercicios Python
**For Loop.py**
``` python
Una persona debe realizar un muestreo con 50 personas para determinar el promedio de peso de los niños, jovenes, adultos y viejos que existen en su zona habitacional. Se determinan las categorias con base en la siguiente tabla:

categoria:      edad:

niños           0-12
jovenes         13-29
adultos         30-59
viejos          60->
'''
pesoni=0
pesoj=0
pesoa=0
pesov=0
edadniños=0
edadjoven=0
edadadulto=0
edadviejo=0

for i in range(5):
    numero=int(input("Ingrese la edad: "))
    peso=int(input("Ingrese el peso: "))

    if numero<13:
        print("Es niño")
        pesoni=pesoni+peso
        edadniños=edadniños+1
    elif 12<numero<30:
        print("Es un joven")
        pesoj=pesoj+peso
        edadjoven=edadjoven+1
    elif 29<numero<60:
        print("Es un adulto")    
        pesoa=pesoa+peso
        edadadulto=edadadulto+1
    else :
        print("Es un viejo")
        pesov=pesov+peso
        edadviejo=edadviejo+1
promedioniñospeso=pesoni/edadniños
promediojovenpeso=pesoj/edadjoven
promedioadultopeso=pesoa/edadadulto
promedioviejopeso=pesov/edadviejo

print("Promedio niños: ", promedioniñospeso)
print("Promedio niños: ", promediojovenpeso)
print("Promedio niños: ", promedioadultopeso)
print("Promedio niños: ", promedioviejopeso)
```

**Ejercicio While Loop.py**
```python
#numero_De_Personas=int(input("Digite el numero de personas a las que quiere entrevistar"))
numero_De_Personas=0
pesototalniños=0
NiñosTotales=0
pesototaljovenes=0
JovenesTotales=0
pesototalAdulto=0
AdultosTotales=0
pesototalViejos=0
ViejosTotales=0

n=int(input("Max"))
while numero_De_Personas<n:
    edad=int(input("Digite su edad"))
    peso=float(input("Digite su peso"))

    if edad>=0 and edad<=12:
        pesototalniños=pesototalniños+peso
        NiñosTotales=NiñosTotales+1
    elif edad>=13 and edad<=29:
        pesototaljovenes=pesototaljovenes+peso
        JovenesTotales=JovenesTotales+1
    elif edad>=30 and edad<=59:
        pesototalAdulto=pesototalAdulto+peso
        AdultosTotales=AdultosTotales+1
    elif edad>=60 and edad<=200:
        pesototalViejos=pesototalViejos+peso
        ViejosTotales=ViejosTotales+1
    else:
        print ("error")
        n=n+1

    numero_De_Personas=numero_De_Personas+1

if NiñosTotales!=0:
    ResultadoPromedioNiños=pesototalniños/NiñosTotales
    print("El promedio del peso de los niños es ",ResultadoPromedioNiños )
    
if JovenesTotales!=0:
    ResultadoPromedioJovenes=pesototaljovenes/JovenesTotales
    print("El promedio del peso de los jovenes es ",ResultadoPromedioJovenes )
if AdultosTotales!=0:
    ResultadoPromedioAdultos=pesototalAdulto/AdultosTotales
    print("El promedio del peso de los adultos es ",ResultadoPromedioAdultos )
if ViejosTotales!=0:
    ResultadoPromedioViejos=pesototalViejos/ViejosTotales
    print("El promedio del peso de los viejos es ",ResultadoPromedioViejos )
```




## C++
- [EJERCICIOS PROPUESTOS VECTORES Y MATRICES](https://soysena-my.sharepoint.com/:w:/g/personal/david_adarme_soy_sena_edu_co/EQufuYeE1LhAvcC1NTVX7w8BWARSPx-5h_MUSiaBPVavHg?e=xVQV2Z)
- [EJERCICIOS PROP. EST DE CONTROL](https://soysena-my.sharepoint.com/:w:/g/personal/david_adarme_soy_sena_edu_co/EaO8Kkvb_f5Pt2hESbdKHoABuqTN5VzTUgN_oIsfRJoZGg?e=k955Hn)
- 


``` c++
//programa C++ que:
//⦁	Lea los n elementos de un vector numericos . (Los //elementos deben leerse de manera ordenada).
#include <iostream>
using namespace std;
void ordenarVector(int A['x'], int n) {
    int temp;
    for (int i = 0; i <= n - 2; i = i + 1)
    {

        for (int j = i + 1; j <= n - 1; j = j + 1)
        {
            if (A[j] < A[i])
            {
                temp = A[i];
                A[i] = A[j];
                A[j] = temp;
            }
        }
    } 
}
void MostrarVector(int A['x'], int n) {
    for (int i = 0; i < n; i = i + 1) {
        cout << "A[" << i << "]   " << A[i] << "   ";
    }
}
void llenarVector(int A['x'], int &n) {
    cout << "digite el tamaño del Vector/Lista:   ";
    cin >> n;

    for (int i = 0; i < n; i = i + 1) {
        cout << "A[" << i << "]   ";
        cin >> A[i];
    }

}

int main()
{
    int A['x'],n;
    llenarVector(A, n);
    ordenarVector(A, n);
    MostrarVector (A, n);
    
}

```
**ejercicio de distancia entre palabra.py**
```
palabra_1=str(input("ingrese una primera palabra "))
palabra_2=str(input("ingrese una segunda palabra para comparar "))
posicion_letras_palabra1=[]
posicion_letras_palabra2=[]
diferencia_entre_letras=[]
abcdario=["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z"]

def encotrar_y_guardar_posicion(palabra_1,posicion_letras_palabra1,):
    
    for x in palabra_1 :
        contador=int(0)
        for i in range(len(abcdario)):
            if x !=abcdario[i]:
                contador +=1
            else:
                contador+=1
                
                break
        posicion_letras_palabra1.append(contador)
        print(contador,posicion_letras_palabra1)

encotrar_y_guardar_posicion(palabra_1,posicion_letras_palabra1)
encotrar_y_guardar_posicion(palabra_2,posicion_letras_palabra2)

if len(palabra_1) == len(palabra_2):
    diferencia=int()
    suma=int()
    for x in range(len(palabra_1)):
        
        diferencia=posicion_letras_palabra1[x]-posicion_letras_palabra2[x]
        diferencia_entre_letras.append(diferencia)
        suma+=diferencia_entre_letras[x]
elif len(palabra_1)>len(palabra_2):
    diferencia=int()
    suma=int()
    for x in range(len(palabra_1)):
        
        diferencia=posicion_letras_palabra1[x]-posicion_letras_palabra2[x]
        diferencia_entre_letras.append(diferencia)
        suma+=diferencia_entre_letras[x]
print(diferencia_entre_letras,suma)
print(posicion_letras_palabra1,posicion_letras_palabra2)
```


### Javascript
[JavaScript for Starters: The Complete Guide](https://mdjunaidap.notion.site/JavaScript-for-Starters-The-Complete-Guide-91f76c8ed85d4bd7afc1f2a63216d303)
https://es.javascript.info/
Angular: [Angular desde 0 (Framework)](https://www.youtube.com/playlist?list=PL2PZw96yQChzdtHpeKao7Lz3JkS4s6HLz)
