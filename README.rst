============================================
Config dir for Ranger
============================================

What is Ranger
============================================

:code:`ranger` is a console file manager with VI key bindings.

- github: https://github.com/ranger/ranger

HOW TO USE IS DATFILES
============================================

.. code-block:: bash

   if [ -d "$HOME/.config/ranger/" ]; then
      rm -rf $HOME/.config/ranger/
   fi
   git clone git@github.com:qh73xe/rangerrc.git  ~/.config/ranger
   sh ~/.config/ranger/install.ubuntu.sh
