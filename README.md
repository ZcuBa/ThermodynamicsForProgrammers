# ThermodynamicsForProgrammers
A small project for documenting the minimum knowledge, which is needed for a programmer to understand the thermodynamic models used within the industry

The documentation is written in Lyx, and the compiler used in my setup is TexLive, but it should work with most tex compilers.

The source code examples, (if I get around to making any) are all kindly sourced from Sabroe Factory by Johnson Controls, with their permission.


To install Lyx, you'll need a tex compiler, I used TexLive.
TexLive is a younger implementation of tex for Windows, and up to 2017 MikTex was the best bet for a functional text compiler on Windows.
however as of 2018 miktex have had numerous bugs especially relating to pdf compiling documents, and as TexLive has become more stable, well this is what we are currently using.

The TexLive pacakge and repository system, used during texlive installation and package updates, requires a reliable perl.exe,
I have had problems with some of the cygwin windows versions of perl, but have had recent success with the strawberry perl engine.
http://strawberryperl.com/

I had problems with installing repositorie during the tex live installation due to the proxy configuration, now this can be fixed, via this wget proxy setup guide:
http://www.gnu.org/software/wget/manual/html_node/Proxies.html
I did however solve it by taking my laptop home, and connect to the net outside the coorporate network.

I used the texlive installer found here:
https://www.tug.org/texlive/acquire-netinstall.html

and did the "big install" setting all choices to defaults

finally to get a "user friendly" tex IDE i installed lyx from:
https://www.lyx.org/Download


Enjoy the contents of theese documents

/Henrik Dalsager 