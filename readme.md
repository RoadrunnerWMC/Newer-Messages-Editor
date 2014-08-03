# Newer Messages Editor
(1.3)

----------------------------------------------------------------

Support:   http://rvlution.net/forums/  
On GitHub: https://github.com/RoadrunnerWMC/Newer-Messages-Editor  

----------------------------------------------------------------

Newer Messages Editor is a program which can edit and save copies of Messages.bin from Newer Super Mario Bros. Wii.  

----------------------------------------------------------------

### Getting Started

If you're on Windows and don't care about having the bleeding-edge latest features, you can use the official Windows builds. This is by far the easiest setup method. Just download either a ZIP or 7Z file, unzip it and run the executable.

If you are not on Windows or you want the very latest features, you'll need to run Newer Messages Editor from source.


### How to Run Newer Messages Editor from Source

Download and install the following:
 * Python 3.4 (or newer) - http://www.python.org
 * PyQt 5.3 (or newer) - http://www.riverbankcomputing.co.uk/software/pyqt/intro
 * cx_Freeze 4.3 (or newer) (optional) - http://cx-freeze.sourceforge.net

Run the following in a command prompt:  
`python3 newer_messages_editor.py`  
You can replace `python3` with the path to python.exe (including "python.exe" at the end) and `newer_messages_editor.py` with the path to newer_messages_editor.py (including "newer_messages_editor.py" at the end)


### Newer Messages Editor Team

Developers:
 * RoadrunnerWMC - Developer

### Dependencies/Libraries/Resources

Python 3 - Python Software Foundation (https://www.python.org)  
Qt 5 - Nokia (http://qt.nokia.com)  
PyQt5 - Riverbank Computing (http://www.riverbankcomputing.co.uk/software/pyqt/intro)  
cx_Freeze - Anthony Tuininga (http://cx-freeze.sourceforge.net)


### License

Newer Messages Editor is released under the GNU General Public License v3.
See the license file in the distribution for information.

----------------------------------------------------------------

## Changelog

Release 1.3 (unreleased)
 * No changes yet

Release 1.2 (August 2, 2014)
 * Added license.txt and license headers to the source files
 * New readme
 * Dropped Python 2 support
 * Added PyQt5 support
 * Switched from py2exe to cx_Freeze

Release 1.1.1 (August 9, 2013)
 * Fixed a bug in which the "Check for
   Duplicate IDs" window did not appear

Release 1.1 (August 8, 2013)
 * Added drag-and-drop support
 * Message IDs are now editable
 * The "Remove Last" button is now titled "Remove",
   and removes the selected message
 * Added a "Check for Duplicate IDs" option
 * Other minor fixes

Release 1.0 (August 1, 2013)
 * Initial release
