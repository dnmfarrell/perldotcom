{
   "tags" : [],
   "thumbnail" : "/images/_pub_2001_08_13_yapc-europe/111-yapc-europe.jpg",
   "categories" : "community",
   "image" : null,
   "title" : "Yet Another Perl Conference Europe 2001",
   "date" : "2001-08-13T00:00:00-08:00",
   "draft" : null,
   "authors" : [
      "jouke-visser"
   ],
   "slug" : "/pub/2001/08/13/yapc-europe.html",
   "description" : " Last year Europe had its first Yet Another Perl Conference. Leon Brocard, Jon Peterson and Greg McCarroll did a marvellous job organizing this grassroots conference - themed \"The Art of Perl\" - from scratch within two months. For the..."
}



Last year Europe had its first Yet Another Perl Conference. Leon Brocard, Jon Peterson and Greg McCarroll did a marvellous job organizing this grassroots conference - themed "The Art of Perl" - from scratch within two months. For the first time Europe had its chance meeting people like Nat Torkington, Tom Christiansen, Kevin Lenzo, brian d foy and Michael Schwern. Even before this conference started, a few people from the Netherlands got together and talked about the possibilities of organizing the next YAPC::Europe in Amsterdam.

And so they did. Only this time, they had a whole year to organize it and they chose "Security" as the theme for the conference. Hardly any of The Big Names from the USA were coming to the conference this time, but a lot of European speakers were. And that should be considered a Good Thing - since of course there is a lot of Perl Talent in Europe!

The first day was filled with tutorials, whereas the second and third day were filled with one track containing security-related talks and two others with more general Perl talks. Three complete simultaneous tracks, all stuffed with lots of very interesting talks covering many facets of Perl - it was very hard to pick the talk you wanted to attend each time! Apart from the conference itself, there were quite a lot of Birds of a Feather meetings too (like CPANTS, PerlMonks, P5P, Concurrency and a Pub Crawl), which made the evenings also very entertaining.

The whole conference went extremely well. That's not just my opinion, which may be coloured because I was one of the organizers, but everyone agreed on that. Of course minor, things did not go as planned. For example, the renovation that was going on in the venue disturbed some talks, but everyone agreed that in general, things went extremely smoothly. Thanks to the wireless crew from [HAL2001](http://www.hal2001.org/) everyone in the whole building had wireless access to the Internet. Many people said that the wireless access was even better than it was at TPC. Besides that, the computer lab offered 10 and 100mb regular ethernet access for laptops and had 30 desktop PCs ready to run.

And then there was the catering. There were free lunches for everyone, along with free coffee, tea and snacks on Thursday and Friday afternoon. We all got a good value for our money.

Thursday was Tutorial Day. I was session chair of the tutorials in `$room[2]`, which got its name because the room was at the third floor and the Dutch call that the second. The tutorials in `$room[2]` were about GUI programming with Perl. First there was a 3 hour tutorial about using Tk for existing applications by Mark Overmeer and after lunch, a 3 hour tutorial about Gtk by Redvers Davies. In other rooms tutorials like `Parse::RecDescent` (by Abigail) and Object Oriented Programming (by Johan Vromans) were given.

The welcome speech on Friday was given by Kevin Lenzo. He explained a bit about the merger between YAS, PerlMongers and PerlMonks and told us not to worry because basically nothing would change for us. After that, Daniel Karrenberg -one of the pioneers of the Internet in Europe - gave his keynote speech. He talked about the time from the early days of RIPE NCC until today.

The rest of the day was filled with lots of interesting talks. For example, Artur "Sky" Bergman talked about POE, Robin Houston gave a talk about Mutagenic Modules, Schwern convinced the audience of the need for CPANTS and there were two sessions of lightning talks.

On Friday afternoon, Brian "Ingy" Ingerson explained all about his Inline module. Of course he started with `Inline::C`, talked about the other possibilities like Java, Python, C++ and the like, and could even announce `Inline::Javascript` by Claes Jacobsson that had just been finished. Things were really getting funny when he explained how he created a C interpreter, where you can use a kind of `Inline::Perl` which in turn uses `Inline::C`.

He also mentioned the hilarious `Inline::PERL` by John McNamara (which has now been released under the `Acme::` namespace on CPAN) and explained why this itself is not a bad idea at all, since you are able to use `Inline::Perl` with a version number. That would, for example, allow you to use Perl 5 code in Perl 6...

Saturday morning started with a second keynote speech by Hugh Daniel about "The Current Tragedy of Common Free & Open Source Quality". I was too busy preparing my own talk about [pVoice](http://jouke.perlmonk.org/) later that morning in the Iterative Software room (named after the sponsor) to attend that speech, but everyone agreed that it was a very good one.

That afternoon General M. Schwern ordered us all to be as strict and disciplined as possible in his talk about "Bondage and Discipline, or Strict beyond `strict.pm`". It was a pity Schwern's voice hadn't had the military training that was needed to keep shouting at us all.

The last talk that was given in the O'Reilly room (again named after the sponsor) was given by Jan-Pieter Cornet and Antony Antony, which showed us all the security bloopers we had all made during the conference. It turned out that during the whole conference they had sniffed the network using `dsniff` and analyzed the logs with a quickly hacked Perl script. The results were astonishing. More than half of the attendees had sent unencrypted passwords over the network, most of them not even good enough to be run through `cracklib`. All kinds of insecure protocols were used like Telnet, POP3, FTP and the like. The end of the story was that people who were going to attend the "Hackers at Large" conference the next week were strongly advised to use secure protocols and better passwords. The Perl community is probably friendly enough not to attack fellow Perlhackers, but don't be too sure that the audience of Hackers At Large will be so friendly...

After Kevin Lenzo and yours faithfully thanked everyone who had helped organizing and running the conference, Greg McCarroll led an auction where items that were generously donated by several sponsors were sold using the Dutch Auctioning system. That system means that you start at a high price and let the the price fall at a certain speed until someone says "stop". The price at the moment the person said "stop" is the price he or she has to pay. It worked very well, and was supported by a small Gtk application that Redvers Davies had written.

Not only books were auctioned this time, but also a few London.pm specific items - signed photos of Buffy and Willow, and the right to decide at what date the London.pm meetings are to be held - were auctioned. Dave Cross, writer of Data Munging with Perl, came with a very special item for the auction. The item is best described as

> A module from Damian Conway that he will dedicate to you and which you can influence the purpose/topic of if you can come up with something sufficiently Damian-esque.

That particular item was sold for $200, and the whole auction raised more than 9000 Dutch guilders, some $4000, which will firstly be used to pay all left over costs of the conference. The remainder will be spent on a Perl advocacy project in the Netherlands and on startup costs of next years' YAPC, which will either be in Munich or Paris. Both cities have Perl Monger groups who want to organize it, and YAS will have to make a decision based on the proposals they submit.
The second edition of Yet Another Perl Conference in Europe was a great success. No complaints were heard and everyone was enthusiastic. That's not due to the merit of the organizing committee, but merely the merit of the attendees and speakers. May the next conference be just as successful!
