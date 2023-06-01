import tkinter as tk

# Création de la fenêtre principale
fenetre = tk.Tk()
fenetre.title("Ma Super App")
fenetre.geometry("800x600")

# Ajouter du contenu à la fenêtre
label = tk.Label(fenetre, text="Bienvenue sur Ma Super App !")
label.pack()

bouton = tk.Button(fenetre, text="Cliquez-moi !")
bouton.pack()

# Lancement de la boucle principale
fenetre.mainloop()
