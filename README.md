# hyperskill-python
(Under Construction, Updating everday. Do visit again!)

## Projects
1. [Zookeeper](https://github.com/afk1997/hyperskill-python/blob/master/README.md#zookeeper)
2. Coffee Machine
3. Hangman
4. Tic-Tac-Toe




## Zookeeper
### Stages
- [Stage 1:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-1)
- [Stage 2:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-2)
- Stage 3:
- Stage 4:



# Stage 1: Rush into Print

# Description <br />

There are many animals in the zoo: all of them need care, and some of them are endangered and require preservation efforts. Animals must be fed, cleaned, surrounded by their kin, and kept happy. That is a difficult task for such a big open-range zoo, so one of your employers suggested a better way to accomplish that. She wants to be able to watch any animal on the screen with the help of a special program. <br />
In this project, you will create a program that helps the zookeeper check on the animals and see that they're well. Your product will be able to understand commands from the zoo staff and show the animals on the monitor. <br />

## Objectives
To begin with, you should develop a simple printer. Your program must show the text from the output example. <br />

## Example<br />
Output:<br />
```
I do love animals!
Start looking after animals...
Deer looks fine.
Bat looks happy.
Lion looks healthy.
```
#### [Solution:](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage1.py) 

# Stage 2: Show me an animal!

# Description<br />
The important thing about working with animals is watching them. We need to see the animals on the screen to know how they are doing, right? At this time, we are ready to print something awesome: animal images! <br />

## Objectives
In the second stage, you need to develop an animal printer. Your program should show a certain animal: you will find it in the code field. <br />

Please, don't remove the r character at the start of the code template. It's a part of the string and it's important. So, the string should start with r""" sequence. <br />

## Example <br />
Your output should contain the following ASCII image: <br />

```
Switching on camera from habitat with camels...
 ___.-''''-.
/___  @    |
',,,,.     |         _.'''''''._
     '     |        /           \
     |     \    _.-'             \
     |      '.-'                  '-.
     |                               ',
     |                                '',
      ',,-,                           ':;
           ',,| ;,,                 ,' ;;
              ! ; !'',,,',',,,,'!  ;   ;:
             : ;  ! !       ! ! ;  ;   :;
             ; ;   ! !      ! !  ; ;   ;,
            ; ;    ! !     ! !   ; ;
            ; ;    ! !    ! !     ; ;
           ;,,      !,!   !,!     ;,;
           /_I      L_I   L_I     /_I
Yey, our little camel is sunbathing!
```

#### [Solution:](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage2.py)

# Stage 3: What's Inside?

# Description <br />
The third stage brings new abilities for your software: it will be able to recognize the number of a specific habitat from the input and show the animals living there.<br />

Add all variables with images from the template to a variable with the type list. The order of variables matters: they must be in the order they're defined in the code. The list must contain all of them with no duplicates.<br />

## Objectives <br />
In this stage, your program should: <br />

Ask for a number of the habitat using the following phrase: `Which habitat # do you need?.`<br />
Use the input number as an index of your habitat to print its content.<br />
End with the following phrase:

`The end of the program. To check another habitat restart the watcher please. `
## Examples
The greater-than symbol followed by a space (> ) represents the user input. Notice that it's not part of the input. <br />

### Example 1
```
Which habitat # do you need? > 5
 
Switching on camera from the habitat with rabbits...
         ,
        /|      __
       / |   ,-~ /
      Y :|  //  /
      | jj /( .^
      >-"~"-v"
     /       Y
    jo  o    |
   ( ~T~     j
    >._-' _./
   /   "~"  |
  Y     _,  |
 /| ;-"~ _  l
/ l/ ,-"~    \
\//\/      .- \
 Y        /    Y
 l       I     !
 ]\      _\    /"\
(" ~----( ~   Y.  )
It seems there will be more rabbits soon!

The end of the program. To check another habitat restart the watcher please.
```

### Example 2
```
Which habitat # do you need? > 4
 
Switching on camera from the habitat with bats...
_________________               _________________
 ~-.              \  |\___/|  /              .-~
     ~-.           \ / o o \ /           .-~
        >           \\  W  //           <
       /             /~---~\             \
      /_            |       |            _\
         ~-.        |       |        .-~
            ;        \     /        i
           /___      /\   /\      ___\
                ~-. /  \_/  \ .-~
                   V         V
It looks like this bat is fine.
---
The end of the program. To check another habitat restart the watcher please.
```

#### [Solution](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage4.py)


