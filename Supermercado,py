def supermercado():
           n 
n=int(input("n: "))
productos=int(input('Ingrese la cantidad de productos:'))
listaProd=[]
for i in range(productos):
            prod=int(input(f'Precio producto {i+1}: '))
            listaProd.append(prod)
            desc=0.2
            total=0
            descuento=0
            j=i
            for i in listaProd:
                if j<= n and desc !=0:
                    j+=1
                elif desc> 0.05:
                    desc /=2
                else:
                    desc=0
                    j=2
                descuento +=i*desc
                total +=i
            print(f'Total:{total}')
            print(f'Descuneto: {descuento}')
            print('Por pagar:',total-descuento)
            supermercado()
