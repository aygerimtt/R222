# R222
from tkinter import *


class Main(Frame):
    def __init__(self, root):
        superman(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logic(self, operation):
        pass

    def update():
       pass


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("485x250+300+200")
    root.title("Калькулятор")
    root.resizable(False, False)
    app = Main(root)
    app.pack()
    root.mainloop()

Отлично, идём дальше.


Делаем кнопочки

В методе build создаём такой список:


btns = [
            "C", "DEL", "*", "=",
            "1", "2", "3", "/",
            "4", "5", "6", "+",
            "7", "8", "9", "-",
            "+/-", "0", "%", "X^2"
        ]
