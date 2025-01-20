class CuentaBancaria:
    def __init__(self, titular, saldo_inicial=0):
        """
        Constructor de la clase CuentaBancaria.

        Args:
            titular: Nombre del titular de la cuenta.
            saldo_inicial: Saldo inicial de la cuenta.
        """
        self.titular = titular
        self.saldo = saldo_inicial
        print(f"Se ha creado una cuenta para {self.titular} con un saldo inicial de {self.saldo}")

    def __del__(self):
        print(f"La cuenta de {self.titular} ha sido cerrada.")

# Creación de objetos
cuenta1 = CuentaBancaria("Juan Pérez", 1000)
cuenta2 = CuentaBancaria("María López")

# Salida:
# Se ha creado una cuenta para Juan Pérez con un saldo inicial de 1000
# Se ha creado una cuenta para María López con un saldo inicial de 0
