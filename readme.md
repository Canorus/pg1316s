# mikefive, a Kailh PG1316S keyboard

Welcome to my repo about my mikefive keyboard! 

It's wireless and five millimeters thick. Here's a picture of it:

![](images/mikefive%20done2.jpg)

The keyboard above is completely custom-designed around Kailh PG1316S switches. 
These switches I got unexpectedly offered by Kailh when ordering other stuff in early 2024. 
I think this build sparked some ultra-low enthusiasm in the community as multiple shops are now carrying them. Go build! 

## Where are the files?!

Sorry. You won't find files or info to build the keyboard yourself here, yet. 

You will only find the ZMK config files for the custom shield, my current keymap, and a custom json for [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/). 
Most commits here will probably be me updating my keymap :)

Maybe I was a fool to show it to the world already, while I only built a single prototype. 
Because, like with most first prototypes, I found stuff that needs to be improved before other people start building. 
Next to that, another unexpected opportunity arose, which I will definitely scream from the rooftops about when it's more concrete...

## Devlog

Find all noteworthy project developments here. 

I will update this page when there is news, and post on r/ergomechkeyboards or r/olkb too.

### 2025-09-10 A new assembled keycaps STL files has been uploaded (by me, not approved by original owner)
Find [STL file](/files/custom-keycaps/PG1316S_keycap_normal_assembled\ v1.5.stl) under [keycap folder](/files/custom-keycaps/). Installed image uploaded [at](/images/assembled\ keycaps\ installed.jpg)

### 2025-02-24 I uploaded the keycap files!
You can now find the keycap STEP files in the [keycap folder](/files/custom-keycaps). Don't forget to read the readme in that folder.

### 2024-10-26 I made custom keycaps for the PG1316S switch!
You can read all about in this [Reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/1gcibfw/custom_keycaps_for_the_ultralow_kailh_pg1316s/), where I made a write-up in the comments if you would like to read about all the details. I resin-printed them myself. The CAD models will be on this site soon so everybody can print them, after I verified they also fit well using when ordering them from a commercial print service.

Small update: I received a small batch of my keycap prints from JLC, but they have more play to them than my own, and I don't want people to be disappointed when printing my caps. Tolerances are very small on this cap and switch combination. Stay tuned for updates! I am working on it.

![](images/mikefivekeycap%20flats.jpg)

### 2024-07-18 Introducing the even smaller PG1316M, 3D CAD also available!
I was informed by a Reddit member about the existence of the PG1316M. Yes, an M instead of an S at the end. This is a lower height switch, often used as Fn-row keys. I don't have a physical sample yet, but based on the keycap size in CAD, I think the keycap size will be around 16x12mm, compared to the 16x16mm PG1316S. I learned from Kailh, that these will also become available! Again, I am free to share the 3D CAD file, really awesome! You can also find the PDF spec sheet in the folder, as this M version does not seem to be on their website yet. I think I will soon add the KiCad footprint for the PG1316M as well!

![](images/PG1316SnMwcap.png)

### 2024-07-16 3D CAD file of PG1316S switch now available!
I received a lot of questions about the availability of a 3D CAD file of the switch and keycap of the PG1316S. Well, I asked Kailh if I could share, and I can! You can find it in the [files folder](/files). I also used the switch model to render images like below and select matching materials before I had the prototype produced. NOTE: This is the original 3D CAD file I received from Kailh. I noticed the switch dimensions are spot-on and the inside of the keycap is too but the outside of the keycap is too small. In reality, the keycap is 16.25mm vertically and 16.05mm horizontally.

![](images/mikefive%20Rendering%20Front.jpg)

### 2024-06-19 Lighter switches are installed!
I received the lighter prototype switches from Kailh and installed them in the mikefive. They feel much better and are a lot more quiet. I uploaded a small video update on [Reddit](https://www.reddit.com/r/olkb/comments/1djruze/new_lighter_kailh_pg1316s_switches_in_the_mikefive/). I am planning on making an extensive video update soon, with much more news to share!

### 2024-05-26 KiCad footprint now available!
I received a message from someone that was able to order some switches, and asked if I could share the footprint. The KiCad 8.0 footprint is in the [files folder](/files), and looks like this:

![](images/PG1316S_footprint_mikeholscher.png)

Some explanation:
- The outer, biggest square is the 16x16mm keycap.
- The slighty smaller square is the switch 'frame' size.
- The two small circles are holes for the allignment pins on the switch.
- Pads 1 and 2 are the switch pads.
- Pads 3 are the SMD mounting points for the switch frame. NOTE: I placed vias in these pads in the PCB to give the switch a more secure connection to the PCB. (I hope) this way the switch connects to both sides of the PCB instead of only the top layer. I connected all pads 3 to GND in the switch diagram and schematic.
- The weird shape in the top half is the available space under the switch for components. I placed my diodes there in the mikefive.

Kailh also made a [product page](https://www.kailhswitch.com/mechanical-keyboard-switches/kailh-ultra-thin-notebook-switch.html) for the PG1316S switch, including [spec sheet](https://www.kailhswitch.com/uploads/15927/files/CPG1316S01D02-data-sheet.pdf?rnd=569) where I based the footprint on. I did some further measurements on the physical switch to complete some details such as the space underneath.

### 2024-05-06 kbd.news reposted!
kbd.news was kind enough to [repost](https://kbd.news/Mikefive-a-Kailh-PG1316S-keyboard-2366.html) my Reddit post on their website!


### 2024-04-28 Hello world :)
After completing the build on Wednesday 24th of April and working with it for a couple days, I decided to make a [post](https://www.reddit.com/r/ErgoMechKeyboards/comments/1cfg3vr/mikefive_a_kailh_pg1316_keyboard/) on r/ergomechkeyboards. 
It became a really long write-up, as I wanted to share as many details as possible.
Thank you all for your flattering replies! They really gave me energy to continue the project and make sure the keyboard will eventually get in the hands of people that want it.

