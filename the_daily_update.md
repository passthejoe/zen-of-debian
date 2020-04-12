## The daily update

Repetition is bad, Western culture tells us.

Repetition is mindless, it says.

But how do you get good at something? How do you _achieve mastery_?

Knowing what you're doing is important. You can read 100 books about how to play the violin. There are very likely violin methods going back hundreds of years.

If you read a couple dozen violin methods, you'd know a lot about the violin: how they're made, how they're tuned, how they're played.

But eventually you need to get your hands on a fiddle, put it under your chin and start sawing away with a horsehair bow. The instruction of a good teacher will help. It's probably mandatory.

Then you need to _get good_.

How do you do that? There's really only one way.

You do that thing. Many, many, many times. Every day. For as long as it takes. Understanding and knowledge are important, but _doing well_ takes _doing often_.

Yet we are told mastery is good. So how do you arrive at mastery?

But it's better when that mastery is the result of pure genius and not relentless, repetitious toil.

But even geniuses need to practice. 

When I saw violinist Joshua Bell lead the Academy of St. Martin in the Fields as both conducter and concertmaster, playing the violin with speed, fluidity and ease, it looks like the most natural thing in the world.

Yet he didn't get there without many thousands of hours of practice and performance over decades.

Scales, exercises, etudes, studies. And more of the same. Every day. Year after year.

Without repetition, Joshua Bell the virtuoso could never happen.

I don't want to compare mastering the violin with washing dishes, sweeping the floor, and setting up and maintaining a Linux system.

But I do. And I will.

The secret to mastery is embracing the toil, the repetition, the practice.

Running `sudo apt update` won't get you to Carnegie Hall (except maybe to the venue's IT department).

I learned to embrace the process of installing Debian by doing it dozens and dozens of times. It helped a great deal that I had many older "test" computers and hard drives at my disposal. If I screwed anything up, I could start over.

I tended to do it the same way every time: Encrypted LVM most of the time, accepting most if not all of the installer's defaults.

And keeping the system up to date goes the same way most times:

```
steven@steven-debian:~$ sudo apt update
[sudo] password for steven: 
Hit:1 http://deb.debian.org/debian buster InRelease
Hit:2 http://security.debian.org/debian-security buster/updates InRelease
Hit:3 http://deb.debian.org/debian buster-updates InRelease
Hit:4 http://deb.debian.org/debian buster-backports InRelease
Reading package lists... Done
Building dependency tree       
Reading state information... Done
All packages are up to date.
steven@steven-debian:~$
```

If there were any packages that needed updating, the next command would be:

```
steven@steven-debian:~$ sudo apt upgrade
```

And that's about it during the life of a Debian Stable release.

On my current Debian laptop, I do this check every day, usually in the morning. There are never too many updates because it's Debian Stable. I could run an update/upgrade once a week or even once a month. 

(something about fast-paced Fedora vs. Debian Stable)

My old laptop still runs Fedora. When things are working, I tend to stick with it. In Fedora, there are updates just about every day. Sometimes I don't open it for a month at a time. When I wait that long, there are hundreds of packages ready to upgrade and up to a gigabyte of data that Fedora's package-manager, `dnf`, needs to pull down.

I expect that the pace of package upgrades is almost the same 



