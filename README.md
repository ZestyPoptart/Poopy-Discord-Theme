# Poopy-Discord-Theme
My discord theme :P

Just download the file called "Poppy's Theme.css" and put it in your themes folder

This theme allows background images but a few steps are required to do so

1:
Go down to line 49 (--theme-background-image) and upload your image url

![image](https://github.com/user-attachments/assets/7956134f-2d17-4e00-9867-1c9dd9c79fd7)

2:
Your discord is going to look something like this:
![image](https://github.com/user-attachments/assets/633a3d9e-b8bb-4c90-9cda-718a3467f743)
To fix this we're going to change the opacity on the background color to make it appear invisible

3:
Go to line 48 (--bg-4)

![image](https://github.com/user-attachments/assets/98a9cab2-0b32-4613-99de-b7b4807aed18)

Now change the 4th number within the brackets from "1" to "0"

And now your background image should appear

To remove the image just follow the steps in reverse and your theme should go back to normal!!!

|
|

Currently changing the dm button is a bit of a harder process than this but its still fairly simple and I'm currently working on making it easier

1:
Go down to line 73 and remove all the code besides "--moon-icon: none;"

I recommend saving the deleted code somewhere in case you want to readd this later

Should look like this:

![image](https://github.com/user-attachments/assets/2bf77159-e794-4170-8b35-8d95e8b5ec40)

2:
Then go down to line 103 and copy and paste this code

.childWrapper_f90abb:has(> svg:not(.favoriteIcon_dcc7a4)) {
	background: url('');
	background-color: transparent !important;
	background-size: cover;
}

Should look like this:

![image](https://github.com/user-attachments/assets/0090133e-0d20-481a-87a5-fbb32d61908d)


3:
Then you can copy your image url into it and your icon should appear in the top left!!!!

thanks 4 reading and using my theme ◝(＾▽＾)◜
