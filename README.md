# clyde

Clyde Lets You Do Everything - keep track of your personal projects and DO them!

```

                 ((   )  (
               ( (   )(( (   )
             )    ) ( )) )( (( )
             ( (((   )  (  )  ) )
            )) (( ) (          ((
           (  )) )  ____   ____ )
            ) ( ) `|<();|-|,()>|
           ( ))(    `--'  \`--'
           )( ( )       (- )   )
             ))        _____  /
               )   `     --  /
                     `   __,

```

Do you find yourself starting random personal projects and never finishing them?

This is a CLI tool that allows you to easily track things that you want to work on and things you want to learn and improve on, but maybe don't necessarily always have the time or motivation to keep it top of mind.

## Installation

Clone this repo. Put the file `clyde` somewhere in your $PATH. It is a simple bash program.

## Usage

When you think of something you want to do or a project that you started but don't want to forget about, use `clyde add` to add it to the list.

```
$ clyde add "Learn more about electromagnetic radiation"
```

This will store the fact that you want to learn more about electromagnetic radiation in your list of "projects."

When you are wondering what you should look on you can have clyde suggest to you something to do. It will select something by random from your list of projects.

```
$ clyde suggest
Today you should spend time working on this:
----------------------------------------------------------------------------------
#23: Learn more about electromagnetic radiation
----------------------------------------------------------------------------------
```

It's now up to you to work on it. Clyde lets you do it!

Keep on adding to your projects and it will always be there for clyde to remind you when you need it.

You can also type `clyde list` to get a list of all the things you have added. You can type `clyde manage` to open the list of projects in a text file. This is good for adding more (one project per line), or removing old ones that you don't want to worry about anymore.

It's exciting to see yourself improve and return to old plans you had. Give it a try!

----

* Ascii ART thanks to ejm (http://www.chris.com/ascii/index.php?art=people/faces)
