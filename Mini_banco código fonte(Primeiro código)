print('===============================================SEU BANCO===============================================')
nome = input('\nQual o seu nome?: ')
N_200 = int(input(f'\nOlá {nome}, seja bem-vindo ao banco. Me informe quantas notas de R$200,00 você deseja depositar: '))
N_100 = int(input('Notas de R$100,00: '))
N_50 = int(input('Notas de R$50,00: '))
N_20 = int(input('Notas de R$20,00: '))
N_10 = int(input('Notas de R$10,00: '))
N_5 = int(input('Notas de R$5,00: '))
N_2 = int(input('Notas de R$2,00: '))

total = (
    N_200 * 200 +
    N_100 * 100 +
    N_50 * 50 +
    N_20 * 20 +
    N_10 * 10 +
    N_5 * 5 +
    N_2 * 2
)

while True:
    print('\nEscolha uma das opções abaixo:')
    print('1 - Consultar saldo')
    print('2 - Saques')
    print('3 - Transferências')
    print('4 - Sair')

    opcao = int(input('\nDigite a opção escolhida: '))

    if opcao == 1:
        print(f'\n{nome}, seu saldo é de: R${total:.2f}')
    elif opcao == 2:
        valor_saque = float(input(f'\nQual o valor que deseja sacar {nome}? Seu saldo: R${total:.2f}: '))
        if valor_saque <= total:
            total -= valor_saque
            print(f'Saque realizado no valor de R${valor_saque:.2f}! Seu saldo restante é: R${total:.2f}')
        else:
            print('Saldo insuficiente para saque.')
    elif opcao == 3:
        transferencia = float(input(f'\nQual o valor que deseja transferir {nome}? Seu saldo: R${total:.2f}: '))
        if transferencia <= total:
            total -= transferencia
            print(f'Transferência realizada! Seu saldo restante é: R${total:.2f}')
        else:
            print('Saldo insuficiente para transferência.')
    elif opcao == 4:
        print(f'\nSaindo... Obrigado por utilizar nossos serviços {nome}!')
        break
    else:
        print('\nOpção inválida.')

    print('\nDigite 5 para voltar ao menu principal ou qualquer outra tecla para encerrar.')
    voltar = input('Sua escolha: ')
    if voltar != '5':
        print(f'\nSaindo... Obrigado por utilizar nossos serviços {nome}!')
        break
