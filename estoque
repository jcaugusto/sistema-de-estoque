produto = input('qual o produto?')
categoria = input('qual a categoria do produto?')
qtde = input('qual a quantidade atual do produto?')

if produto and categoria and qtde:
    qtde = int(qtde)
    if categoria == 'bebidas':
        if qtde < 75:
            print('solicitar {} á equipe de compras,temos apenas {} unidade de estoque'.format(produto, qtde))
    elif categoria == 'limpeza':
        if qtde < 30:
            print('solicitar {} á equipe de compras,temos apenas {} unidade de estoque'.format(produto, qtde))
    else:
        if qtde < 50:
            print('solicitar {} á equipe de compras,temos apenas {} unidade de estoque'.format(produto, qtde))

else:
    print('preencha todas as informações')