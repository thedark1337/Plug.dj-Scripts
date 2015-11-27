# Plug.dj-Scripts
> Misc. Utility Scripts for Plug.dj

### Info

Note that as of september 28th 2015  [plug.dj][plugdj-url] has shut down. This is here as a legacy repository, however the scripts may be adapted to work for other alternate sites as long as licensing is followed. I have also shut down plug2youtube. Thank you to all the users of  [plug.dj][plugdj-url].

The script media2file.js supports converting a playlist from [plug.dj][plugdj-url] to a text file in the format of:

```
 Smash Mouth - I'm A Believer https://youtube.com/watch?v=0mYBSayCsH0
 thedark1337 - First Track (WIP) https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/75136737
```

The script plug2youtube.js supports converting a playlist from [plug.dj][plugdj-url] to a modal popup that can then be used to convert it to a YouTube playlist via Plug2Youtube.

### Usage

Add the one you want to use to the URL for bookmarks.

> Media2File:

```javascript
javascript:(function(){$.getScript('https://scripts.thedark1337.com/media2file.min.js');}());
```

> Plug2Youtube:

```javascript
javascript:(function(){$.getScript('https://scripts.thedark1337.com/plug2youtube.min.js');}());
```

### License
Copyright &copy; 2015 Thedark1337 and other contributors

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see http://www.gnu.org/licenses/.

[plugdj-url]: https://plug.dj
