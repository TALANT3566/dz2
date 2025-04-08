#import pygame as pg
#pg.init()

#width, height = 800, 600
#screen = pg.display.set_mode((width, height))

#while True:
    #for event in pg.event.get():
        #if event.type == pg.QUIT:
            #break
            #exit()
    
    #screen.fill((100, 0, 100))
    #pg.draw.rect(screen, (255,255,255), (100, 100, 200, 200), 10, 20)
    #pg.draw.rect(screen, (255,255,255), (500, 100, 200, 200), 10, 20)
    #pg.draw.circle(screen, (0,0,0), (180, 150), 30, 0)
    #pg.draw.circle(screen, (0,0,0), (600, 150), 30, 0)
    #pg.draw.line(screen, (255,255,255), (0, 400), (500, 400), 5)

    #pg.display.update()







import tkinter as tk

def create_chess_board(canvas):
    square_size = 62 
    colors = ['white', 'black'] 

    for row in range(8):
        for col in range(8):
            color = colors[(row + col) % 2] 
            x1 = col * square_size
            y1 = row * square_size
            x2 = x1 + square_size
            y2 = y1 + square_size
            canvas.create_rectangle(x1, y1, x2, y2, fill=color)


root = tk.Tk()
root.title("Шахматная доска")
root.geometry("500x500")  

canvas = tk.Canvas(root, width=500, height=500)
canvas.pack()

create_chess_board(canvas)

root.mainloop()
