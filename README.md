# bash-tutorial-game

Awesome tutorial to teach people bash, which is also a game.

# Step 1 - Opening The Terminal

## Mac

On mac, press CMD + Space to open spotlight, then type `terminal` and press enter.

Maximise the window by double clicking the bar (or use CMD + F if you have Specticle).

## Linux

On linux, press CMD, type `terminal` and press enter.

## Windows

First you need to install virtual box to get linux.

# Step 2 - Setting Up The Game

Run `ls` (type `ls` then press enter).  This will print a list of your directories in your home folder.  You will see something that looks like this:

```
sam@net1:/Users/sam ls
Applications			Documents			Library				Music				Public				steelseries-exactmouse-tool.dmg
Desktop				Downloads			Movies				Pictures
```

Create a directory in your home directory called `src` by running the following command. We will explain the `mkdir` program more later.

```
mkdir -p src
```

Now when you run `ls` you will see the `src` directory, like this:

```
sam@net1:/Users/sam ls
Applications			Documents			Library				Music				Public				steelseries-exactmouse-tool.dmg
Desktop				Downloads			Movies				Pictures			src
```

