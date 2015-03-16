Wiking is extensible through modules. Modules may define classes to replace or enhance the functionalities of Wiking.

A module is a folder placed inside the module dir of Wiking, or inside the module dir of the app itself. Modules inside app dir always replace modules in main dir, in case of conflict.

# media ressources for modules #
For modules inside wiking dir, there is no way to display an image for example, as the wiking dir is usually outside of the scope of the web server. A special node may take place to handle that, like wiking:modules:module\_name:img:file.jpg, where the node, could be wiking