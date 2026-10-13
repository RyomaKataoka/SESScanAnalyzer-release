SES Scan Analyzer — Third-party software / サードパーティ ソフトウェア

This application is built with Python and the packages listed in PACKAGES.txt
(numpy, SciPy, matplotlib, PySide6, ...). Their license files are in the
sub-folders of this "licenses" folder.

Qt for Python (PySide6, shiboken6) and the Qt libraries are used under the
GNU Lesser General Public License v3 (LGPL-3.0; texts: LGPL-3.0.txt, GPL-3.0.txt).
The Qt libraries are distributed as separate, unmodified DLL files in the
application folder (_internal\PySide6), so they can be replaced by the user
with compatible versions. Source code: https://download.qt.io/ and
https://code.qt.io/ (Qt for Python 6.11.2).

本アプリは Python と PACKAGES.txt に記載のパッケージを使用しています。
Qt / PySide6 は LGPL-3.0 で利用しており、Qt のライブラリは改変せずに
個別のDLLとしてアプリのフォルダ（_internal\PySide6）に置いています。
