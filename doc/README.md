BiYanZu Core 1.0.0
=====================

Running
---------------------
The following are some helpful notes on how to run BiYanZu on your native platform.

### Unix

You need the Qt4 run-time libraries to run BiYanZu-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/biyanzu-qt (GUI, 32-bit) or bin/32/biyanzud (headless, 32-bit)
- bin/64/biyanzu-qt (GUI, 64-bit) or bin/64/biyanzud (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run biyanzu-qt.exe.

### OS X

Drag BiYanZu-Qt to your applications folder, and then run BiYanZu-Qt.

Building
---------------------
The following are developer notes on how to build BiYanZu on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)

Development
---------------------
The BiYanZu repo's [root README](https://github.com/biyanzu/biyanzu/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)



### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
