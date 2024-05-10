from tkinter import *
from time import *

class MyFrame(Frame):
    def __init__(self):
        Frame.__init__(self)

        self.myCanvas = Canvas(width=800, height=800, bg="dark blue")
        self.myCanvas.grid()
        self.myCanvas.create_rectangle(0, 700, 800, 800, fill="dark green")

        #Background moon 
        self.myCanvas.create_oval(600, 40, 750, 180, fill="light gray")
        self.myCanvas.create_oval(700, 70, 720, 90)
        self.myCanvas.create_oval(680, 90, 690, 100)

        #Background star
        self.myCanvas.create_oval(500, 50, 502, 52, fill="white", outline="white")
        self.myCanvas.create_oval(570, 270, 572, 272, fill="white", outline="white")
        self.myCanvas.create_oval(30, 110, 32, 112, fill="white", outline="white")
        self.myCanvas.create_oval(300, 40, 302, 42, fill="white", outline="white")
        self.myCanvas.create_oval(750, 250, 752, 252, fill="white", outline="white")
        self.myCanvas.create_oval(250, 150, 252, 152, fill="white", outline="white")
        self.myCanvas.create_oval(180, 24, 182, 24, fill="white", outline="white")
        self.myCanvas.create_oval(400, 198, 402, 198, fill="white", outline="white")
        self.myCanvas.create_oval(70, 270, 72, 272, fill="white", outline="white")


        star = self.myCanvas.create_polygon(0, 0, 0, 0, 0, 0, 0, 0, fill="white",
                                     outline="white")
        for count in range(190): 
            increment = 10*count
            self.myCanvas.coords(star, 10 + increment, 10 + increment,
                             10 + increment, 10 + increment)
            self.myCanvas.create_rectangle(0, 700, 800, 800, fill="dark green")


            self.myCanvas.update()
            sleep(.020)




frame02 = MyFrame()
frame02.mainloop()
