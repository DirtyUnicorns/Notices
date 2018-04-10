# How to add to our font pack #

If you're contributing a font to DU, make sure the font is either freeware, shareware, demo versions or public domain. Do 
not contribute a paid font or anything that will likely get us in trouble with the author of said font(s).

If you're using it for personal use, do you. We're not responsible for your actions.

Once you found the font you want to use, simply rename the font to something without spaces. For example if a font is 
called 'Ubuntu Cool Font', you will have to rename it to 'Ubuntu-Cool-Font'. It just makes things easier this way.

Now that you have the font name and your font, make sure is a .ttf format and not any other type.

Now open up the fonts.xml included here and replace 'FONT-NAME.ttf' with your font name. If you're wanting to include 
variants of your font, simply copy and paste ```<font weight="400" style="normal">FONT-NAME.ttf</font>``` and place it underneath the sans-serif array. 

Finally grab both the fonts.xml and the font and zip it up. In Linux, you can just select both the fonts.xml and your 
fonts and just right click to compress. In Windows, you can use something like WinRAR.

If you're wanting to contribute this font, simply move the font to ```/SOURCE/vendor/du/themes/Fonts/assets/fonts``` and 
commit, push to gerrit for review

```bash
cd SOURCE/vendor/du
git add .
git commit -a
git push ssh://USERNAME@gerrit.dirtyunicorns.com:29418/PROJECT HEAD:refs/for/BRANCH
```

If you're wanting to use it for personal use, you'll have to place it in the same location as above, compile it and then 
push the apk to ```system/app/DU-Fonts/```
