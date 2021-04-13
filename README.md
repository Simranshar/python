# python
# Paper,scissors  ,stone game
player1 = input("player1 give your move")
Player2 = input("player2 give your move")
if player1 =="rock" and player2 ==" scissors":
print("player1 wins")
elif player1 =="paper" and player2 =="rock":
print("player1 wins")
elif player1 == player2:
print("game is tie")
else:
print("player2 wins")
