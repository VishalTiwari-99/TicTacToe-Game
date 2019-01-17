import os
def cls():
	os.system("CLS")
def display_board(board):
	cls()
	print('  |   |  ')
	print(str(board[7])+' | '+str(board[8])+' | '+str(board[9]))
	print('  |   |  ')
	print('---------')
	print('  |   |  ')
	print(str(board[4])+' | '+str(board[5])+' | '+str(board[6]))
	print('  |   |  ')
	print('---------')
	print('  |   |  ')
	print(str(board[1])+' | '+str(board[2])+' | '+str(board[3]))
	print('  |   |  ')
def player_input():
	global player1,player2
	while True:
		a=input('PLAYER 1 , What you want to take ? (X/O) :  ')	
		if a=='X' or a=='x' :
			player1 = 'X'
			player2 = 'O'
			print('PLAYER 1 :',player1)
			print('PLAYER 2 :',player2)
			break
		elif a=='O' or a=='o' :
			player1 = 'O'
			player2 = 'X'
			print('PLAYER 1 :',player1)
			print('PLAYER 2 :',player2)
			break
		else:
			print("You Entered Wrong !!!! \nPlease Enter Again, a valid Character among 'O' and 'X' only. ")
			continue
def chk():
	if board[1]==player1 and board[4]==player1 and board[7]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[2]==player1 and board[5]==player1 and board[8]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[3]==player1 and board[6]==player1 and board[9]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[1]==player1 and board[2]==player1 and board[3]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[4]==player1 and board[5]==player1 and board[6]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[7]==player1 and board[8]==player1 and board[9]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[1]==player1 and board[5]==player1 and board[9]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[3]==player1 and board[5]==player1 and board[7]==player1:
		print('Player 1 won and game ends here.')
		return 'END'
		
	elif board[1]==player2 and board[4]==player2 and board[7]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[2]==player2 and board[5]==player2 and board[8]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[3]==player2 and board[6]==player2 and board[9]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[1]==player2 and board[2]==player2 and board[3]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[4]==player2 and board[5]==player2 and board[6]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[7]==player2 and board[8]==player2 and board[9]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[1]==player2 and board[5]==player2 and board[9]==player2:
		print('Player 2 won and game ends here.')
		return 'END'
		
	elif board[3]==player2 and board[5]==player2 and board[7]==player2:
		print('Player 2 won and game ends here.')
		return 'END'

	elif (board[1]=='X' or board[1]=='O') and (board[2]=='X' or board[2]=='O') and (board[3]=='X' or board[3]=='O') and (board[4]=='X' or board[4]=='O') and (board[5]=='X' or board[5]=='O') and (board[6]=='X' or board[6]=='O') and (board[7]=='X' or board[7]=='O') and (board[8]=='X' or board[8]=='O') and (board[9]=='X' or board[9]=='O'):
		print("Opps !!!!!\nGAME TIED HERE.")
		return 'END' 	
		
														
def play():
	global board,player1,player2
	print('RULE : Input the number on the board at your turn where you want to mark .\n       PLAYER 1 will play first followed by PLAYER 2 . Game will continue till a player win or Tie at last.')
	while True:
		while True:
			b=int(input('PLAYER 1 : '))
			if board[b]=='O' or board[b]=='X':
				print("This Index is already occupied !!!\nTry Again in different Index. ")
				continue
			else:
				break	
		board[b]=player1
		display_board(board)
		c=chk()
		if c=='END':
			break
		while True:	
			d=int(input('PLAYER 2 : '))
			if board[d]=='O' or board[d]=='X':
				print("This Index is already occupied !!!\nTry Again in different Index. ")
				continue
			else:
				break	
		board[d]=player2
		display_board(board)
		e=chk()
		if e=='END':
			break
board=[0,1,2,3,4,5,6,7,8,9]
display_board(board)
player_input()
play()			


	 



	



