# Dataset Assets for Blender

A Blender add-on that browses open 3D datasets (Poly Haven, Google Scanned Objects, NVIDIA
SimReady, Smithsonian, Objaverse, Amazon Berkeley Objects, and more) plus Quixel Megascans on
Fab, in its own window. It imports models straight into the open .blend with their textures
packed.

Requires Blender 5.2 or newer.

## Install

1. Download the latest `dataset_assets-<version>.zip` from this repository.
2. Drag it into Blender (or Edit > Preferences > Get Extensions > ⌄ > Install from Disk).
3. Under Edit > Preferences > System > Network, turn on **Allow Online Access**. The add-on needs
   it to download assets.

That's it. The add-on keeps itself up to date: shortly after Blender starts it checks this
repository and installs a newer version on its own. Turn this off with **Update automatically**
in the add-on's preferences, which also has a **Check for Updates** button.

## Use

Open it from the **Datasets** button in the top bar, the Add menu (Shift+A), or
File > Import > Dataset Asset Browser.

## License

GPL-3.0-or-later. Assets you import keep their own licenses (shown in the browser and stored
on each imported asset).
