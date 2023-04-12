# Nims_game_Tomass_minimax
def reset_game():     global serkocini     serkocini = 12     serkocinu_daudz.config(text="Sērkociņu daudzumus: " + str(serkocini))     gajiens.config(text="Veic gājienu")     ievade.config(state="normal")     rest_poga.config(state='disabled')     computer_first()  # call computer_first() to start a new game with the computer going first
