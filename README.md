# stone-paper-scissor
import random
def func():
    ch=''

    while ch!='no':
         l=random.randint(1,4)
         if l==1:
            x='stone'
         elif l==2:
            x='paper'
         elif l==3:
            x='scissor'
         m=input('enter the choice:')
         if m==x:
            print('tie')
         elif m=='paper' and x=='stone':
                print('you win')
         elif m=='paper' and x=='scissor':
                print('you lose')
         elif m=='stone' and x=='paper':
                print('you lose')
         elif m=='stone' and x=='scissor':
                print('you win')
         elif m=='scissor' and x=='stone':
                print('you lose')
         elif m=='scissor' and x=='paper':
                print('you win')
         ch=input('do you want to continue')
        
func()

