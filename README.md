![Feature Graphic](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/main/app/src/main/feature_graphic.png)

# MJ PDF
MJ PDF is a fast, minimalist, powerful and totally free PDF viewer made by [Mudlej](https://gitlab.com/mudlej).


# Download & Links
- [x] [Play Store](https://play.google.com/store/apps/details?id=com.gitlab.mudlej.MjPdfReader)
- [x] [IzzyOnDroid Repo](https://apt.izzysoft.de/fdroid/index/apk/com.gitlab.mudlej.MjPdfReader)
- [x] [Direct Download (V2.0.1)](https://archive.org/details/mj-pdf-v2-0-1)
- [ ] F-droid (still trying)
- [x] [Github Page for issues](https://github.com/mudlej/mj_pdf/)


# TABLE OF CONTENTS
* [MJ PDF](#mj-pdf)
* [Download & Links](#download--links)
* [Source Code](https://gitlab.com/mudlej_android/mj_pdf_reader)
* [Screenshots](#screenshots)
* [Github Page](#github-page)
* [More Screenshots](https://gitlab.com/mudlej_android/mj_pdf_reader/-/tree/main/screenshots)
* [MJ PDF Features](#mj-pdf-features)
* [Permissions and privacy](#permissions-and-privacy)
* [MJ PDF V2.0.0 Release Notes](#mj-pdf-v200-release-notes)
* [MJ PDF TO-DO List](https://gitlab.com/mudlej_android/mj_pdf_reader/-/blob/main/todo.md)
* [What is different from PDF Viewer Plus](#what-is-different-from-pdf-viewer-plus)
* [Underlying Libraries](#underlying-libraries)
* [Authors and acknowledgment](#authors-and-acknowledgment)
* [License](#authors-and-acknowledgment)


## MJ PDF Features
- Fast, simple, and very lightweight. (5.1 MB in Play Store)
- Open source with total privacy.
- Remembers the last page that was opened in each document.
- Dark mode for the PDF.
- Very fast and powerful search in the PDF.
- Full-screen mode with buttons to:  
  - Rotate the screen.  
  - Brightness control bar.  
  - Auto scroll with adjustable speed.  
  - Lock horizontal swipe.  
  - Take a screenshot.
- Text Mode to view the PDF a text.
- A page to see the full Table of Content
- A page to see all the Links embedded in the PDF.
- Open online PDFs through links.
- Share & print PDFs.
- Open multiple instance of the app at the same time.


## Screenshots
| Light Mode | Dark Mode | Main Menu |
|:-:|:-:|:-:|
| ![Light Mode](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/main/screenshots/light_framed.png) | ![Dark Mode](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/main/screenshots/dark_framed.png) | ![Main Menu](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/main/screenshots/light_main_menu_framed.png) |


## Github Page
The codebase is hosted on [Gitlab](https://gitlab.com/mudlej_android/mj_pdf_reader). But I opened a page in Github for issues like requests, bug reports...
[Github page link](https://github.com/mudlej/mj_pdf/).


## Permissions and privacy
This app does not collect any data.
The following permissions are required to provide specific features in the app:
* *Internet*: For opening PDFs through links
* *Storage*: For saving downloading PDFs and opening them from storage


## MJ PDF V2.0.0 Release Notes
* Rebranded the app as MJ PDF with a new original icon.  
* Search has become blazingly fast.
* Added the ability to filter search results by another query.
* Search results are expandable if you want to see more context.
* The chosen search result will be highlighted in the PDF.
* Added support for Hyperlinks.
* Added a Table of Content page.
* Added auto scrolling. (adjustable speed, both direction).
* Added a button to lock horizontal scrolling.
* Added a button to take a screenshot.
* Added a second top bar with seven shortcuts. (hidden by default)
* Added a page to see a list of all the links embedded in the file.
* Added Text Mode to view the PDF as text.
  * You can change the size of text in Text Mode.
  * You can change the color of the text and background in Text Mode.
  * All preferences (size, color..) and the last opened page will be saved automatically.
  * Clicking on the page number in Text Mode shows a 'Go To Page' popup.
* Added icons to all menu items in all pages.
* Clicking on the scroll handle shows the 'Go To Page' popup.
* Prevent accidental back pressing by required double press to exit. 
* Decreased app's size by 27.5%. It became 5.1 Megabytes.
* Fixed not remembering the last visited page sometimes.
* Fixed hiding the Buttons and Scroll Handle while the user is still interacting with them.
* Fixed not being able to reset the zoom to a page-width level by double tapping
* Fixed few common crashes.
* Fixed not stopping auto scrolling when the user exit the Full Screen Mode.


## What is different from PDF Viewer Plus
After the launch of MJ PDF, Gokul Swaminathan discontinued PDF Viewer Plus app. 
And he [suggested](https://github.com/JavaCafe01/PdfViewer#anouncement) MJ PDF as a replacement.
MJ PDF V2.0 codebase is 400% larger than PDF Viewer Plus without counting the libraries forked for MJ PDF, while being a quarter of its size.
[See changelog](https://gitlab.com/mudlej_android/mj_pdf_reader/-/blob/main/change_log.md)


## Underlying Libraries
I Forked [PdfiumAndroid](https://github.com/barteksc/PdfiumAndroid) to update its core libraries that were years behind and had too many security vulnerabilities.
And Forked [ AndroidPdfViewer](https://github.com/barteksc/AndroidPdfViewer) to add features (like extracting PDF text) and modify some of its behavior (like scroll handle).

* Updated PDFium to 112.0.5579.0 (in v2.0.2) ([source code](https://pdfium.googlesource.com/pdfium/+/refs/heads/main), [building script](https://github.com/bblanchon/pdfium-binaries))
* Updated libpng to 1.6.37 ([source code](https://sourceforge.net/projects/libpng/files/libpng16/1.6.37/), [building script](https://github.com/kota-kota/libpng-build))
* Updated Freetype to 2.12.1 ([source code](https://github.com/freetype/freetype), [building script](https://github.com/kota-kota/freetype-build))


## Authors and acknowledgment
- MJ PDF is made by [Mudlej](https://gitlab.com/mudlej).
- The original app (PDF View Plus) was made by Gokul Swaminathan ([@JavaCafe01](https://github.com/JavaCafe01)).
- [@barteksc](https://github.com/barteksc), made the libraries that MJ PDF uses to render PDFs. 
- Credits to (@Derekelkins)'s pull request for adding the ability to remember last opened page.

## License
MJ PDF uses the GPLv3 license, the original app (PDF View Plus) was under MIT license
