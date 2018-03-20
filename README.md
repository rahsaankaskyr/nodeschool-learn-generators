Install or Update

    You need nodejs >= 0.12.x or iojs >= 1.0.x

$ npm install learn-generators -g

Start learning
0. General information

learn-generators is i18n-friendly workshopper, currently you can learn on English or French language. Hit choose language menu item or selet language with -l flag with aviable prefixes: en, fr, ko, ja, es and ru. Type:

$ learn-generators -l

To see aviable languages and select the language which you like.

You can also get all available commads in help:

$ learn-generators help

1. Select a topic to learn

Once the workshop is installed, run learn-generators to print a menu where you use the arrows ↑↓ (vim jk works too) to select a topic to learn.

$ learn-generators

2. Writing your solution

Once you have selected a topic, the workshop will remember which problem you are working on. Using your preferred editor, simply create a file to write your solution in. Most topics will supply some boilerplate with which to get started. Copy this from the topic description to your solution file.
3. Testing your solution

Use the workshop's run command to point the workshop at your solution file. Your solution will loaded and passed the topic input. This usually won't perform any validation, it will only show the program output.

$ learn-generators run mysolution.js

4. Verifying your solution

Your solution will be verified against the output of the 'official' solution. If all of the output matches, then you have successfully solved the problem!

$ learn-generators verify mysolution.js