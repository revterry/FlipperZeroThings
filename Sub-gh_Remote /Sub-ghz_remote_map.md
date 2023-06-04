Posted by u/MikeySkates at https://www.reddit.com/r/flipperzero/comments/zbiuwo/subghz_remote_map_configure_tutorial_for_new/?utm_source=share&utm_medium=web2x&context=3

#Sub-ghz remote map configure tutorial for new people
I wanted to make this post for new people. Because not a lot of people do a good job explaining simply how the sub-ghz remote feature works. Im dumb and had to research it myself. Basically, the sub-ghz remote is just a shortcut for sending out sub-ghz signals youve saved. Thats all it does. Its just a shortcut. It makes it to where you can press your up/down/left/right/ok buttons and each button will send out the signal you saved and assign to each button.

#This is what youre going to want to do:

Go into your flippers files. You can do this on your mobile app too. Go to file manager. Go to ext (or “any”. It doesnt matter) Go to Unirf (should be at the bottom) Create a file that ends with “.txt” Name it whatever you want. I named mine “remote.txt” Open the file and copy paste this below:

UP: /ext/subghz/example.sub

DOWN: /ext/subghz/example.sub

LEFT: /ext/subghz/example.sub

RIGHT: /ext/subghz/example.sub

OK: /ext/subghz/example.sub

ULABEL: example text

DLABEL: example text

LLABEL: example text

RLABEL: example text

OKLABEL: example text

The text above is how you will configure your remote map.

In your sub-ghz saved signals you have a saved signal that you named when you saved it. You will put the name of the signal you saved into the text code above.

For example: lets say you saved a sub-ghz signal and you named it “unlock”. And you want to program that signal to emulate when you press the up button. Above in the code where it says: “UP: /ext/subghz/example.sub” You will put the name of your saved signal into it and change it to: “UP: /ext/subghz/unlock.sub” MAKE SURE WEN YOU PUT THE NAME YOU SAVED INTO IT YOU END IT WITH “.sub”

You have now assigned the up button to send out that unlock signal you saved. Now you want to name it.

In the code where it says “ULABEL: example text” You will change it to “ULABEL: unlock”

And thats it. Youve now programmed your up button and gave it a name. “ULABEL” just means up label. Youre typing in what you want the label of the up button to be on the screen. The “UP: /ext/subghz/example.sub” is where your choosing the path of where the flipper will find the signal. Thats it. The rest of the code can be used to assign more signals to other buttons and name them whatever you want. Thats it! Its just a shortcut to sending out sub-ghz signals youve saved. I hope this helped you. Please comment if you need any further help!
