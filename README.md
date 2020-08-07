# KEYBOARD KEYCODE APP:sparkles:

#### ABOUT
This is a simple app I designed to checkout keyboard
key codes of the various keys on the computer keyboard when clicked.

The code below is the major key in the code :smile: (please forgive my pun).
 
```
  window.addEventListener('keydown', function (event) {
            kbdCode.innerText = event.keyCode;
            console.log(event) // returns a key code object
 }
```  

from the  object when you press the `A` character key, the `event.key` returns `A`
while the `event.code` returns `KeyA`. there are other properties from the event object 
to check out too.

you can checkout the [Keyboard key code app](https://thepascoder.github.io/get-keyboard-keycode-app/) 

(hi, this right here is me lerning how to write a README.md file. So here's my first thanks.)
