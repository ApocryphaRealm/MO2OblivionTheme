# Changelog - Oblivion MO2 Theme

Versions are issued by the project's version gate. Written as the change happens (rule 61).

## 1.0.0 - 2026-10-02

First version. The owner: *"make an MO2 theme that matches the AMF Oblivion theme"*.

* The palette of Apocrypha Menu Framework for Oblivion Remastered's "Oblivion" theme, through the same stylesheet
  and graded tints as the five themes of 2026-09-26:
  * #E4DBCC parchment;
  * #2A1C12 ink text and #6F5D4C dim text;
  * #6B563F lines;
  * #8A6A2C brass accent;
  * #D2C3A6 separator rows over parchment mod rows.
* AMF's map-edge frame art, exported from AMF Oblivion's `tools\make_mapedge_frame.py`.
  * Its edges repeat rather than stretch; the texture is twice its design size (52 px slices).
  * It sits where the Njordlinger (Skyrim) MO2 theme puts its gold knotwork: round the list, tree and table views,
    the locked dialog, menus and tooltips, with the same 20 px and 17 px borders. The owner: *"Refer to the Skyrim
    theme for Mod Organizer 2 for where to place the gold knotwork"*.
  * The mod list is framed too (the owner: *"I want the left pane to have the knotwork too"*). Njordlinger leaves it
    unframed only because its knotwork's solid centre covered the rows; the map edge's centre is transparent, and MO2's
    conflict highlight stays visible.
  * Group boxes and tab panes get a plain ink line.
  * The builder gained `frame_slice`, `frame_mode` and `frame_places` in `theme.json` for this; the other themes keep
    26, stretch and their own places.
* The Oblivion shape:
  * buttons edged in brown ink with a gold thread inside;
  * a gold thread in a ticked check box;
  * the compass star as the selected radio mark.
* The Njordlinger icons recoloured to the theme's ink.
* Seen in MO2 2.5.2 on the Oblivion Remastered instance (2026-10-02): parchment panels, ink text, the map-edge frame
  tiled round the plugin pane, threaded buttons and check boxes.
