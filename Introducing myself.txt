# 17/01/23
# Welcome to my introduction readme! but also .py because fun.
greeting_top = "Welcome to my introduction readme! but also in .py because it\'s fun."
#print (greeting)

# My name is Sam McNamara, but sometimes online I go by "Poppleop", or
# "Pop" for short.
name = "Sam McNamara"
alias = "\"Poppleop\""
nickname = "\"Pop\""
greeting_with_name = "My name is "+name+", but sometimes online I go by "+alias+", or "+nickname+" for short."
#print(greeting_with_name)

# I'm 28 years old.
the_year = 2023
my_age = 28
greeting_age = " The year is "+str(the_year)+". I\'m "+str(my_age)+" years old."
#print(greeting_age)

# Coding has been a fun pastime for me, and I hope to turn that into a career, one step at a time.
# This has been my tiny, fun introduction. Hope you enjoyed.
# It's good to greet people and introduce yourself, afterall!
greeting_bottom = """Coding has been a fun pastime for me, and I hope to turn that into a career, one step at a time.

This has been my tiny, fun introduction. Hope you enjoyed.
It's good to greet people and introduce yourself, afterall!"""
#print(greeting_bottom)
greeting = greeting_top+"""

"""+greeting_with_name+greeting_age+"""

"""+greeting_bottom
print(greeting)