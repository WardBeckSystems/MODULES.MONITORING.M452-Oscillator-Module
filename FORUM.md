# M452 — Oscillator Module: on the WBSps forum

What owners, technicians and Ward-Beck people said about the M452 on the WBSps.ca forum (Simple Machines), 2006|39 to 2013|46: 8 topics, oldest first. Quoted as posted (contact details taken out). Made by tools/forum_quotes.py from the forum's database backups.

## how much does this thing weigh?

_WBS INFO · Jun 16, 2006|39_

> No problem! I can get you a copy. Its a nice book they put together the day after my birthday, June 19th, 1980. Basically its an analysis of what Ward Beck thought the TV station needed, and how much it'd cost them. Included with the booklet (which looks like a junior high yearbook) is all the schematics of the console. I also have a huge packet of schematics of the console, from one HUGE drawing as big as the board done to scale, down to each individual module. The last ward beck was thrown away, right into the dumpster about 4 yrs ago (they then installed a Wheatstone, very nice) and they let me take this model, L3242 for television audio production. Its got:
>
> 32-M470
>
> 2-M498
>
> 4-M477
>
> 2-Aux mix output groups using 1 M479
>
> 4-M475
>
> 1-M451
>
> 1-M452
>
> 1-M453A
>
> 3-M462 EQ's patchable
>
> 7-VU meters
>
> 2-M625 
>
> All penny and giles faders. 
>
> Its setup to have EQ on all 32 channels, but the station cheaped out and only got 3 patchable EQ's . . . 
>
> Thanks for the advice on the weight. We pulled all the main modules, power supply, and under cariage off the beast. and we have a dolly . . . should be ok.

— **Tommy P**, Jun 17, 2006|39

## Ebay auction: this makes me laugh

_WBS INFO · Jun 17, 2006|39_

> http://cgi.ebay.com/15-Ward-Beck-Manuals-Parts-List-Schematics-M462-M466_W0QQitemZ9742581675QQihZ008QQcategoryZ23785QQssPageNameZWDVWQQrdZ1QQcmdZViewItem
>
> BUY NOW $119!!
>
> Manual Model Numbers Included Are: 
> M462 & M462B Equalizer Module, M632 & M632A Power Supply, M451 Talkback Module, 
> M466 Compressor, M450B Program Amplifier, M484 Schematic Only, 
> M703B Intercom Pre and Output Amplifier, M453A Cue Amplifier, 
> M452 Oscillator Module, M464 HP/LP Filter, & General 7000B series.
>
> just so you all know, most of the manuls he lists are on the site already. I'm still in the porocess of converting the rest to PDF

— **kuzub**, Jun 17, 2006|39

## Ward Beck mixer parts for sale!!! Constantly updating, today's date: 11/15/06

_WBS PARTS FOR SALE · Sep 8, 2006|39_

> Have a bunch of unneeded modules for my board. If you are looking for an extra, here is the list.
>
> MIXER MODULES
> Full Channel length
> M529 Channel Strip seems to be a Master module type with gooseneck for talkback mic. comes with odd other channel strip with no model number $100
> M460B Channel Strip Mic Pre with 3 band eq parametric with adjustable Q on mid $200 Twenty 
> M463B Submaster module with 3 band eq parametric with adjustable Q on mid $135 Twenty
>
> Half-size modules Eq's Filters
> M457 4 x 2 Pre-Mixer $100 Ten available
> M464 Hp/Lp filter $50 Ten available
>
> M468L Selector Module $10 Plenty
> M468M Selector Module $10 Plenty
> M468AP Selector Module $15
> M459A Switching module $15 Five available
> M454Switching module $
>
> M452 Oscillator-Test Tone Generator $30
> M453 $20 Two available
> M453A Cue Amplifier $20
> M455 Aux Return Module $25
>
> AUDIO BOARDS/CARDS
> Looking to recap your board and not be down!
> M450 Line Amplifier $15 Plenty
> M450B Program - Summing Amplifier $15 Plenty
> M701B $15 Plenty
> M703B $15 Plenty
> M712B $15 Plenty
> M809 $15 Plenty
>
> Penny & Giles Faders Model 1550 $15 Fifty available
> VU Meters From meter bridge (Large) $40 Twelve available
>
> POWER SUPPLIES
> M625A $100 Two available
> M625B $100 Three available
> M666 $100 Two available
>
> M610 $40
> M604 $40
> M624 $50 Five available
> M612 $40
> M608A $40
> M648 $50 Four available
>
> M621 $60 Three available
> M632 $60 Three available
>
> Please email me with any inquiries, cserig (at symbol) gmail.com

