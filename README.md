
I forked the repo, fixed some issues and added some missing hex codes.
I only have a ti84+, so I don't know if this works with anything else (100% not all hex codes will work on ti83).

https://aur.archlinux.org/packages/ti84cc-git

Tip: if you need to add any hex codes (example: lower case letters, tibasic instructions)
you can add them on your calc then use tilp2 to transfer the program back to your PC then
open it in a hexedit and check the code

I have also updated some of the tokens, for example what used to be ` or ` is now ` [or] `. See `tokens.cpp`.

# Old description

== The TI-BASIC Compiler

The TI-BASIC Compiler is all about compiling TI-BASIC code on your computer
into an 8XP file ready for transferring to your TI-83/TI-83+/TI-84 calculator.

Being able to type your programs instead of try and use the calculator's keypad
is much easier :).

== How to run the compiler?

For most situations, just "drag and drop" the text file containing your code
on top of the tibasic.exe file. A black window will appear for a split second
and you should have an 8XP file next to your text file.

If you feel comfortable using a command line, you can run tibasic.exe without
any arguments to get usage information.

== Important Note!

There are a few symbols that could not be directly transferred to the language and were replaced instead with simpler tokens. Also note some of these are 'shorthand' versions of supported tokens:

& --> 'and'
| --> ' or '
~ --> ' xor '
theta --> '[theta]'
powers --> '^' (for instance, 5 squared would be '5^2')
'e' constant --> '[e]'
Store --> '->' (same for such things as >DMS: ->DMS)
Roots --> '[root]^' (for instance, square root would be '[root]^2')

All Picture variables (Pic0 - Pic9) and String variables (Str0 - Str9) are CAPITALIZED (ie. STR0)

Other shorthand versions for more obscure functions exist, to find these the source code is viewable (Develop tab on the SourceForge page).

-----------------------------------------

As a final note, all support requests must go to either the 'Support Requests' tracker on the SourceForge page, or pcmattman@gmail.com (the email method usually gets a reply within 24 hours). The trackers are checked often so you can be assured that your request for help will be responded to.

Happy programming!
