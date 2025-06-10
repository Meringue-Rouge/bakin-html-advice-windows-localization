# bakin-html-advice-windows-localization
HTML version of the Advice Windows used in RPG Developer Bakin for the purposes of localization.

This is only useful for those who want to make localisations of the Bakin engine.

Currently, Bakin uses images that are displayed through HTML, which isn't too great for translating, especially since it's the first thing that a new user will see. With some quick work, I've converted the contents and layouts from the original advice images and turned them into pure lightweight HTML code.

This should make it significantly easier to translate the tool in it's entirety without having to open an image editor.

Additionally, the splash screen has a "Translated by" banner at the bottom if you wish to credit yourself and has a link you can change, and each advice window has a corresponding link to the English bakin wiki page regarding the subject. Of course, since it's HTML, feel free to edit the contents of the pages to suit your localisation, or even enhance it with related imagery. The styling is contained within the styles css file, and affects all the files except for the FormTop page (the splash screen).

To add to your localisation:
In Steam\steamapps\common\BAKIN\data, make sure you've created your localisation folder (fr-fr, en-uk, etc). If you're localising the tool you've already done this.
Make a folder called advice inside of your folder.
Drop the contents of the zip attached here.

To test the changes, you can reinitialise the advice windows shown status through Bakin's settings before opening a project.

The contents of the assets belong to SmileBoom: https://smileboom.com/en/
