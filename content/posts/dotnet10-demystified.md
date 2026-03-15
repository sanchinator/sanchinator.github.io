---
title: ".NET 10 Demystified"
date: 2025-11-18
tags: ["events", "dotnet", "csharp"]
description: "A Tech & Meet session with Kevin De Rudder covering what's new in .NET 10."
---

![Kevin De Rudder presenting the .NET ecosystem](/images/dotnet10-slide.png)

I went into this session knowing basically nothing about .NET 10. I'd heard the name, used C# in a few projects, but had no real picture of where the ecosystem was heading or how the pieces fit together. Kevin De Rudder filled in a lot of that in under an hour.

He moved quickly — new features, ecosystem overview, what's actually changed between versions. At one point he described .NET as "one big family," meaning the runtime, libraries, and tooling are built to work together rather than against each other. We've spent enough time in class talking about Java's fragmentation that the contrast landed. Java has a reputation for having five ways to do the same thing, half of them deprecated, and nobody quite agreeing on which build tool to use. .NET doesn't have that problem to the same degree, at least not from what Kevin showed. I can't say how it holds up on large enterprise projects, but as a mental model for someone still learning the ecosystem, it's useful.

The demo used the Spotify API. Nothing complex — the point was to show how quickly you can wire up something real in .NET, not to build a production app in 45 minutes. Kevin set up the project, hit a bug partway through, and debugged it live. That was probably the most useful part of the whole session. It's easy to watch someone experienced write code and assume the process is smooth for them. It isn't. They just know how to read the error message and stay calm. Seeing that play out in real time, in front of a room full of people, was a good reminder.

The performance improvements in .NET 10 came up briefly — garbage collection changes, some JIT compiler work — but went by fast. Same with the updates to minimal APIs, which I've been meaning to actually use. A few things slipped past me and I've flagged them to read up on later. That's probably the most honest sign a session was worth attending: you leave with a reading list rather than a sense that everything was covered.

One thing I didn't expect was how much the talk made me want to actually build something. Not for an assignment — just to try the features out. That doesn't happen with every session.
