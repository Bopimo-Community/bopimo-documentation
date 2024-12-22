# What I found in the client and launcher source code.  
Now, let's get this straight. I am _not_ condoning ANYONE to browse the source code of Bopimo!. I have specifically not stated how I got access to these files for this reason.  
With that out of the way, now we can get started on the fun stuff.  

# Launcher Findings
This will be short since there's not too much to talk about.  
But mainly, the launcher is an electron app.  
Yeah, the entire thing is just HTML, CSS, and JS. It wasn't hard to make mods for the launcher after this was discovered, and it's not too hard to get the source directly from the launcher.  

Technically, the launcher is "open-source" since it is licensed under ISC. If you want to know more about that, just view the license [here](https://www.isc.org/licenses/).  

That's all we have on the launcher at the moment, more may be found later on, but whether or not the vulnerability will be patched or not is unknown.

**Added note, I found the client CDN and you can get older versions of Bopimo!'s client.

# Client Findings
Boy could I talk about this all day long. But I'll just sum up the better parts.  
First off, the client is Godot, if it wasn't already obvious. There are a bunch of Godot scripts and files in the client source code (which I will again remind you, to NOT try to get these files. I did not look into the actual code.) which are, for the better part, showing a lot of behind the scenes. Such findings as rizz.bop and egg.gd truly do make me think of the future. Speaking of which,

## Maps/Level files
Yes, there are bop files bundled in the client. A LOT of bop files. I can only fully assume that they were made for testing early on and were simply never removed from the game code, because a lot were about features like rolling and dashing. And yes, it is where I found the true and only, rizz.bop. A few interesting ones are:
 - BanPrison.bop
 - AAAAAAAAAAAAAAAAAt.bop_old_godot_3 (what??)
 - HALLOWEEN.bop
 - rolling.bop
 - wtf.bopjson

## Unusual findings
I found things in the client that, well I'd suppose, im not supposed to see. That also included a bit of a "spoiler" which I cannot bring up for obvious reasons. There is a track in the Music folder called "devoid.ogg". It's quite the, strange track. I'll just link the track and let you hear it for yourself. https://files.catbox.moe/wqgaii.ogg  
There is also a scrapped track called "peaceful1.ogg" in the files. While not as, well, devoid.ogg like devoid.ogg, it's still strange to see such a track just be scrapped. Very likely replace with Serene. https://files.catbox.moe/ci63ow.ogg

## Accessories?
So, a quick one here, All the official Bopimo! accessories (including toys, shirts, shoes, pants, and hats) are stored locally in the client. While I'm not fully sure if the client actually uses these models and textures, they are in the source files.

# My general overview
If it wasn't clear already, Bopimo! has a crap ton of entrances for anybody and it doesn't take a genius to get in. All of this also _kind_ of makes me think differently of it, if this took 6 years.  
But, like I should say, don't go harrassing the devs over this. They still put effort into it and I believe Bopimo has potential. (just to say, one of the owners got doxxed after 2 days after release.)