— **Christian**, Sep 8, 2006|39

## CALIBRATION, where am I going wrong??

_WBS TECHNICAL SUPPORT · Jul 26, 2009|42_

> I'm working on calibrating my console right now to operate at +4 I have a few questions and I think I'm doing something wrong please help me if you can!
>
> 1. to generate the tone I'm using the on board 1khz M452 module. I've got two outputs that I've lined up. 0dB is 0.775 V between the ground and the hot +4dB is 1.225V between the ground and the hot.
>
> 2. I patch the 0dB tone into the Line input of the M470A channel. I meter the Insert send and adjust the gain knob until i get a reading of 0.775V
>
> 3. I leave the tone in the line in meter the direct out. I adjust the fader until I get .775V
> Q: Have I achieved unity on the channel? signal in = signal out?
>
> 4. I meter the insert send of the master module. I adjust the summing amp input (M477 R7) until the meter reads 0.775V
>
> 5. After the insert point on my master fader there is a 15dB pad network then a potentiometer. 
> Q: If the 15dB pad is compensating for the fader, am I to assume the pot should be up full?
>
> 6. I have modified R15 on the 8.109E Booster amp to a variable pot so I can adjust the output. 
>
> 7. I meter the output of the master module, and adjust this R15 until I get 0.775V
>
> so, every stage of the console is the same.
>
> I removed the PPM meters from the console and put in VU meters on M1 and M2, to do this I had to remove a Pad on the back. Then I changed the resistors on the VU meter to align them to 0vu once the master outputs were 0.775 V
>
> where am I goign wrong? I've been chasing my tail for weeks on this

— **kuzub**, Jul 26, 2009|42

> Figured this one out in my sleep. the insert send is not a break point on my patchbay it's a split, so the tone goes to the meter and to the insert return... so when i get back I'm going to try putting a loose cable into the insert return and see what that does.
>
> Also, I've given up on the M452 OSC, its a funny beast and the tone is not the right frequency... and going in between tones the voltage changes A LOT... so I broke out the BK tone gen and added an Isolation transformer... so now I think I'm wrong about where I'm measuring my voltages. I can't get a straight answer about it... but could someone confirm that +4dBm is 1.225 when measuring VAC across the tip and the ring of the tone gen? this seems to be the case, but dont want to do anymore until i have that confirmed. 
>
> My studer has a tone gen, it measure 1.256 (ish) across a few channels between tip and ring. and when i plug that into the pod 22 meter, it's at 0dBVU... so I'm sure it's right... 
>
> bye for now

— **kuzub**, Jul 27, 2009|42

## WBS L2042 console value?, figuring out model numbers

_WBS INFO · Sep 17, 2009|42_

