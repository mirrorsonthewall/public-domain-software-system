<h1> Public Domain Software System (PDSS) </h1>

<h3> Introduction </h3>
<p>
This is a project to try to create as much of a fully public domain software system (PDSS) as possible. 
The assumption is that eventually, a fully public domain system will exist, 
from a public domain operating system to the applications running on it, comparable to popular operating
systems like Linux, Windows, or Mac, etc.
</p>
<p>
Please see [NOTES.md](https://github.com/mirrorsonthewall/public-domain-software-system/blob/master/NOTES.md) for more project-specific rules of thumb. 
</p>
<p>Please note this is also a brand new work in progress!</p>

<h3> Addressing Licensing Issues </h3>
<p>If there are issues surrounding public domain licenses, that might be among the top issues to talk about, as creating a solid foundation to build upon. Some suggested licenses have been:</p>
<p> <a href="https://unlicense.org"> Unlicense </a>
<p> ...more to come... </p>

<h3> Open Hardware </h3>
<p>Because of the difficulty of writing drivers, it might be wise to focus on writing software for specific chosen hardware,
  and possibly some open hardware like the <a href="https://www.crowdsupply.com/sutajio-kosagi/novena"> Novena Project </a> might be a good choice.
  
<h3> Public Domain Programming Languages </h3>
<p>Then, to write public domain software, it might be nice to have a programming language that's in the public domain 
to write in. At present, I only have found a few:</p>
<p>So-called <a href="https://templeos.holyc.xyz/Wb/Doc/HolyC.html#l1"> "HolyC",</a> which seems to lack documentation
and perhaps the ability to be used outside of the TempleOS operating system.</p>
<p><a href="https://github.com/drylang/drylang"> Dry Language, </a>created by one of the Unlicense co-creators or creator.</p>
<p><a href="https://pdos.sourceforge.net/">PDPCLIB (Public Domain Project C Library),</a> which I think is just a library
and not a full programming language?</p>
<p>One of these projects could be reworked, or a new programming language could be created from scratch.</p>
<p>The most promising project might be to rewrite one or both of the CMUCL/SBCL Common Lisp implementations, as <a href="https://www.cons.org/cmucl/">CMUCL</a> and <a href="http://www.sbcl.org/history.html">SBCL</a> are both mostly in the public domain except for some select files. If those non-PD files could be identified and rewritten, then forks like "PDCMUCL" and "PDSBCL" could be released.

<h3> Public Domain Operating Systems (PD OSs)
<p>Then, at some point, I expect a full public domain operating system will be created. 
At first it will have simple features, but may grow to something like Linux is today. I expect this could take a long time,
but I also think there are a growing number of people interested in public domain software projects, so I'm not sure if
we might have a lot of people willing to contribute to such a project. At present, the PD OS projects I could find online are:</p>
<p><a href="https://templeos.org/"> TempleOS:</a> This project in itself was eclectic and is considered finished, so it may not be the ideal basis for a PDSS, however a fork called <a href="https://github.com/minexew/Shrine">ShrineOS</a> exists to attempt to build on TempleOS in a more "modern" way. I have considered possibly another fork like "TemplelessOS" that might strip the "Temple" aspect of TempleOS and keep the functional operating system parts; I have wondered if in any event some parts might be salvaged from this to move PD OS development forward, but I suspect probably a new or alternative project altogether might be picked to move a PDSS forward. TempleOS has, however, been said to be technically impressive for one person to have created.</p>
<p><a href="http://pdos.sourceforge.net/">PDOS: Public Domain Operating System.</a> This appears to be the most active current effort to create a public domain operating system. Note how I have refered to PD OSs with that kind of spacing, to contrast with "the" singular PDOS project.</p>
<p><a href="https://github.com/muazzamalikazmi/alotware">AlotwareOS</a>- I do not know how this compares to the others, it seems like a small project.</p>
<p><a href="https://github.com/catseye/BefOS">BefOS</a>- Same as AlotwareOS, don't know how it compares and seems small, but either might have something the could be built upon or learned from, or the projects themselves might be functional to fork and build on.</p>
<p> In addition to these, I think there would be nothing wrong with starting up a new few projects from scratch, and I have an interest in trying that maybe at some point. </p>
  
<h3> Shells </h3>
<p>The most promising shell available seems to be the <a href="https://web.archive.org/web/20040216045828/http://web.cs.mun.ca/~michael/pdksh/"> Public Domain Korn Shell (pdksh),</a> which is mostly in the public domain except for a few files which I think are <a href="https://github.com/ibara/oksh/blob/master/LEGAL">identified here.</a> If those are the files or we could identify them and rewrite them, we could release a fpdksh (FULLY public domain korn shell...).</p>

<h3>Text Editors </h3>
<p><a href="https://kakoune.org/">Kakoune</a> seems like the clear winner here, as it is a new/modern project and is released in to the public domain. This is a great example of good current public domain software, the quality of which I hope the other mentioned categories can be brought up to. Some other projects I found that might be reworked or learned from:
<p></a href="https://github.com/mamoniot/mtext">MText</a></p>
<p></a href="https://github.com/mooseman/pdeditor">PDEditor(s)</a></p>
<p></a href="https://sourceforge.net/projects/wed/">WED, Windows Text Editor</a></p>

<h3> Image Editing </h3>
<p></a href="https://github.com/timmyRS/Paintery">Paintery</a></p>

<h3> Browser </h3>
<p>This might be one of the more challenging ones, but maybe something of a CLI browser like links or lynx could be
made without a lot of difficulty, to at least get the ball rolling.</p>

<h3> Games</h3>
<p> ... </p>

<h3> Other Software As Desired And Needed </h3>
<p>From the core above, it would seem like the rest of the software that people want could just be added and subtracted as people need.</p>

<h3> PD Software Listings </h3>
<p></a href="https://unlicense.org/">Unlicense.org Lists</a></p>
<p></a href="https://github.com/johnjago/awesome-uncopyright#software">Awesome-Uncopyright:Software</a></p>

<h3> Four Ways To Get More PD Software </h3>
<p>1. Improve Current PD Projects</p>
<p>2. Suggest Current License-Free Software Become PD</p>
<p>3. Create A Fully PD Fork Of Currently-Existing Mostly PD Projects (pdksh or CMUCL/SBCL cores for instance)</p>
<p>4. Write New Software From Scratch</p>

<h3> Conclusion </h3>
<p>Are you interested in participating in or leading an effort to create a full basic PD software system?
What can be done to move PD software forward? I think a lot of people are interested in this, so how could we
effectively organize moving on the top priority projects? Perhaps, check out the "NOTES.md" link above, and
then open an issue if you have any feedback.</p>
