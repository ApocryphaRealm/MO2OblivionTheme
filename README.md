# Oblivion MO2 Theme

A Mod Organizer 2 theme in the look of Apocrypha Menu Framework for Oblivion Remastered's default theme, "Oblivion":
parchment panels, brown ink text and lines, a brass accent, and an embroidered map's edge in gold and brown round the
panels. That edge is a couched gold cord, a compass star in a stitched ring at each corner and a brown running stitch.

Separators and mods are coloured separately (separators are the mod list's parent rows; MO2's conflict highlight on
mods stays visible). The map-edge frame sits round panels and group boxes, tiled along each side so the stitches keep
their size. Buttons are edged in brown ink with a fine gold thread inside, ticked check boxes take the gold thread, and
a selected radio button shows the map edge's compass star. The toolbar and MO2's small buttons carry the Njordlinger
icon set in the theme's ink colour.

## Install

Extract into your Mod Organizer 2 folder (the one with ModOrganizer.exe) so `stylesheets\Oblivion.qss` and the
`stylesheets\Oblivion\` folder land in MO2's own `stylesheets` folder, then pick **Oblivion** in Settings > General >
Style. Restart MO2 once so the toolbar picks up the icons.

## Building

`python tools\build_theme.py` (Python 3 with Pillow) writes `stylesheets\` from `src\theme.qss.in`, `src\theme.json`
(the palette), the art in `src\` and the icons in `src\icons\`.

Licence: GPL-3.0-or-later (`LICENSE`, `NOTICE.md`).
