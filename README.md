waiter
======

I would like wait / sleep to show me how much time is remaining in my timers.

Example usage
=============

`waiter 3600 && ./build.sh i9100 && waiter 7200 && repo sync -j16 && ./build.sh i9100`

This is a real use example that I run. Sometimes I like to watch The West Wing before
slowing down my video playback, so I have it wait an hour before initiating a build of
CyanogenMod, then I have it wait two more hours before pulling down the source and
building CM10 again.

In theory, it should work on Windows (I use it on Linux), I imagine it would be usable
in a batch file something like this:

    waiter 3600
    c:\myfile.exe
    waiter 7200
    c:\myotherfile.exe

Really, I've spent more time authoring this documentation than the script. Now go and enjoy :)

Copyright / License
===================

Copyright (c) 2012, Adam Carmichael <carneeki@carneeki.net>
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
  * Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
  * Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
  * Neither the name of Adam Carmichael nor the
    names of its contributors may be used to endorse or promote products
    derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL ADAM CARMICHAEL BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
