# Refine SVG Script

This script is designed to refine and optimize SVG files for exporting to Flutter custom icons, ensuring no defective icons are generated.

<img src="[https://github.com/ibrahimEltayfe/refine_svg_script/assets/40795940/bb26a4c8-d9eb-4d72-a2e7-79a5bfa04b0b](https://github.com/ibrahimEltayfe/refine_svg_script/assets/40795940/5763b8de-912d-47ae-89b3-3781264f09e6)" width="48%"> ➔ <img src="[https://github.com/ibrahimEltayfe/refine_svg_script/assets/40795940/a224377f-a8f3-4ca7-9d6f-62c7e6075090](https://github.com/ibrahimEltayfe/refine_svg_script/assets/40795940/cdf28299-54ed-4f00-a9af-837e5c9a7807)" width="48%">

## Setup (macOS)

1. **Download Inkscape:**
   - Visit [Inkscape's official website](https://inkscape.org/) to download the application.

2. **Add Inkscape to zshrc:**
   - Open the terminal and run:
     ```bash
     nano ~/.zshrc
     ```
   - Add the following line:
     ```bash
     export PATH="/Applications/Inkscape.app/Contents/MacOS:$PATH"
     ```
   - Save and exit by pressing `Ctrl + O`, then `Enter`, then `Ctrl + X`, then `Y`.

3. **Install SVGO using Homebrew:**
   - Ensure Homebrew is installed. If not, visit [Homebrew's official website](https://brew.sh/) for installation instructions.
   - Run the following command:
     ```bash
     brew install svgo
     ```

4. **Give the Script Permissions:**
   - Run the following command in the terminal, replacing `(put here the script path)` with the actual path to your script:
     ```bash
     chmod 777 (put here the script path)
     ```

## Usage

Now, create a directory and put all of your icons in it, put the script in this directory, then open the terminal in this directory, drag the script in the terminal then press enter.

https://github.com/ibrahimEltayfe/refine_svg_script/assets/40795940/16c8f9fd-25b4-4420-bec6-a5253f39fe8a
Now, you can upload the refined icons to the FlutterIcon website and they will appear as expected.

We welcome contributions for additional platform setups like Windows ..etc. Happy refining! 🚀
