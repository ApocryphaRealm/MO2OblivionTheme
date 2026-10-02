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
* AMF's map-edge frame art round group boxes and tab panes, exported from AMF Oblivion's
  `tools\make_mapedge_frame.py`.
  * It is drawn at twice its size (52 px corners shown at 26) and its edges repeat rather than stretch.
  * The builder gained `frame_slice` and `frame_mode` in `theme.json` for this; the other themes keep 26 and
    stretch.
* The Oblivion shape:
  * buttons edged in brown ink with a gold thread inside;
  * a gold thread in a ticked check box;
  * the compass star as the selected radio mark.
* The Njordlinger icons recoloured to the theme's ink.
* Seen in MO2 2.5.2 on the Oblivion Remastered instance (2026-10-02): parchment panels, ink text, the map-edge frame
  tiled round the plugin pane, threaded buttons and check boxes.
