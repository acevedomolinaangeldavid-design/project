def lapiz(canvas, x0, y0, x1, y1, color, grosor):
    canvas.create_line(x0, y0, x1, y1, fill=color, width=grosor,
                       capstyle="round")


def borrador(canvas, x0, y0, x1, y1, color_fondo, grosor):
    lapiz(canvas, x0, y0, x1, y1, color_fondo, grosor * 3)


def figura(canvas, tipo, x0, y0, x1, y1, color, grosor):
    if tipo == "rectangulo":
        return canvas.create_rectangle(x0, y0, x1, y1, outline=color, width=grosor)
    return canvas.create_oval(x0, y0, x1, y1, outline=color, width=grosor)
