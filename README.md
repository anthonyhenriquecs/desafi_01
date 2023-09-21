# desafi_01
'''T = input("Digite seu TW: ")

if len(T) <= 140:
    print("TWEET")
else:
    print("MUTE")
print(T)


def verifica_tamanho_tweet(texto):
    if len(texto) <= 140:
        return "TWEET"
    else:
        return "MUTE"

# Teste
texto = input().strip()
print(verifica_tamanho_tweet(texto))
'''

def mes_por_extenso(numero):
    meses = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
    
    # O índice da lista começa em 0, então subtraímos 1 do número fornecido
    return meses[numero-1]

# Entrada
numero = int(input())

# Verificar se o número está no intervalo correto
if 1 <= numero <= 12:
    print(mes_por_extenso(numero))
else:
    print("Número fora do intervalo!")
