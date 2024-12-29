<div align="center">

  # Orion
  
  
  𝖳𝗁𝖾 𝗈𝗇𝖾 𝖺𝗇𝖽 𝗈𝗇𝗅𝗒 𝖣𝖫𝖢 𝖴𝗇𝗅𝗈𝖼𝗄𝖾𝗋 **𝖿𝗈𝗋 𝗆𝖺𝖼𝖮𝖲**, 𝗃𝗎𝗌𝗍 𝗅𝗂𝗄𝖾 𝗍𝗁𝖾 𝗂𝗇𝖿𝖺𝗆𝗈𝗎𝗌 𝗈𝗇𝖾 𝖻𝗒 𝖺𝗇𝖺𝖽𝗂𝗎𝗌.<br>
  𝖠𝗉𝗉𝗅𝖾 𝗌𝗂𝗅𝗂𝖼𝗈𝗇 𝖿𝗂𝗋𝗌𝗍-𝖼𝗅𝖺𝗌𝗌 𝖼𝗂𝗍𝗂𝗓𝖾𝗇; 𝗅𝗂𝗀𝗁𝗍𝗐𝖾𝗂𝗀𝗁𝗍 𝖺𝗇𝖽 𝖾𝖺𝗌𝗒. 𝖨𝗇𝖼𝗅𝗎𝖽𝖾𝗌 𝖺𝗎𝗍𝗈-𝗅𝗈𝗀𝗂𝗇 𝗍𝗈𝗈!

</div>

#### Well how do I use it then?

Just go to **→ Releases**, grab the latest one, run it. You're all set!
To use online features, use the app icon in the menu bar (you'll instantly recognize it) and click on it.
You'll figure it out from there!



### Troubleshooting

<details>
   <summary>Cannot launch, App is damaged</summary>

   > One of these should probably do it:
   > ```bash
   > sudo xattr -rc "Orion.app"
   > ```
   > ..or:
   > ```bash
   > sudo xcode-select --install
   > codesign --force --deep --sign - "Orion.app"
   > ```

</details>

<details>
   <summary>Where da source at??</summary>

   > Will come at a later date (for good reasons, I promise), for now you either
   >
   > a. find somebody who can inspect the compiled code and vet it for you
   >
   > b. learn to examine the compiled code and vet it yourself
   >
   > c. trust it blidnly
   >
   > I've no intention to spread malware; releases aren't obfustacted and are "readable" by those with the necessary expertise. The app doesn't even go to github for update checks, only some **official** online services, had you chosen to use them.
   >
   > Once a good strategy for pusing the source arises, I'll pursue it.
     Releasing it in its current state will likely bring total chaos to the lovely 🏴‍☠️ world as we know it. Trust me, you don't want that either.


</details>


<details>
   <summary>This seems to be developed around that one specific part four of a specific game. Can this work on other games?</summary>

   > *Short answer:* probably; somebody tested it with the third installment (without online, of course) - but nothing else. 
   >
   > Were there any other Mac releases? Good thing is you can test it and report back!

</details>

<details>
   <summary>Launching the game w/ online, I get <b>"'The World Of Borat 4' would like to access data from other apps."</b>. What the heck?</summary>

   > **Short answer:** **if** you want gallery avatars - just click **"Yes"** each time. Yes, it can be annoying. I know, I know.
   
   > **Long and boring answer:** Game really-really wants to fetch avatars and other images for Gallery thru this tool.
   > But this tool is "sandboxed" - meaning macOS won't give it access to any other app whatsoever - as a security measure.
   > Unfortunately, it means that these images from the Gallery must be stored inside Orion's directory, and *The Game 4* will have to get there.
   > 
   > That's what that prompt means - *The Game 4* will go to Orion's directory and get those images from there, and you'll have to allow it first.
   > 
   > For what it's worth, the same happens when you run the tool made by 𝖺𝗇𝖺𝖽𝗂𝗎𝗌 on your Mac.
   > 
   > Also if you don't want to see avatars of people in the Gallery - just say **"No"** to that prompt. Easy!
  
</details>

<details>
   <summary>Some DLCs are missing!</summary>

   > Open Settings via the icon in the menu bar, drag and drop the config file into there - if it's good - the tool updates and you've just unlocked nirvana.
   >  <details>
   >    <summary>What config file?!</summary>
   >        Configs by 𝖺𝗇𝖺𝖽𝗂𝗎𝗌 work <i>just fine</i>. If you don't have one - open a ticket and I'll update the app.
   >  </details>


</details>
