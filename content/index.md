# Table of Contents

<div style="background-color:red;padding:10px;text-align:center">
<div style="font-size:200%;font-weight:bold">WARNING</div>
<p style="font-weight:bold">This Bill of Materials is still under construction and has not been peer reviewed yet.</p>
<p>Although we are quite confident that the components are correct, there may still be major flaws. Use it at your own risk.</p>
</div>

<div class="toc"><ul>
  <li><a href="index.html">Introduction</a> &ndash; this page</li>
  <li><a href="rejuvenator-bom.html">The Bill of Material</a> &ndash; what you are probably here for</li>
  <li><a href="csv.html">CSV Export</a> &ndash; for Mouser Electronics</li>
  <li><a href="rejuvenator-bom.xlsx">Excel Export</a> &ndash; for your spreadsheet application</li>
  <li><a href="https://github.com/shred/rejuvenator-bom">GitHub Project Page</a> &ndash; feel free to contribute</li>
</ul></div>

# Introduction

This is the Bill of Material for a replica Amiga 1000 Rejuvenator. It is optimized for [joethezombie's Amiga 1000 Rejuvenator Re-creation Project](https://github.com/joethezombie/Amiga-1000-Rejuvenator).

## Read Me First!

If you want to build your own Rejuvenator, be aware that you are dealing with technology from the last century.

While almost all of the standard components are still available, some components are rare by now. You will need *all* of the listed components (except of those marked optional). We recommend that you try to get the components marked as <span class="rare">Rare</span> first, so you won't waste your money on standard components if you fail to get all the rare ones.

Also, installing the Rejuvenator into your Amiga 1000 is a very difficult process. Once you've done it, you definitely won't want to try again. We recommend to read the installation manual first (link see below).

## Rare Parts

* **RAM**: You can use any 44256 type DRAM with a 256Kx4 organization and an access time of 120ns or faster. You can use either 4 or 8 chips, for 512KB or 1MB of Chip RAM. If 4 chips are used, they are seated in U6, U8, U10, U12. An easy way to get them is to purchase a used Amiga 500 memory expansion with 4 chips. You can also reuse the OKI clock chip from that expansion.
* **OKI 6242B**: These chips can still be found as NOS part at online marketplaces. However, it's better to use a RTC72421A as replacement, and skip Y1, C21 and C24 (which is difficult to find). The RTC72421A also does not need calibration.
* **EPROM**: You can use 512KB x 16 bit EPROMs like AM27C400 or MX27C4100. They can still be found as NOS parts at online marketplaces. If the Kickstart image is 256KB big, duplicate it when burning it to a 512KB EPROM.
* **Agnus**: You will need a Fat Agnus in a PLCC-84 package.
* **Denise**: Can be reused from your Amiga 1000, or replaced with an ECS Denise.
* **Paula**: Can be reused from your Amiga 1000.
* **PAL 16L8**: They can be replaced with ATF16V8 GALs that are still in production.
* **PAL 20L8**: They can be replaced with ATF20V8 or ATF22V10 GALs. The ATF22V10 type is still in production. Adapted fusemaps for that type are provided.

## Assembly and Installation

* The fusemaps for the GALs [can be found here](https://github.com/joethezombie/Amiga-1000-Rejuvenator/tree/master/PLD/Rejuvenator).
* For assembly see the [original installation manual](http://amiga.resource.cx/manual/Rejuvenator.pdf).
* [See here](https://www.amigalove.com/viewtopic.php?t=749) about how to expand the Rejuvenator to 2MB of Chip RAM.

## Disclaimer

This is not an official list! It was collected and reviewed by Amiga enthusiasts.

Although we strive to make the information in this project as helpful and accurate as possible, it is provided "as is" and without warranties of any kind either expressed or implied.

In other words: You might spend a lot of money, and end up with a non-functioning board or a cardboard box full of useless components.

**Use at your own risk!**

## Contribute

This list is meant to be a community work. Our goal is to have a canonical list that people can rely on when ordering parts for building an own Rejuvenator board.

However, this list may not be free of errors. If you have found one, please [open an issue](https://github.com/shred/rejuvenator-bom/issues) or send a patch.

## License

This project is distributed under the terms of [GNU General Public License (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.en.html#content).
