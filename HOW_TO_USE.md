Usage:

STEP 1.
Change samples to your real email/password at these lines in SCSender.py 
Don't foget to change delay between sending emails.

send_to = 'SEND_TO@EMAIL.COM'       #email to send
user_email = 'USER_EMAIL@EMAIL.COM' #your email; gmail is recomended
user_password = 'PASSWORD'          #your password
smtpserver = 'smtp.gmail.com'       #smtp server; gmail is recomended
smtpport = 587                      #smtp server's port
delay = 30                          #delay between sending emails in seconds


STEP 2.

Type "pip install requirements.txt"
Type "python SCSender.py" in terminal.
