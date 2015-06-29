# Plugin.yml-Tutorial

Learn how to make a correct plugin.yml


Here you will learn how to make a plugin.yml without any errors, so that your plugins work!

The first thing you will want in your plugin.yml is a name. This is the name of the plugin you are working on 
and this is what will show up when you type /pl or /plugins.

The second thing that is very important is a version. This is only important because minecraft requires it.
The actual number version you put is not very important itself.

The third thing that is probably the most important for your plugin.yml is the main class. The path is case 
sensitive so PLEASE be careful with this. It is the name of the package then .(main class). For example if
me.kevin.Example was my package and my main class was Example it would be as shown: me.kevin.Example.Example 

If you have any commands in your plugin, then you MUST have a commands section in your plugin.yml. This tells
bukkit what commands you have, and how they will be used when formmating your commands you must use 4 spaces
and must not use tab because this will cause your plugin to fail tremendously. The same goes for permissions,
if you have any you must have a section for permissions in your plugin.yml.

An optional addition to your plugin.yml is author. Here you can just type your mc name if you would like, or
whatever name you please.
