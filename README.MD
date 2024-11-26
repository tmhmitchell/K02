<p float="left">
  <img src="/other/img/logo.svg" width="20%" /> 
</p>

**Less, but better.** - Dieter Rams

After seeing the [Ferris Sweep](https://github.com/davidphilipbarr/Sweep) for the first time I've fallen in love, but as a designer I cannot accept the things the way they are. So I've done some experimentation with it.

I changed the overall form of the board so it can be a little bit more compact and be a canvas for expression in the matter of case design. For example, you can do a case inspired in the [totem](https://github.com/GEIGEIGEIST/TOTEM) or in the [stront](https://github.com/zzeneg/stront) aesthethic.

With this redesign I've taken every milimiter into account. As so the acrylic case released with the `TRRS` version counts with 2 versions, the full version adds 2mm to the board height, and the lite version adds 0mm.

This is a parcial redesign of the [Ferris Sweep 2 half-swept](https://github.com/davidphilipbarr/Sweep). In other words this is a:

- 34 keys.
- Diodeless.
- Low profile.
- Non-hotswap.
- Reversible PCB.
- Column staggered.
- Wireless and wired capable.
- Choc MBK spaced (17,5mm x 16,5mm).
- Cheaper than the [cheapino](https://github.com/tompi/cheapino) (at the time of the build).

### What have been done:

- Change PCB overall form.
- Add support screw holes.
- Add teardrop on solder joints.
- Reposition of the reset and power switch.
- Create an alternative version with `USB-C` instead of `TRRS`.
- Add commissioned art by the brazilian artist [Aline Dal Pont](https://www.instagram.com/manifesto.efemero/).
- Remove all the informative silk graphics for a better looking board.

### What I plan on doing:

- Do an extensive and compreensive assembly manual.
- Design some _minimalist_ and _low profile_ [cases](/TRRS/Case/).

### What I may do<sup>1<sup>:

- Create an 36 keys pcb with breakpoints.
- Change the power switch to something better build. _I accept suggestions_.
- Add a variation with choc spacing for [CFX keycaps](https://kbd.news/CFX-keycap-1553.html) (16,5mm x 16,5mm).

> <sup>1</sup> The main reason for not doing this at the moment is the lack of motivation. As I have to pay for every prototype test and take time off to do the development and iterations I have to be mindful of the tasks I take.

## Versions

At the moment this repo contains 2 versions, one with `TRRS` and one with `USB-C` connecting the halves. In the community the TRRS connectors are not praised, due to causing problems when unpluged with the board powered on. The `USB-C` if not wired correctly may introduce some [risk of being connected directly to a power supply](https://docs.qmk.fm/features/split_keyboard) by mistake. I've done the bare minimum, just wired the `GND` and `VCC` following the USB protocol. Even with this [it's not recommend to do it](https://github.com/zmkfirmware/zmk/issues/1110#issuecomment-2395179298).

The [gerber files are in the release section.](https://github.com/anothermimich/K02/releases)
The list of materials for each version are inside of the respective folder.

## Silk art

I commissioned the work of the brazilian artist [Aline Dal Pont](https://www.instagram.com/manifesto.efemero/) for this board. You can remove the work completely or leave it as it is with the credits. You cannot use the work outside of this board or modify it in any way without the express autorization of the artist.

## Firmware

As this redesign had only touched on aesthetic aspects, you can use the firmware from the [Ferris Sweep](https://github.com/davidphilipbarr/Sweep).

## Disclaimer

The files in this repo may contain problems, use them at your own risk.

For the type nerds (like me), the text on the PCB and logo are [FuturaRenner](https://www.fontsquirrel.com/fonts/futura-renner) aka [Formera](https://github.com/noirblancrouge/Formera).

The team behind the design of the incredible [Ferris Sweep](https://github.com/davidphilipbarr/Sweep) are: [Pierre Chevalier](https://github.com/pierrechevalier83), [David Barr](https://github.com/davidphilipbarr), [Ibnu Daru Aji](https://github.com/ibnuda/), [Duccio](https://github.com/duckyb). Without their work this parcial redesign would not be possible.
