Change the ENTER HERE part to the thing you want to pop up for example:

import webbrowser
print("Hello and welcome to HOMEWORK ANSWERS! Here you will find all the newest homework answers! Just type 'A' to view the answers or 'h' to see how we work!")
enter = input("Enter here!: ")
if enter == "h":
    while True:
        print("XD HAHAHAHAHAHA IMAGINEEEEEE")
        webbrowser.open("https://google.com/search?q=HELLO")
elif enter == "A":
    while True:
        print("THIS IS IN YOUR SEARCH HISTORY LOL")
        webbrowser.open("https://google.com/search?q=CODING")
else:
    while True:
        webbrowser.open("https://google.com/search?q=TECH")