> Hi,
>
> New member here.
>
> I have a chance to pickup what I suspect is a 802 or 1202, but I think I would be happier with something like a 16-channel and 4 to 8 buss, like my current console.
>
> Seems like an L2042 would be nice. However, I am trying to get a gauge of what one would cost and am coming up without any indicators searching the web.
>
> So I used the used prices link on this site and (using the L2042 configuration) came up with an amount for the cost of the pieces:
>
> 20 M470 Input Modules 5000
> 20 M472 State Variable Equalizers 1500
> 20 P&G faders 500
> 4 M473 Submaster Modules with P&G fader 100
> 2 M477 Master Modules 100
> 2 M479 Aux Modules 50
> 1 PFL Mixing Buss with M453 Cue Amp 25
> 1 Solo Mixing Buss
> 3 M475 Monitor Modules with M478A 8x1 Selector Module 25
> 1 M452 Oscillator Module 10
> 1 M451 Talkback/Slating Module 25
> 7 VU meters 175
> 2 M625A Console PSUs 200
> 1 M624 Console PSU (lamp, relay, tally) 100
>
> TOTAL 7810
>
> Does $8k sound about right for a whole console like a 2042? More? What would they typically go for? Or one with similar specs?
>
> Another question: I see reference to model numbers that don't make the most sense to me. For example, 73065 is a 32x16. I understand the "73", which looks to indicate the year of manufacture, but how does the 065 indicate the 32x16 configuration? Do the last three numbers just indicate the amount of WBS consoles produced for that particular year?
>
> Thanks,
> Chris

— **fazeka**, Sep 17, 2009|42

## GARAGE SALE - M452 - Tone Generators

_WBS PARTS FOR SALE · Apr 5, 2011|44_

> M452 - Tone Generators
>
> great for parts if you have an L series. if you have any broken switch on your auxs, or master modules you can scavenge parts from these modules 
>
> $20 each or two for $30
>
> Terms of Garage sale:
>
> - First post "SOLD" gets first serve or make me an offer
> - sold as is. No implied warranty (if you want it tested and restored I'll do it for triple the Garage sale price)
> - Buyer pays actual shipping costs + a $15 handling / packing fee
> - can combine shipping
> - payment via interac bank transfer, if you want to use paypal add 2%
> - anything you buy here comes with support from the forum, so if you have questions, problems and project design ideas we'll all help you out.

— **kuzub**, Apr 5, 2011|44

![M452 - Tone Generators.jpg](PHOTOS/FORUM/2011%20-%20forum%20726%20-%20M452%20-%20Tone%20Generators.jpg)

## need schematics for 461,462(also a and b) and 466

_WBS TECHNICAL SUPPORT · Aug 15, 2011|44_

> sorry for the delays
>
>  do not have a scanned copy of the M461 yet or the M462A... I know I have them somewhere
> no M468V
>
> but here is what you're looking for
>
> M451:
> http://wbsps.ca/PDFs/Ward-Beck%20Systems%20-%20M451%20Talkback%20Module%20-%20www.WBSps.ca.pdf
>
> M452:
> http://wbsps.ca/PDFs/Ward-Beck%20Systems%20-%20M452%20Oscillator%20Module%20-%20www.WBSps.ca.pdf
>
> M462B:
> http://wbsps.ca/PDFs/Ward-Beck%20Systems%20-%20M462B%20EQ%20Module%20-%20www.WBSps.ca.pdf
>
> M466:
> http://wbsps.ca/PDFs/Ward-Beck%20Systems%20-%20M466%20Compressor%20-%20Limiter%20-%20www.WBSps.ca.pdf

— **kuzub**, Aug 15, 2011|44

## 1982 WBS Frame restoration and customization: Project started October 2011

_MY WBS CONSOLE · Nov 12, 2013|46_

> 1982 WBS Frame restoration and customization
>
> Ward Beck Systems
>
> Model #: 810721
> Serial #: 8205034
>
> I came across a frame in July or August 2011. Someone was selling it on the WBSps facebook page. It took about 3 months to get to the right "moment" for pick up and everything. 
>
> What was included with this frame was:
>
> 1x WBS frame
> 3x 5x20 Patch Bays
> 12x M468K bussing modules
> 26x Penny & Giles faders
> 1x Phantom Power/Talkback Mic module
> 1x M452 Oscillator module
> 4x M451 Slate/Talkback module
> 2x M453A Cue Amp module
> 2x M498A Selector module
> 4x M625 PSU
> 2x M648 PSU
> 3x M624 PSU
> 8x M605 Distribution Amp
> 4x M612 Distribution Amp

— **pawajari**, Nov 12, 2013|46

_Serial Number.jpg_
_not kept: the file is not in the forum backups_
