print('Welcome to my computer quiz')


playing=input('Do you want to play?').lower()
if playing!='yes':
    quit()
    
print("OK Let's play!")
answer=input('What does CPU stands for?').lower()
if answer=="central processing unit":
    print('Correct!')
else:
        print('Incorrect!')  


answer=input('What does API stands for?').lower()
if answer=='application programming interface':
    print('Correct!')
else:
        print('Incorrect!')  


answer=input('What does VPN stands for?').lower()
if answer=='virtual private network':
    print('Correct!')
else:
        print('Incorrect!')  


answer=input('What does SQL stands for?').lower()
if answer=='structured query language':
    print('Correct!')
else:
        print('Incorrect!')  


answer=input('What does RAM stands for?').lower()
if answer=='random access memory':
    print('Correct!')
else:
        print('Incorrect!')  
