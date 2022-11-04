# alarm
the syntax used in the alarm file is:
> command grep/argument/for/date/command

The date command is commented in the alarm executable

The command calls xfce4-terminal and is therefore unable to operate with systemctl, however, by putting it in the ~/.xinitrc file you are able to use it whenever you start up your xfce environment.
This allows for usage such as an mpv alarm clock without ever needing to touch a graphical programm.

> exaple at time: Nov 4, 2022 version
>> this is a comment #
>> 
>> friday morning alarm #
>> 
>> play 'Lemon Fight - Stronger' 00/06/.*/.*/.*/5

The syntax can easily be reverse, but I prefer it this way at the momenr. If I decide to make a new syntax, I will add a comment/make a new file, so watch out for that. You can alwais, and are encouraged to
explore the options and change the file to best fit your needs
