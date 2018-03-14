print ("Welcome to our website. Please log in now!")
username_credential=input(str("Please put in your username credential here."))
password_credential=input(str("Please input your password credential here."))
login=input(str("Would you like to log in?????"))
if login==("yes"):
    print ("Welcome",username_credential,"Have a nice day!")
if login==("no"):
    print ("Too bad so sad.")
change_password=input(str("Would you like to change your password???"))
if change_password==("yes"):
    new_password_login=input(str("Please enter your new password!"))
    print ("So",new_password_login,"is your new login credential right? Keep this one secret!")
if new_password_login==("no"):
    print ("Yah chubby")
Status_Update=input(str("Do you want to change your status?"))
if Status_Update==("yes"):
    print ("Whats your mood? Your current status is nothing ust say how you feel!")
Status=input(str("Please enter your mood!"))
print ("So",username_credential,"You are",Status,"Good job!")
Online_Connection=input(str("We also offer a free online services network would you like to connect?"))
#if Online_Connection=("yes"):
#'    #print ("Connecting to online servers..... Connection succesful!..... What game would you like too play? Our range includes The Magic Number Game!")
