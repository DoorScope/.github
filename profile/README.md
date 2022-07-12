## Welcome to DoorScope, the open-source DOORS and ReqIF viewer!

This is the official website of DoorScope. DoorScope is a software application which can be used 
in the specification review process. Specifications can be exported from IBM DOORS® and viewed with 
links, object attributes and change history (including tables, images and richtext). Objects can be 
annotated and marked with their review status. There is also a fulltext search and scripting facility. 
DoorScope is a single executable and runs natively on Windows without installation. The source code is 
available under GPL or - on request - under user-specific licences.

**Note that DoorScope is now also able to read OMG ReqIF 1.1 format files!**

![Screenshot](http://software.rochus-keller.ch/DoorScope/media/Screen2.png)

More Screenshots: [screenshots - DoorScope HQ.pdf](http://software.rochus-keller.ch/DoorScope/screenshots%20-%20DoorScope%20HQ.pdf)

Tutorial: [How to create a new repository and import documents.pdf](http://software.rochus-keller.ch/DoorScope/Tutorial%20-%20How%20to%20create%20a%20new%20repository%20and%20import%20documents.pdf)

[API Documentation](http://software.rochus-keller.ch/DoorScope/DoorScopeLuaAPIDocumentation.html)

### Downloads
DoorScope is deployed as compressed single-file executables for Windows 9x/2k/XP/Vista/7. Download the ZIP/GZ file 
and uncompress it. The resulting executable can be run without any installations or administrator privileges.

#### Viewer:
Last stable release: [DoorScope (current release)](http://software.rochus-keller.ch/DoorScope/DoorScope_win32.gz)

Source code: [GitHub](https://github.com/rochus-keller/DoorScope)

NOTE: in principle DoorScope would also run natively on Macintosh OS X and Linux, but this would require some additional 
test and adaptation effort; if you're interested send me an email; if there are enough people interested in Linux and OS X 
versions, the effort might be justified; or try it yourself; of course DoorScope perfectly runs with 
[Wine](http://www.winehq.org/) or [WineBottler](http://winebottler.kronenberg.org/) on Linux or OS X. 

#### Extractor:

Last stable release: [DoorScopeETL 0.6.0](http://software.rochus-keller.ch/DoorScope/DoorScopeEtl_0.6.zip)

Source code: [GitHub](https://github.com/rochus-keller/DoorScopeEtl)

The ZIP also includes the DXL script to be run from within DOORS. If you run the script in a module viewer then 
the current module is sent to DoorScopeETL. If you run the script in the DOORS explorer, all formal modules of 
the currently selected folder and its subfolders are transmitted. If DoorScopeETL is not running, or the port 
numbers do not correspond, you get an error. DoorScopeETL writes the modules to DSDX streams located in the selected 
output directory. These streams can then be deployed and imported in a DoorScope repository (DSDB).

#### Demo Repository:
[Demo.dsdb](http://software.rochus-keller.ch/DoorScope/Demo.dsdb)

### License:

DoorScope may be used under the terms of the GNU General Public License (GPL) versions 2.0 or 3.0 as published by the 
Free Software Foundation and appearing in the file LICENSE.GPL included in the packaging of this file. Please review 
the following information to ensure GNU General Public Licensing requirements will be met: 
http://www.fsf.org/licensing/licenses/info/GPLv2.html and http://www.gnu.org/copyleft/gpl.html

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty 
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. 

### Credits:

Author: rochus.keller [at] doorscope.ch

Copyright (c) 2005-2017

Additional Credits:

- Qt GUI Toolkit 4.4 (c) 1995-2008 Trolltech AS, 2008 Nokia Corporation
- Sqlite 3.5, dedicated to the public domain by the authors
- DoorScope icon by courtesy of koalaloha
- Fugue Icons © 2012 by Yusuke Kamiyamane
- Lua 5.1 by R. Ierusalimschy, L. H. de Figueiredo & W. Celes (c) 1994-2006 Tecgraf, PUC-Rio

### Support:
Please post an issue in the corresponding Github repository.
