# keyFu

KeyFu is currently just a weaksauce little thing that runs on the Windows Desktop.  The project's core came from an accessibility/universal macro utility that I built for MS Windows, but that project is finished and delivered to the client.  I took my core and moved it into this little gadget which has some specialty uses for geeks, nerds, and other bespectacled types who glare intently into flickering rectangles of LED-backlit plastic while mashing weird little boxes of petroleum-distillate-byproduct down on rubbery pads.

KeyFu is only active while the desktop app is running.  To shut it off, just close the program.  It doesn't save profiles or target any specific application.  When it's on, it's on, you have to define your target keys and delay values every single time you start it up, etc.

You may define 3 specialty key treatments:

## The Double-Tap:

The Double-Tap Definition defines a key that you have to double-tap before it registers a single keystroke.  The delay value represents how fast you have to double-tap it, or how long the delay is between the first tap and the second tap before the keystroke is completely discarded.  What on earth for, you ask?  I imagine a lot of people could find a lot of uses for it, but the one that gets the most attention from this group of flickerfiends with cludgy fingers who grope in a panic for V and inadvertently hit G in the process is to set, for example, your Grenade key as a double-tap definition.

So if you elect G as your double-tap key and give it a delay of 50, you have to hit G twice really fast to get it to register G once.  After the first registered tap, though, you can keep pounding away at G (so you can throw 4 grenades in rapid succession, you don't have to double-tap every single time, just the first time to activate the key).  That way when V is your melee and G is your grenade, you're not mashing V and G at the same time and throwing a grenade in your own face because the nade is bouncing right off the nose of the monster you're trying to boff in the snoot!

If 50 milliseconds is way too fast then just push that Delay value up to 500 - if that's still too fast then push it up some more.  Just keep in mind that the higher the Delay value, the longer the app waits for the second tap that activates grenades.  So if you're really mashing V and your double-tap delay on G is 1000ms (1 full second) and you accidentally mash it twice in 1 second, you're going to nade yourself anyway.

The app is really smartly designed.  You don't have to hunt for the key you want to select - just open up the dropdown and tap the key you want, and it jumps right to it.  Just keep in mind that once you've elected that key, it's bound.  If you define G as a double-tap, you'll now have to double-tap G in chat boxes to get it to show up as well.

## The Hold:

The Hold Definition defines a key that you have to hold for a little bit before it registers a single keystroke.  The delay value represents how long you have to hold before it activates the key, but once activated it repeats at the normal typomatic repeat as if you held the key down normally.

Delay is exactly the same as with Double-Tap, except that it represents how long you have to keep the key held down before it registers the first keydown message.

This is intended for the same purpose as the Double-Tap, just a different way of going about it, for folks who find they just plain can't find a Double-Tap speed that both fits a speed they can perform deliberately and at the same time fits speed they can manage not to perform accidentally.

## The Repeat:

The Repeat Definition has gotten me scolded even by people who use and love either/both of the above features in multiple games.

Why is it in here in the first place?  I have that common problem lots of people call carpal tunnel, which in my case comes from having a broad shoulders and huge hands and using a keyboard and mouse 80-120 hours a week and living in a world where computer mice and keyboards are designed for people who are literally 3/4 my size.  If you don't know what carpal tunnel is:  My right hand develops godawful cramps in the thumb, which curls into a claw of searing pain that I literally have to pry open with my other hand and bend back until the nail touches my forearm to stretch it out.

This will happen sooner or later anyway, but comes a lot faster when I'm constantly clicking the left mouse button, such as is required with any game that thinks it's a brilliant idea to give you a semi-automatic weapon and then throw endless hordes of enemies at you who have a Panzer tank where their frontal lobe should be.  This is plain idiotic game design whether the player has carpal tunnel or not, by the way, but puts me specifically in a world of hurt in less than a minute.  If I take the 30 second break I desperately need to stretch my hand I'm just going to die in-game.  I don't know why pressing and holding the button doesn't stress the tendon in my wrist like constantly clickety-click-click-clicking does, but it doesn't.  And before you say, "Just don't play those games," just internalize it and go back to eating paint chips.  I have friends who like those games and I like spending time with my friends.  Even if I didn't have carpal tunnel, these kinds of games would suck and I'd still play them with my friends.  I just wish game designers would spend more time designing a decent game instead of wasting all their budget on eye candy and then puking up a game that plays like smashing your face with a 2x4, which is only fun when you quit doing it.

I know I'm not the only person in the world who has this problem.  My mom had the same problem 20-30 years ago and she's not even built like I am.

So why do other people who are served by those other two accessibility features pitch a titty fitty about this one?  Because if you don't have this problem you think it's just a cheat.  Dumbass.

As with the other features, Delay is in milliseconds.  In this case, it represents the number of milliseconds between key repeats.  You need to be really careful with this setting.  You'll probably use this key with your fire button, and your fire button is also your select button for menus, so setting it too low *will* cause problems with menus.  You'll also probably be using your fire key with both semi-auto weapons and full-auto weapons, so setting it too low and using it with full-auto weapons *will* cause you rapidly chew up all your ammo in full-auto weapons (and semi-auto too).  On the flip-side, if you set it too high then your semi-auto weapons won't fire fast enough to kill anything before it eats your lunch.

## Patreon

I have a Patreon goal set up for further development on this.  If you like the idea, want features or improvements, pitch me your ideas.  If you want to see the source, feel free to contribute.

https://www.patreon.com/tekmunkey