# About the template

## EPFL - Unofficial Report/Thesis Template (v1.0)

This template aims to simplify and improve the (Xe)LaTeX report template by EPFL. Some of the main features:

* **Simplicity First:** A class file that has been reduced by nearly 70% to simplify customization;
* **Effortless:** Many common packages are included to get started immediately;
* **Complete:** Ready-to-go when it comes to document and file structure.

This template works with _pdfLaTeX_, _XeLaTeX_ and _LuaLaTeX_. In order to adhere to the EPFL house style, either _XeLaTeX_ or _LuaLaTeX_ is required, as it supports TrueType and OpenType fonts. _BibLaTeX_ is used for the bibliography with as backend _biber_. Please visit https://batuhanfaik.github.io/report for the full documentation.

### License

This work is based of Daan Zwaneveld's TU Delft - Unofficial Report/Thesis Template
This template is available under CC BY-NC 4.0. For more information, see https://creativecommons.org/licenses/by-nc/4.0/. No attribution is required in reports/theses created using this template.

# About the dev container

I couldn't find a way to accept the ttf-mscorefonts-installer EULA automatically for now. If you want to use Microsoft fonts (as is the case in this template), you will need to run `sudo apt update && sudo apt install --no-install-recommends -y ttf-mscorefonts-installer fontconfig && fc-cache -fv` inside the container and accept the EULA manually.