oven-dot-py
==============

oven-dot-py is a python api that is built on top of the AT&T library (SPEECH, SMS and PAYMENT), which enables any smartphones or websites to control hardware with ease.   
   
setup:   
bash getauth
<copy down the token>
python -i oven.py   
set_token(<token>)   
set_port(0, "lamp")   
set_port(1, "coffee maker")   

example usages:   
1. control device by speech   
voice_to_text("mypath/TURN ON THE LAMP.wav")   
    
2. control device by text   
set_text_inbox(<number>)
<text the number / id --> TURN OFF THE LAMP>   
text_get()   

3. payment by text   
text_get_with_payment()


