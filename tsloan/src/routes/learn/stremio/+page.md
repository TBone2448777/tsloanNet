---
title: Stremio - Replace Every Streaming Service
---

# {title}

If you, like most people, are fed up with needing a dozen streaming services in order to watch everything, then you need to try Stremio. There are three primary benefits to this:

1. You can watch basically every show and movie.
2. Everything is in one place. 
    - Netflix, AppleTV, Hulu, Peacock, etc.
    - So is your watchlist and currently watching, meaning you don't have to constantly switch programs.
3. Better video and audio quality than streaming typically offers.

And the best part is the price! It is only $19 for 6 months (depending on when you are reading this, the price may have changed, but it shouldn't be drastically different)! This writeup will walk you through the setup for Stremio as well as explain the why and how. If you don't care how or why and just want the step-by-step instructions: [click here](#steps).

## How does Stremio work?

There are three levels to Stremio:

1. Initial Seeder
    - This is just someone who takes a file and makes it available for others to download directly from their computer. In the case of shows and movies, the initial seeders get high quality videos of said shows and movies.
    - From there, other people interested in these videos can download them directly from the initial seeder's computer. Once downloaded, they seed the file as well. Allowing the next person who wants that particular show or movie to get the file from both of them at once: this both increases download speed and decreases the strain on each seeder's hardware. They cycle repeats as more and more people download and seed the video.
    - The downloading of these files from others computers is a type of peer-to-peer file sharing (P2P), also known as torrenting. The files themselves are torrents.
2. Debrid Services
    - These are giant servers that download torrents and allow people that subscribe to them to download the file directly from their servers.
    - Debrid services are very useful, as sometimes all seeders of a file stop seeding it, and people can no longer gain access. In addition, these servers are typically <i>way</i> faster as you don't have to rely on random people's internet connections.
3. Stremio
    - Stremio acts as a bridge between your screen and these debrid services. By using installed plugins, Stremio requests the movie or show you want from a debrid services and puts it on your screen.

## Security Risks

Because torrenting (see above) is decentralized, anybody can join. This means law enforcement or agencies hired by media companies may also help seed the content. But why would they help with piracy? Because when they send the files out to users, they can track where it is going. Then you get a warning and a bill in the mail from your internet service provider telling you to stop or else your service will be disconnected.

However, this is incredibly rare and is unlikely to happen. In particular, for our use case they're infinitely more interested in the people that released the video in the first place and those seeding the file to provide access to everyone else. That doesn't mean we won't take steps to protect ourselves against it.

That's where the debrid services come in. By downloading from them you can ensure you are safe as there would be no way for law enforcement or media companies to figure out what you are downloading and to send you a bill. The servers are typically located in countries with terrifically strong privacy laws that would prevent agencies from strong arming them. In addition, the good ones have a "no logging" policy that is also audited regularly: meaning there wouldn't be documents on who downloaded what even if an agency did successfully strong arm them.

## Requirements
- Laptop
- Real Debrid Account (Follow this guide here if you don't have one yet)

## Steps<a id="steps"></a>