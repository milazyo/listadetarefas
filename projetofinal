lista_de_tarefas = []
continuar = True

while continuar:
    print("escolha uma opção:\n" 
        "1 - Inserir nova taraefa\n" 
        "2 - Listar\n"      
        "3 - Sair"
         )
    opcao = input('insira o que deseja fazer: ')
    
    if opcao == "1":
        print("\n")
        tarefa = input('insira uma nova tarefa: ')
        lista_de_tarefas.append(tarefa)
    elif opcao == "2":
        print("\nlista de tarefas:")
        for tarefa in lista_de_tarefas:
          print(f"-{tarefa}")
    elif opcao == "3": 
        continuar = False
    else:
        print("Opção inválida! Por favor, tente novamente.")
    print('\n')
