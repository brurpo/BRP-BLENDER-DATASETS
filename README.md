# Dataset Assets for Blender

A Blender extension repository with one add-on, **Dataset Assets**. It browses open 3D
datasets (Poly Haven, Google Scanned Objects, NVIDIA SimReady, Smithsonian, Objaverse,
Amazon Berkeley Objects, and more) plus Quixel Megascans on Fab, in its own window. It imports
models straight into the open .blend with their textures packed.

Requires Blender 5.2 or newer.

## Install with automatic updates

1. In Blender, open **Edit > Preferences > Get Extensions**.
2. Open the **Repositories** menu (top right) and click **+ > Add Remote Repository**.
3. Paste this URL and turn on **Check for Updates on Startup**:

   ```
   https://raw.githubusercontent.com/brurpo/BRP-BLENDER-DATASETS/main/index.json
   ```

4. Search for **Dataset Assets** in Get Extensions and click **Install**.
5. Under **System > Network**, turn on **Allow Online Access**.

New versions then show up in Get Extensions with an **Update** button.

## Install once, without updates

Download `dataset_assets-<version>.zip` from this repository and drag it into Blender.

## Use

Open it from the **Datasets** button in the top bar, the Add menu (Shift+A), or
File > Import > Dataset Asset Browser.

## License

GPL-3.0-or-later. Assets you import keep their own licenses (shown in the browser and stored
on each imported asset).
