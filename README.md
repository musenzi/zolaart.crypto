# zolaart.crypto
Repo for zolaart.crypto

For more info about zolaart.crypto go to https://art.musenzi.be or if you're using Opera browser you can go directly on https://zolaart.crypto I think...

This repo will only store the smartcontracts used on the site. 

It is open source and you can use it as a base for your own projects if you want.

How does it work?

You can deploy any of these contracts yourself using zilliqa's IDE or other ways you may know...
Just copy the code and paste it in the textbox, change the name of your file and check => save => deploy

When deploying you need a few parameters.

Owner : Owner of contract in base16

Description : Description of your project 

Artist : Your name/twitter handle/telegram handle or just a random chosen string 

Original Mail : The mail address u use for contact [Unchangable]

There is feature that permits the owner to change the mail address. The OG mail address will stay, but there's another mutable field called curr_addr to change it. 

The contracts are in their simplest form like this.

Future projects:
As I started working with artist I ended up taking the role of a manager. I don't like that but it gave me another idea...

[Manager functionalities on a contract coming up!!!]

Manager will work based on the same principle as the mail func. 
With an OG manager that could still be the artist itself if so chosen! 
In theory at least... But should be fun to try out!

As a rule of thumb never trust external contracts, test them out on https://ide.zilliqa.com/#/ or talk to someone who can read and understand Scilla. 

Docs for Scilla: https://scilla.readthedocs.io/en/latest/

If you find bugs or you know how to make it faster/more secure or anything that can improve it, please mail at info@musenzi.be
