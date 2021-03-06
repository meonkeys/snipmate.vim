snipmate.vim
============

:Author: `Michael Sanders`_
:Maintainer: `Rok Garbas`_
:Homepage: http://www.vim.org/scripts/script.php?script_id=2540 

::

    After several unsuccessful attempts of contacting Michael Sanders, no
    commits in last half year and long pull request line on github (none of
    pull requests were commented/replied/rejected).

    But nothing to worry about. We all get busy, accupied with our daily work
    or just lose interest in doing boring maintainance.

    While reviewing pull requests on github.com/msanders I found lots of great
    improvements and I decided to **friendly** fork it review and apply patches
    that were send, notify all the patch submiters and do the maintainance of
    snipmate.vim from now on. Ofcourse if somebody want to help, please don't
    hesitate to write me. The only thing in what I'm not interested is leaving
    things like they are now.

    Maybe I'll only maintain it for a while until Michael Sanders takes things
    back into his hand or until some other super-hero shows up.

    Tnx and happy snipmating, Rok Garbas



How to install
--------------

    * using `vim-addon-manager`:
      Add "snipMate" to the addon list.


    * manually:
      See snipMate-addon-info.txt, you need tlib and vim-addon-mw-utils


comment about this (MarcWeber) branch
-------------------------------------

::
    I also asked Michael Sanders - A long time ago I got a reply - but nothing
    which would have lead to a merge.  Probably my branch can be dropped if Rak
    Garbas accepts my (major?) changes

    My forks differs in the following way:

    - snippets are loaded lazily.

    - snippets are no longer cached. Thus you always get the snippets you just
      wrote to a file without reloading anything.

    - when visually selecting a snippet in a .snippets file you can press <cr>
      to replace spaces by tabs automatically in a smart way



future
--------------------------

::
    I'd like to investigate whether xptemplate or snipmate has the better
    engine. So maybe my vision of the future could be making xptemplate read
    snippet files. It is not important enough to me to work on it right now,
    because snipmate works reasonable well for me.

    Snippets should be distributed in additional repositories. Eg
     - snipmate-snippets-ruby
     - snipmate-snippets-vim
     - snipmate-snippets-...
    One repo containing snippets is:
    git://github.com/scrooloose/snipmate-snippets.git


    comment without verifying it:
    < Silex> MarcWeber: btw, check out ultisnips. Much better than snipmate imho

    And before this discussion xptemplate vs snipmate vs ultisnips .. continues
    we should create a wiki page comparing them and keep that up to date.
    If you volunteer tell me so that I can reference the link.

    Think about merging:
    https://github.com/vim-scripts/superSnipMate
    (note: vim-scripts is only a "mirror all service".
    I asked the author o superSnipMate to create his own upstream on github.
