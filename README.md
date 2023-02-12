![Feature Graphic](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/main/app/src/main/feature_graphic.png)

# MJ PDF
MJ PDF is a fast, minimalist, powerful and totally free PDF viewer made by [Mudlej](https://gitlab.com/mudlej).


# Download
- [x] [Play Store](https://play.google.com/store/apps/details?id=com.gitlab.mudlej.MjPdfReader)
- [x] [IzzyOnDroid Repo](https://apt.izzysoft.de/fdroid/index/apk/com.gitlab.mudlej.MjPdfReader)
- [ ] [Direct Download (V2.0.1)](https://gitlab.com/mudlej_android/mj_pdf_reader/-/raw/V2.0.1+-stable/app/release/app-release.apk)
- [ ] F-droid (no progress yet)


# TABLE OF CONTENTS
* [MJ PDF](https://gitlab.com/mudlej_android/mj_pdf_reader#mj-pdf-reader)
* [Download](https://gitlab.com/mudlej_android/mj_pdf_reader#download)
* [Source Code](https://gitlab.com/mudlej_android/mj_pdf_reader) 
* [Screenshots](https://gitlab.com/mudlej_android/mj_pdf_reader#screenshots)
* [Github Page](https://gitlab.com/mudlej_android/mj_pdf_reader#github-page)
* [More Screenshots](https://gitlab.com/mudlej_android/mj_pdf_reader/-/tree/main/screenshots)
* [MJ PDF Features](https://gitlab.com/mudlej_android/mj_pdf_reader#mj-pdf-reader-features)
* [Permissions and privacy](https://gitlab.com/mudlej_android/mj_pdf_reader#permissions-and-privacy)
* [MJ PDF V2.0.0 Release Notes](https://gitlab.com/mudlej_android/mj_pdf_reader#mj-pdf-v200-release-notes)
* [MJ PDF TO-DO List](https://gitlab.com/mudlej_android/mj_pdf_reader/-/blob/main/todo.md)
* [What is different from PDF Viewer Plus](https://gitlab.com/mudlej_android/mj_pdf_reader#what-is-different-from-pdf-viewer-plus)
* [Underlying Libraries](https://gitlab.com/mudlej_android/mj_pdf_reader#underlying-libraries)
* [Authors and acknowledgment](https://gitlab.com/mudlej_android/mj_pdf_reader#authors-and-acknowledgment)
* [License](https://gitlab.com/mudlej_android/mj_pdf_reader#authors-and-acknowledgment)


## MJ PDF Features
- Fast, minimalist and simple.
- Open source with total privacy.
- Remembers the last opened page.
- Dark mode for the PDF.
- Fast and powerful search in the PDF.
- True full screen with shortcut buttons.
- Auto Scrolling with adjustable speed.
- Text Mode to view the PDF a text.
- Separate pages for Table of Content, Links in the PDF and search results.
- Open online PDFs through links.
- Share & print PDFs.
- Open multiple PDFs.
- MJ PDF does not collect any kind of data. (you can check the code yourself)


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
* You can search the the results of a search.
* Added support for Hyperlinks.
* Added a Table of Content page.
* Added a page to see a list of all the links embedded in the file.
* Added Text Mode to view the PDF as text. (configurable text size and color)
* Added auto scrolling. (adjustable speed, both direction).
* Added a button to lock horizontal scrolling.
* Added a button to take a screenshot.
* Added a second top bar with seven shortcuts. (hidden by default)
* Added icons to all menu items in all pages.
* Clicking on the scroll handle shows the 'Go To Page' dialog.
* Prevent accidental back pressing by required double press to exit. 
* Decreased app's size by 27.5%. It became 5.1 Megabytes.
* Fixed not remembering the last visited page sometimes.
* Fixed hiding the Buttons and Scroll Handle while the user is still interacting with them.
* Fixed not being able to reset the zoom to a page-width level by double tapping
* Fixed few common crashes.
* Fixed no stopping auto scrolling when the user exit the Full Screen Mode.


## What is different from PDF Viewer Plus
After the launch of MJ PDF, Gokul Swaminathan discontinued PDF Viewer Plus app. 
And he [suggested](https://github.com/JavaCafe01/PdfViewer#anouncement) MJ PDF as a replacement.
MJ PDF V2.0 codebase is 400% larger than PDF Viewer Plus without counting the libraries forked for MJ PDF, while being a quarter of its size.
[See changelog](https://gitlab.com/mudlej_android/mj_pdf_reader/-/blob/main/change_log.md)


## Underlying Libraries
I Forked [PdfiumAndroid](https://github.com/barteksc/PdfiumAndroid) to update its core libraries that were years behind and had too many security vulnerabilities.
And Forked [ AndroidPdfViewer](https://github.com/barteksc/AndroidPdfViewer) to add features (like extracting PDF text) and modify some of its behavior (like scroll handle).

* Updated PDFium to 106.0.5241.0 ([source code](https://pdfium.googlesource.com/pdfium/+/refs/heads/main), [building script](https://github.com/bblanchon/pdfium-binaries))
* Updated libpng to 1.6.37 ([source code](https://sourceforge.net/projects/libpng/files/libpng16/1.6.37/), [building script](https://github.com/kota-kota/libpng-build))
* Updated Freetype to 2.12.1 ([source code](https://github.com/freetype/freetype), [building script](https://github.com/kota-kota/freetype-build))


## Authors and acknowledgment
- MJ PDF is made by [Mudlej](https://gitlab.com/mudlej).
- The original app (PDF View Plus) was made by Gokul Swaminathan ([@JavaCafe01](https://github.com/JavaCafe01)).
- [@barteksc](https://github.com/barteksc), made the libraries that MJ PDF uses to render PDFs. 
- Credits to (@Derekelkins)'s pull request for adding the ability to remember last opened page.

## License
MJ PDF uses the GPLv3 license, the original app (PDF View Plus) was under MIT license
