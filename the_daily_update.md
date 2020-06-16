## The daily update

Repetition is bad. That's what Western culture tells us.

Repetition is mindless, it says.

But how do you get good at something? How do you _achieve mastery_?

Knowing what you're doing is important. You can read 100 books about how to play the violin. There are violin methods going back hundreds of years. While you're at it, why not read one of the many books on how to build a violin. That will help you soak up the _essence_ of the violin.

If you read a couple dozen violin books on building and playing them, you'll know a lot about the violin. How they're made, how they're tuned, how they're played.

But eventually you need to get your hands on a fiddle, put it under your chin and start sawing away with a horsehair bow. The instruction of a good teacher will help. It's probably mandatory.

Then you need to _get good_.

How do you do that? There's really only one way:

You do that thing.

Many, many, many times. Every day. For as long as it takes. Understanding and knowledge are important, but _doing well_ means in large part _doing often_.

We are told mastery is good. How do you arrive at mastery?

In Western culture, it's better when that mastery is the result more of pure genius and less relentless, repetitious toil. It makes for a better story.

But even geniuses need to practice. 

When I saw violinist Joshua Bell lead the Academy of St. Martin in the Fields as both conducter and concertmaster, playing the violin with speed, fluidity and ease, it looks like the most natural thing in the world. It seems effortless.

Yet he didn't get there without many thousands of hours of practice and performance over decades.

Scales, exercises, etudes, studies. And more of the same. Every day. Year after year.

Without constant repetition, Joshua Bell the virtuoso could never happen.

I don't want to compare mastering the violin with washing dishes, sweeping the floor, and setting up and maintaining a Linux system.

But I do. And I will.

The secret to mastery is embracing the toil, the repetition, the practice.

Running `sudo apt update` and then `sudo apt upgrade` won't get you to Carnegie Hall (except maybe to the venue's IT department).

But you'll have a fully patched Debian system that's ready to run.

## Installing Debian: How to get good

I learned to embrace the process of installing Debian by doing it dozens and dozens of times, beginning when I first "discovered" Etch until now, when I run Buster on a 2017 HP laptop and 2011 iMac desktop. During the many years between Etch and Buster, it helped a great deal that I had many older "test" computers and hard drives at my disposal. If I screwed anything up, I could start over.

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

Weekly is better. I like to think of running an update/upgrade daily as _something you do_.

Many days there are no updates. Sometimes you have two or three. On a day when Firefox updates, there are so many language packages that you could have 50.

Keep an eye on <http://debian.org/security>. There you can see all of the updates that the Debian Security Team has sent through the repositories to keep your system running as securely as possible. Sometimes there are even bug fixes, though the whole point of Debian Stable (that being _stability_) means that security patches are king and software "improvements" wait for the next release.

But what if you really want those _improvements_? After using Linux and BSD for years, I've come to learn that latest doesn't always mean greatest, and being on the edge often brings new bugs along with it.

That's not to say that you can't run newer software in Debian. There's always the Testing and Unstable distributions, though even those I find to be behind Fedora and Arch in almost all cases.

There are some newer packages in Debian Backports. And now software packaged in the Flatpak format can run on Debian Stable. Since Buster is very IDE-poor in its repos, I have successfully used the Flathub site (where Flatpaks tend to live) to successfully install and run Apache NetBeans and IntelliJ IDEA Community. I haven't yet tried Eclipse, but Flathub has it.

Why none of these big-time Java IDEs are in Debian is another story. Eclipse and NetBeans weren't "ready" when Buster was frozen, and I think there are licensing reasons why IntelliJ is not in Debian. Flathub means you can get all three with little hassle.

My old laptop still runs Fedora. When things are working, I tend to stick with it. In Fedora, there are updates just about every day. Sometimes I don't open it for a month at a time. When I wait that long, there are hundreds of packages ready to upgrade and up to a gigabyte of data that Fedora's package-manager, `dnf`, needs to pull down.
