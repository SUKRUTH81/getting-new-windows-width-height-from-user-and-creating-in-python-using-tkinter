# getting-new-windows-width-height-from-user-and-creating-in-python-using-tkinter

from tkinter import *
root = Tk()
w=int(input("enter the height length : "))
h=int(input("enter the breadth length : "))
root.geometry(("%dx%d" % (w,h)))
btn = Button(root, text = 'Click me !', bd = '2',
command = root.destroy)
btn.pack(side = 'top')
root.mainloop()
