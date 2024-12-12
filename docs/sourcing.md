Heyo!

A :b:epis motherboard needs some parts! Namely, a Pi Zero, a display, a Blackberry keyboard, and a battery.

## Screens

There are a few screen options expected to work with this revision with no hardware mods.

- Sharp LS027B7DH01 (or LS027B7DH01A) - 400x240 monochrome transflexive LCD (Amazon/Aliexpress/eBay, is also sold on breakouts from Adafruit)
-- can also check [Octopart](https://octopart.com/ls027b7dh01-sharp-18121932) and see if it's available on Digikey or such
- ILI9341 18-pin 2.4" display panel - 320x400 colour LCD, with touch panel option
-- we have a touch panel driver connected to PiZero's I2C on the :b:epis, and it's supported by the Linux kernel!
-- two reference listings: [one](https://de.aliexpress.com/item/32794392693.html) [two](https://de.aliexpress.com/item/32861524235.html)
- ST7789 18-pin 2.4" display panel - 320x400 colour LCD, IPS (higher viewing angles and better colours)
-- reference listing: [one](https://de.aliexpress.com/item/1005005998013197.html)
-- not known if it's well-supported by the Linux kernel yet

## Pi Zero

Zero W or Zero 2 W, we'll use the latter. [https://rpilocator.com/](https://rpilocator.com/) can help you find one near you!

## Keyboard

Blackberry Q20 replacement keyboard. There's a few on eBay/Amazon/Aliexpress, but please, first check for them locally in your country! You'll likely get a better deal, and, it's better if you leave the more global sources as a backup option, so that everyone has a shot at getting a keyboard.

Here's [a link](https://www.ebay.com/itm/405153457651) (now out-of-stock) as a reference for "what exactly you need to get".

You can also buy a cheap/broken Blackberry Q20 and take it apart for its keyboard. In fact, that might be the cheapest possible option
for you - so, do check!

## Battery

Has to have a JST-PH two-pin connector, more than 2000mAh preferred, dimensions should be somewhere on Beepy discord. We're planning for custom batteries now but will be looking for OG-beepy-sized cells in the future, for now, we'll be going for some 4000mAh ones from Amazon, they don't quite fit, but they're alright. We don't yet have a solid recommendation here, but we'll keep you posted - if you're struggling picking a battery, contact us!
