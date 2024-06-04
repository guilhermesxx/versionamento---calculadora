class calculadora:
    def __init__(self) -> None:
        pass

    def adicionar(self, a , b):
        return a + b
    
    def subtrair(self , a , b):
        return a - b 
    
    def multiplicar(self , a , b):
        return a * b
    
    def dividir(self , a , b):
        if b == 0:
            return "erro: Divisão por zero!"
        return a / b
    
calc = calculadora()
print("Adição: 10 + 5 =", calc.adicionar(10, 5))
print("Subtração: 20 - 6 = ", calc.subtrair(20 , 6))
print("Multiplicação: 10 * 8 =", calc.multiplicar(10, 8))
print("Divisão: 10 / 5 =", calc.dividir(10, 5))
print("Divisão: 10 / 0 =", calc.dividir(10, 0))
