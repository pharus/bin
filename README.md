# bin

Scripts in shell I usually  use for my machines.
All are using bash.

List:
- ewrap: evince wrapped as in wrap, to use evince for pdfs.
- twork: open a tmux session in a folder, keep name for session, window main 
- upub: update, upgrade, dist-upgrade in apt suites, normally ubuntu
- upfed: same as upub, but with dnf , normally fedora
- wrap: envelop command with redirection of stdout and stderr to /dev/null.
 

Dependencies:
- ewrap
	+ evince
	+ wrap
- twork
	+ tmux
- upub
	+ apt management tool
- upfed
	+ dnf management tool
- wrap
	+ a shell

