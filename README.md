import os

def ochish():
    h = r"D:\Men_bekorchiman" 
    if not os.path.exists(h):
        os.makedirs(h)
        print(f"Papka {h} yaratildi.")
    else:
        print(f"Papka {h} allaqachon bor.")

ochish()
