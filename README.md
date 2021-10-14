# zakim-monitor
A program that watches [Zakim](https://www.w3.org/2001/12/zakim-irc-bot.html) in an IRC channel and shows a live view of Zakim's current agenda, queue and questions.

Screenshot:

<img alt="Screenshot of zakim-monitor running in an xterm" src="screenshot-curses.png" style="width: 496px">

Run it with a command such as this:

    perl zakim-monitor ircs://mylogin:mypassword@irc.w3.org/channelname

(Leave the password empty to have the program prompt for it.)

The full manual is contained in the program file. Use `perlpod zakim-monitor` to read a formatted version.

## Installation
The [program](zakim-monitor) requires Perl and the following Perl modules to be installed:
* [Bot::BasicBot](https://metacpan.org/pod/Bot::BasicBot) (in Debian: libbot-basicbot-perl)
* [Curses](https://metacpan.org/pod/Curses) (in Debian: libcurses-perl)
* [Term::ReadKey](https://metacpan.org/pod/Term::ReadKey) (in Debian: libterm-readkey-perl)
