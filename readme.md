## Tkinter frame and canvas

#### Create frame container in window
```python
import tkinter as tk

# Declare window object
window = tk.Tk()

# Window size
window.geometry("300x300")

# Window title
window.title("Hello World")

# Declare frame object in window object
frame = tk.Frame(window, width=200, height=200, background="orange")

# Display frame object
frame.pack()

# Build window object
window.mainloop()

```

##### Example

<img src="frame.png">

#### Create canvas in frame container
```python
import tkinter as tk

# Declare window object
window = tk.Tk()

# Window size
window.geometry("300x300")

# Window title
window.title("Hello World")

# Declare frame object in window object
frame = tk.Frame(window, width=300, height=300)
# Display frame object
frame.pack()

# Declare canvas object in frame object
canvas = tk.Canvas(frame, width=300, height=300, background="blue")
# Display canvas object
canvas.pack()

# Build window object
window.mainloop()
```

##### Example

<img src="canvas.png">