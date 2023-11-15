from time import sleep
class Cachorro:

    def __init__(self, raca, tamanho, cor):
        self.raca = raca
        self.tamanho = tamanho
        self.cor = cor

    def Latir(self):
        print('Começou a latir', end=', ')


    def Comer(self):
        print('Está correndo agora', end=', ')


    def Correr(self):
        print('começou a correr', end=', ')

    def TipoCachorro(self):
        print(f'O {self.raca} {self.cor}', end=' ==> ')


    def Descansar(self):
        print('Agora decidiu descansar', end='! ')


cachorro1 = Cachorro('Pitbull', '50', 'Marrom')

cachorro1.TipoCachorro()
sleep(1)
cachorro1.Latir()
sleep(1)
cachorro1.Comer()
sleep(1)
cachorro1.Correr()
sleep(1)
cachorro1.Descansar()