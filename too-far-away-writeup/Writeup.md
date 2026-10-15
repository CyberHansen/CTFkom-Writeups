# Too far away - Writeup

**Category:** OSINT / Misc
**Points:** 912

> The flag is right there, on the sign :)
>
> (you do need a minecraft account to solve)

![challenge](images/01-challenge.png)

We get a screenshot from Hypixel SkyBlock with a sign circled in red. The sign is way too far away to read, so we have to go there ourselves.

![minecraft.png](images/02-minecraft.png)

## Getting into the game

First head to [minecraft.net/download](https://www.minecraft.net/en-us/download).
Either buy Minecraft, or download the launcher if you already own it.

![download](images/03-download.png)

Once the launcher is installed and you're logged in, click **Play**.

![launcher](images/04-launcher.png)

Press **Continue**.

![continue](images/05-continue.png)

Then click **Multiplayer**, and accept third-party online play.

![multiplayer](images/06-multiplayer.png)

## Finding the server

In the screenshot we can see the scoreboard says `www.hypixel.net`, and it's SkyBlock. So the player is on Hypixel SkyBlock.

![hypixel](images/07-hypixel.png)

Add a new server with the IP `mc.hypixel.net`.

![add server](images/08-add-server.png)

When you're in the server, open the Game Menu in your hotbar and click on **SkyBlock**.

![skyblock](images/09-skyblock.png)

Click **Proceed** on the resource pack prompt.

![proceed](images/10-proceed.png)

## Visiting his island

Now you're on your own island. We need to get to his island instead. In the bottom left of the screenshot you can see a chat message from him, so his username is **Minoritet**.

![username](images/11-username.png)

Type this in the chat:

```
/visit Minoritet
```

![visit command](images/12-visit-command.png)

Click to visit his island.

![visit menu](images/13-visit-menu.png)

## The sign

Here we are. The sign is right there, just walk around it to the front.

![sign back](images/14-sign-back.png)

![flag](images/15-flag.png)

## Flag

```
CTFkom{5kybl0ck_ctf_1s_fun}
```

## Bonus

Amazing world btw. Had to take a look around before leaving :)

![world](images/16-world.png)
