-import tkinter as tk

# Create the main window
root = tk.Tk()
root.title("Change Color Example")

# Create a canvas
canvas = tk.Canvas(root, width=400, height=400)
canvas.pack()

# Create a rectangle
rectangle = canvas.create_rectangle(50, 50, 200, 200, fill="blue")

# Function to change the color of the rectangle
def change_color():
    canvas.itemconfig(rectangle, fill="red")

# Button to trigger the color change
button = tk.Button(root, text="Change Color", command=change_color)
button.pack()

# Run the application
root.mainloop()

-
-
-
-
- My name is @FatalFS
- I’m interested in Coding, Python, and coding in general.
- I’m currently in Cybersecurity.
- I’m looking to collaborate on nothing at the moment

<!---
FatalFS/FatalFS is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
