import hospital


pacientes = []
opcao = 0
while
print("1 - cadastra paciente")
print("2 - consulta paciente")
print("3 - atendimento paciente")
print("4 - sair")
opcao = int(input("Informe uma opção"))

if opcao == 1:
    cadastra paciente(paciente)
elif opcao == 2:
    status = int(input("Informe o status: "))
   hospital.consulta_paciente("status, pacientes")
elif opcao == 3:
    Pos = hospital.recupera_paciente(pacientes)
    print("nome" pacientes [pos])
    print("pressao ", pacientes[pos+4])
    print("temperatura: ", pacientes[pos+5])
    novo_status = int(input("Resultado atendimento: "))
    pacientes[pos+6] = novo_status

    print("Sistema finalizado!")
