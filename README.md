## The Unofficial Homestuck Collection

Homepage: <https://homestuck.giovanh.com/unofficial-homestuck-collection/>

The *Unofficial Homestuck Collection* is a fan-created Browser for reading the webcomic *Homestuck* and other works by Andrew Hussie as they were originally intended to be experienced with Flash integration along with a number of other features. The unofficial Homestuck collection must be paired with an external "Asset Pack" to function that can be downloaded [here](https://cdn.beyondcanon.com/uhc/assets.zip).

This repository is a fork of the original [Unofficial Homestuck Collection](https://github.com/GiovanH/unofficial-homestuck-collection) that is maintained and operated by *Homestuck, Inc.* to ensure its preservation and continued availability while a new "Official" Homestuck Collection is in development. Any future 'official' support or updates to the UHC will be made here.

## About the Codebase

The Unofficial Homestuck Collection is an open source project built using Electron and Vue under the [GNU General Public License](https://www.gnu.org/licenses). You are free to fork and modify the code, as well as suggest changes to be made to it here. 

## Some details on the codebase

This application runs entirely in Electron + Vue, with very little else going on. Although it functions in a manner very similar to a web browser, everything is running in what I would charitably describe as a "creative" fashion. I am by no means an expert, and while I'd love to say I always had good practices in mind while developing this, I largely didn't even know what a good practice *was* for a decent chunk of it.

So what I'm saying is this: You're welcome to peruse the codebase, fork it, make and suggest changes, or use it in any way you see fit. Just uh... don't expect it to be well formed or documented in any of the ways that really count. If you want to make some changes and my code is causing you physical discomfort, [try asking around our Discord server.](https://discord.gg/43QHASFC2X) Someone should be able to help out!

Building a development version of TUHC requires NPM (Node 14.18), Yarn, `make`, and `tar`.

- NPM is the node package manager, used for developing with Node.js.
- [Yarn](https://www.npmjs.com/package/yarn) is a npm-like package manager that is itself distributed as an NPM package.
- [`tar`](http://gnuwin32.sourceforge.net/packages/gtar.htm) and [`make`](https://www.gnu.org/software/make/) are basic GNU utilities used extremely commonly in software development. `tar` is used to pack files (like zip) and `make` is used to build projects with dependencies. If you don't already have them on your system (you can maintain robust CLI environments using tools like [cygwin](https://www.cygwin.com) or [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)), you can download [`tar`](http://gnuwin32.sourceforge.net/packages/gtar.htm) and [`make`](https://www.gnu.org/software/make/) individually directly from GNU.
  
### Compiles and hot-reloads for development

```
make test
```

## Credits

The Unofficial Homestuck Collection was created by [Bambosh](https://bambosh.dev) and is currently maintained by [GiovanH](https://im.giovanh.com).
[A lot of people](https://github.com/GiovanH/unofficial-homestuck-collection/graphs/contributors) have contributed to the success of this project and I am deeply grateful to all of them. 
A full list of contributors and thanks can be found in the program itself under the Credits page.

## Legal

<pre>The Unofficial Homestuck Collection
Copyright (C) 2025 GiovanH

This program is free software: you can redistribute it and/or modify
it under the terms of the <a href="https://www.gnu.org/licenses">GNU General Public License</a> as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; 
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  
If not, see https://www.gnu.org/licenses/.

Portions of this program may contain material subject to copyright and not subject to the 
GNU General Public License, including the copyrights associated with the properties owned 
and distributed by Homestuck, Inc. and Andrew Hussie.
</pre>

---

In (non legally-binding) summary, you may freely use and distribute the software, as well as modify it and distribute your changes and modified versions, so long as you do not restrict the rights of others to do the same. You must clearly notate any changes and provide links to the unmodified original, and not remove credits (which are part of the original copyright). The Homestuck webcomic and associated copyrights are not subject to the rights granted under this license, and may be subject to takedown, enforcement, or modification by Homestuck, Inc.

As per section 7, the author attributions in Credits.vue must be preserved in all covered works. Modified versions may optionally extend this list as applicable, but modifications that remove attributions or otherwise misrepresent the origin of the material are not permitted.
