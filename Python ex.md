## Vou deixar um exemplo do que posso fazer no **Python** e logo logo farei mais projetos em JS, React, etc. O **mundo** é uma criança!


    class error(Exception):
        pass

    class input_error(error):
        def __init__(self, message):
            self.message = message
    while True:
        try:
            x = input("Escreva a palavra DIO: ")
            if x=="DIO":
                print("GIO sera o mais novo colaborador da EDUZZ!!!")
            elif x!="DIO":
                raise input_error("Voce nao digitou DIO!")
            break
        except ValueError:
            print("Invalido. Digite apenas DIO!")
        except input_error as ex:
            print(ex)


[Copie e cole o codigo acima no link a seguir!!!](https://www.programiz.com/python-programming/online-compiler/)
