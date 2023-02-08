# hyprland-void

**NOTICE**: due to getting cancelled from void-linux entirely, I no
longer have any motivation to maintain this port.

Despite using this distribution for years, it is unfortunate to admit
this thing is not worth my time anymore.

The repository will be available until March of 2023.

Consider cloning it and maintaining the package yourself.

---

The repository contains port of [Hyprland](https://hyprland.org/)
(wayland compositor based on wlroots) for
[Void Linux](https://voidlinux.org).

Tested briefly on a virtual machine (QEMU).

I do not use wayland myself, so you are free to test it as you see fit.

If you encounter any problems and believe the template is to blame,
feel free to open an issue or pull request.

## Installation

Clone this repository and put the `srcpkgs` directory into your local
copy of [void-packages](https://github.com/void-linux/void-packages).

Refer to `xbps-src`'s instructions for building and installing packages
locally.

Follow Void's [documentation](https://docs.voidlinux.org/config/graphical-session/wayland.html)
to set up environment for wayland compositors properly.

Do not forget to follow the [upstream tutorial](https://wiki.hyprland.org/Getting-Started/Master-Tutorial),
too.

## Why not just submit it to void-packages?

Hyprland will not be accepted into the repository, this I can guarantee.

See <https://github.com/void-linux/void-packages/issues/37544>.

If you believe the link above is not convincing enough for you, have a
look at IRC logs below:

From **#voidlinux**:

> 23:11 vuldo         | Hello

> 23:11 vuldo         | Have you guys tried hyprland on void?

> 23:12 vuldo         | I am looking at the screenshots and it looks so pretty 😍

> 23:12 vuldo         | I wonder if it will work well

> 23:13 abby          | upstream is also hostile to making it packageable

> 23:14 paper_        | and development version of wlroots

---

> 15:55 sozuba        | Does anyone use or have a template for hyprland. I read the issue for why Hyprland wm wouldn't officially part of void anytime soon. I am wondering if someone has already a template. I have made a template, but very reluctant to use it. I am sure it has so much issues. 😁

> 16:13 paper_        | apeaking of hyprland, packages with hostile upstreams will also have hars time getting to void

> 16:16 sozuba        | paper_:  I agree, i read th issues mentioned regard wlroots and how upstream has a completely different view. ;)

> 16:55 kruceter      | paper_: does this "hostility" has anything to do with that micro-drama on discord? Thank you.

> 17:53 paper_        | kruceter: if you mean what I mean, then that is a reason why some people might not want to dedicate their free time to merging it even if the technical issues are adressed

> 17:54 paper_        | I was talking more about their hostility towards packaging

---

From **#xbps**:

> 04:58 ahesford      | what is with the boom in interest in hyprland

> 04:59 Nilium        | Never heard of it before. Looks like a typical tiling WM with animations?

> 05:00 ahesford      | yeah, except the author is unreasonably hostile to distribution packaging and apparently also of poor or questionable character

> 05:01 sam_          | oh dear.

> 05:02 q66           | what did they do

> 05:02 sam_          | yeah im out of the loop here

> 05:02 Nilium        | More or less hostile than kitty's author?

> 05:02 q66           | what did kitty's author do

> 05:03 ahesford      | I've only heard secondhand reports about the hyprland author

> 05:03 Nilium        | Just very abrasive if anyone opens any issue on the project

> 10:06 paper_        | sam_, q66: some weird technical decisions: https://github.com/hyprwm/Hyprland/issues/302, the maintainers act immaturely, so it's very frustrating for anyone to communicate with them and they are of course transphobic: https://fosstodon.org/@TheEvilSkeleton/109587658504727925

> 10:09 fossy         | from that gh thread "Unless Kainoa fucked up the pkgbuild again in which case I'll have him prosecuted for violating the geneva convention" -- this person sounds a bit unstable

> 10:12 fossy         | this seems like more "my software exists in a vaccum and that's the only place i care about it" which means that your program is a pain for anyone to use so you never get adoption lol

> 10:14 abby          | some or all of the maintainers appear to be kids

> 10:14 abby          | teens

> 10:14 aedinius      | agist

> 10:15 aedinius      | ageist?

> 10:15 aedinius      | hunspell save me

> 10:15 sam_          | paper_: thanks for sharing

> 10:15 sam_          | jeez
