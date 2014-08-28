===================
Music Score Creator
===================

Description
-----------

It is "A music score creator", a program that, starting from a audio recorded or loaded, will generate the sheet music for that sounds. It's limited to a single instrument-voice and still as development.

Installation
------------
You'll need to install the following packages:

python-wxgtk2.8
python-pyaudio
python-numpy
python-matplotlib
python-scipy
lilypond

In Debian systems, you can install it like this:

sudo apt-get install python-wxgtk2.8 python-pyaudio python-numpy python-matplotlib python-scipy lilypond

To Do
-----

For now, it's limited to a single voice. And the results can vary depending on the time when you start recording. Since the audio is divided into pieces and for now is sensitive to when you start recording. In future versions I will try to fix it by adding a preprocessing. So, the missing features, for now, are:

- Add Windows/Mac support.
- Add possibility of change the instrument.

Changelog 0.7
-------------

- New method to obtain the duration of the notes.
- Steps for multiplatform support.

Example of use
--------------

If you want to see a working example, in this link_ you have a video.

.. _link: http://www.dailymotion.com/video/x2404p9_score-music-creator_tech