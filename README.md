# Springfield-AI

See Fred-AI for a full breakdown.

Copy and paste the entire Springfield_extension file into your extensions_custom.conf file. (/etc/asterisk/extensions_custom.conf) Place the Springfield sound file in (/var/lib/asterisk/sounds/en/). Then create a custom destination for it and give it a target of (Springfield,foo,1).

To do this in FreePBX, in the top menus, Admin –> Custom Destinations. In the Custom Destination dialog box paste (Springfield,foo,1). Give it a description, then press submit.

Now all you need to do is assign an inbound route or extension to the custom destination.
