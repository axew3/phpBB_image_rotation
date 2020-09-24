# phpBB attachments images rotation
For jpg/jpeg, gif and png attachments files
## Version 1.0.2-Dev 

Tested under 3.3.0> ( 3.2.0> should also work fine, but not tested ) ( 3.1.0> not tested )

## Install

Copy the "w3all" folder into phpBB/ext/

So you'll have: phpBB/ext/w3all/w3imagerotation

Set ACP option "Recompile stale style components" to yes

Go to "ACP" > "Customise" > "Extensions" and enable the "Attachments images rotation" extension

Test things may doing a test post

If all ok, reset "Recompile stale style components" to no

Done

## How do i can style the rotation popup?

It is the file rotate_popup.html, which you can find into:
/ext/w3all/imageattachrotation/styles/prosilver/template/event/rotate_popup.html
Note that you need to respect the DOM in this file, that start with a <style> tag 

<style> .... </style>
</head>
<body> .... </body>
</html>

If you edit this file, respect elements assets.


## Update/install: 

If updating, disable the old version and delete data into ACP Extensions Manager

Upload and copy or overwrite all files as above explained

Set ACP option "Recompile stale style components" to yes

Enable the Attachments images rotation extension

Test things may doing a test post

If all ok, reset "Recompile stale style components" to no

Done

## Missing older versions?
Are available here: https://www.axew3.com/w3/forums/viewtopic.php?p=4815#p4815

## License

[GPLv2](license.txt)
