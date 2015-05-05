# The Lullabot Lunge in VR
Lullabot's first VR website. Visit in [janusVR](http://janusvr.com/) >>> http://lullabot.github.io/lb_breakroom/

## tldr;
* download janusVR
* launch janusVR
* when you see a room, hit tab and enter the address http://lullabot.github.io/lb_breakroom/
* a portal will appear. click the portal and walk through and you'll be in this lounge

## Viewing

### Prerequisites
* [janusVR](http://janusvr.com/)
* [Mumble Client](http://wiki.mumble.info/wiki/Main_Page) (if you want voice chat)

To view this site properly, you need the janusVR 3D web browser. Go to http://janusvr.com/, click the download link, and choose the client for your OS.

Upon first launching the browser you will be taken to the default website which is called the Lobby. From here you can walk around and click on various other portals to explore even further. Here are some of the basic controls:

### Movement
* Hit `w`, `a`, `s`, `d`, `q`, and `e` to move around.
* Hit `f` to enter flight mode. Look where you want to fly and hit `w`, `a`, `s`, `d`, `q`, and `e` to move.
* Hold left click to see an arrow. After a few miliseconds you'll see a green avatar appear. Release to instantly teleport to where your mouse cursor is placed.

### Navigation
* Left click on any portal to open and just walk through.
* Hit `tab` to create your own portal. A textbox will appear with the ability to type in any url you want. If the website you choose does not have janusML, a default room will be generated with the 2D version of the website presented on the walls.
* Click on a web surface to control the website. While the web surface has control of your mouse, you can hit `tab` to enter a new address. Note that `tab` does not switch between text input fields in a web surface.
* Hit `cmd+b`(mac) or `ctrl+b`(win) to bookmark the current url you are within. Bookmarks can be accessed from the main lobby, or from the `esc` menu.

### Communication
* Hit `t` to text chat within janusVR.
* Hit `c` to open up the chat log. You can scroll this with your mouse wheel or trackpad.
* To voice chat with the **janusVR community**, download the Mumble client and connect to 
 * Address: `babylon.vrsites.com`
 * Port: `64738`
* T voice chat with **Lullabots**, see our [wiki page](https://github.com/Lullabot/lb_breakroom/wiki/Connecting-to-our-Mumble-Chat).
* The janusVR community also communicates asychronously via the [janusVR subreddit](http://www.reddit.com/r/janusVR/).

### `ESC` Menu
* Hit `esc` to see various options presented as floating buttons. This will also give you a floating web surface presenting the 2D version of the url you are currently within, as well as your avatar, and a link to your bookmarks. Hit `esc` again to turn off the menu. 

### Editing Basics
* **Turn on edit mode**: Hit `esc` to access the options and select `Edit Mode` to turn it on. Hit `esc` again to turn off the menu. Now you can use the right click to edit anything you see (unless it's locked).
* **Spawning**: A single right-click will spawn a primitive object. If you now hit `w`, `a`, `s`, `d` you can cycle through various primitive object. Another single right-click will cancel the operation. A single left-click will commit the operation, placing the object within the room where others can now see it.
* **Selecting**: A single right-click on an object will highlight it and it will begin to glow. Text will appear in front of it indicating it's `pos` vector. You can change these values with the `w`, `a`, `s`, `d`, `q`, and `e` keys. Hitting the `tab` key while an object is highlighted will allow you to cycle through the objects attributes such as `xdir, ydir, zdir`, `scale`, `col`(color), etc.
* **Copying**: While and object is highlighted with a right-click, you can also copy it with `cmd+c`(mac) or `ctrl+c`(win).
* **Pasting**: Hold right-click and place the green cursor whereever you like, then hit `cmd+v`(mac) or `ctrl+v`(win) to paste a copy of the object.
* **Saving**: Hit `cmd+s`(mac) or `ctrl+s`(win) to save the source code of the url you are within to your clipboard. This also saves an html file of the output to your workspaces directory. The workspaces directory is found within `/Applications/janusvr.app/Contents/MacOS/`(mac) or alongside of the janusVR executable(win).

### Changing Avatars
* **Method 1**: `cmd+click`(mac) or `ctrl+click`(win) on any ghost you find to assign it as your own avatar. A ghost is a janusML specific asset. You can find a bunch of pre-made avatars at http://lobby.vrsites.com/avtype/
* **Method 2**: your avatar is read from a text file on your system found within `/Applications/janusvr.app/Contents/MacOS/userid.txt`(mac) or alongside of the janusVR executable(win). This is a basic janusML file where you can define your own head and body using regular .obj or .dae models and materials. For more examples on this, see http://vrsites.com/assets/nukemarine_02/10/userid_avatars.txt

## Credits
Original model created by [/u/dizzket](http://www.reddit.com/user/dizzket). Please ask him for permission before reusing.
