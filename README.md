

nome=input("Digite o nome: ") <br>
idade=int(input("Digite a idade: ")) <br>
doenca_infectocontagiosa=input("Suspeita de doença infectocontagiosa? ").upper() <br>


if doenca_infectocontagiosa=="SIM":
    print("Encaminhe o paciente para sala AMARELA") <br>
elif doenca_infectocontagiosa=="NAO":
    print("Encaminhe o paciente para sala BRANCA") <br>
else:
    print("Responda a suspeita de doença infectocontagiosa com SIM ou NAO")


if idade >= 65:
    print("Paciente COM prioridade") <br>
else:
    genero=input("Digite o gênero do paciente: ").upper() <br>
    if genero=="FEMININO" and idade>10:
        gravidez=input("A paciente está grávida? ").upper() <br>
        if gravidez=="SIM":
            print("Paciente COM prioridade") <br>
        else:
            print("Paciente SEM prioridade") <br>
    else:
        print("Paciente SEM prioridade") <br>
