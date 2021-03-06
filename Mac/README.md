Mac Configurations
==================

## [Install-Casks.sh](Install-Casks.sh)
This shell script helps install a bunch of apps from [Homebrew Casks](http://caskroom.io)
For more apps and Safari extensions, see my pinboard links tagged with [Mac Essential](https://pinboard.in/u:netj/t:mac/t:essential/).

## [Tweak.sh](Tweak.sh)
This shell script includes some preference tweaks I use on my Macs.

## Terminal.app
Open any `.terminal` file to load configuration into OS X's Terminal app.
You should use Mac's default terminal unless you have a strong reason to do
otherwise, even after watching [the talk given by the author of Terminal.app (Ben Stiglitz)][Ben Stiglitz's talk] I found from [TotalTerminal's website in the past][TotalTerminal special guest].
I recommend using [Envy Code R font][] for your terminal if you want something
different from Apple's default, Menlo or Monaco.  You can find more fonts from
my [Fonts directory](../Fonts#readme).

### MouseTerm plus
(OS X 10.11 El Capitan now ships a Terminal app that has superior mouse reporting capability which can be enabled from menu View > Allow Mouse Reporting, this plugin is no longer necessary! :)

[MouseTerm plus][] is a great SIMBL plugin, which passes mouse events to programs
running in OS X's Terminal.app, e.g., tmux, vim, or emacs.  I [highly
recommend installing it](http://superuser.com/a/595284/45702) because there's
nothing to lose.

You can still use most of the old mouse behavior with option key pressed, e.g.,
Option+Command+clicking for opening URLs, selecting blocks of text, etc.
However, selection that spans over multiple lines becomes impossible.  A
workaround is to select all lines from the first column and trim the first and
last line afterwards.


## Karabiner private.xml
[Karabiner][] (or formerly KeyRemap4MacBook) is a great tool that allows you to remap keyboard in OS X.
I'm using it to remap left command as option key except a few Mac key combinations in Terminal.app, and Esc to switch back to English IM in Vim to make life easier.


## Many Scripts
In the `Scripts` directory, there are various AppleScripts I use for many
purposes.  I bind them to global and application-specific shortcut keys with
[FastScripts][].  Some might be useful as-is, others might need to be tailored
to fit your need.  Feel free to copy and modify them, or include in your
scripts.

### Automatically Organizing Window Layouts
I'm using [`HelloDisplay.applescript`](Scripts/HelloDisplays.applescript) with [Control Plane][] for repositioning and resizing windows as I move around.


## BetterTouchTool Gestures
[BetterTouchTool][] is another awesome tool that lets me use trackpad on a
whole new level.


## iStat Menus
[iStat Menus][] is pretty essential to have an eye on what's going on your Mac, and I have [settings to keep it compact](iStat%20Menus%20Settings.ismp).


[TotalTerminal]: http://totalterminal.binaryage.com 
[TotalTerminal special guest]: http://web.archive.org/web/20140805045750/http://totalterminal.binaryage.com/#special-guest
[Ben Stiglitz's talk]: https://confreaks.tv/videos/rubyconf2008-terminal-app
[Envy Code R font]: http://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released
[MouseTerm plus]: https://github.com/saitoha/mouseterm-plus#readme
[Karabiner]: https://pqrs.org/osx/karabiner/
[FastScripts]: http://www.red-sweater.com/fastscripts/
[Control Plane]: http://www.controlplaneapp.com/
[BetterTouchTool]: http://blog.boastr.net/
[iStat Menus]: https://bjango.com/mac/istatmenus/
