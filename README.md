# Ctrl-Zsh

Did you know you can suspend any (well, almost any) process in the terminal by pressing Ctrl-Z?  You did?  But you always found it a pain to reactivate it because you had to type `fg` at the prompt?  Me too!

That's why I wrote **Ctrl-Zsh**.  Just install this tiny Zsh plugin and suddenly Ctrl-Z will *also* take you back *into* the process you just left.  Amazing!

(For more information about the awesomeness of job control, see [my blog post on the topic][job control].)

[job control]: http://blog.peeja.com/blog/2012/08/29/lets-talk-about-jobs/

### Installation

#### Antigen

[Antigen] is awesome, and if you aren't using it yet, you should give it a try.  To install Ctrl-Zsh just add

```
antigen-bundle Peeja/ctrl-zsh
```

to your `.zshrc`.  Or, to try before you buy, just run that command to enable Ctrl-Zsh for the current shell session.

#### Oh My Zsh!

Add it to your plugins directory, like so:

```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/Peeja/ctrl-zsh
```

#### Other

Just source `ctrl-zsh.plugin.zsh` from your `.zshrc`.  Or, heck, copy it *into* your `.zshrc`.  It's only three lines!  (But I've got devious plans for more.)

[Ctrl-Zsh]: https://github.com/Peeja/ctrl-zsh
[Antigen]: https://github.com/zsh-users/antigen