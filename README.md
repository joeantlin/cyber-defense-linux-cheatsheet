# Cyber Defense Linux Field Guide

A Linux command reference for cyber defense and security hardening work. It's one HTML file — commands, tools, quick-start checklists, and a glossary — that you can search through instead of digging through old notes.

**[Live version →](https://joeantlin.github.io/cyber-defense-linux-cheatsheet/)**

## Why I made this

I built this while prepping for a CCDC (Collegiate Cyber Defense Competition) team, mainly because I got tired of switching between slide decks and my own notes every time I needed a command. Putting everything into one searchable page made more sense than digging through either.

I keep adding to it as I learn more about Linux and network hardening. This is the first entry in what I'm planning to grow into a larger collection of security notes.

All the commands, notes, and structure came from my own studying and class materials. I used Claude and a couple other AI tools to help turn that into an actual working page quickly instead of hand-coding it from scratch — I fed it the info I'd gathered and went back and forth on formatting until it worked the way I wanted.

## What's in it

- **Linux Commands** — grouped by what they're actually used for (permissions, users, processes, networking, forensics, etc.) instead of alphabetically, so you're not stuck guessing the command name to find it
- **Programs & Tools** — longer write-ups for the bigger stuff: iptables, tmux, PAM, cron, rootkit scanners
- **Quick Start & Routine Checks** — three checklists: one for just looking around a new box, one for actually setting up a firewall, one for network config. Kept them separate so it's always clear whether a step is just checking something or changing something
- **Reference / Glossary** — plain explanations for concepts like permission math, PAM, CIDR notation, stateful firewalls, IOCs — the ideas behind the commands

A few things built into the page to make it faster to actually use:
- **Search bar** — filters straight down to matching commands, checklist steps, and glossary terms as you type, instead of scrolling through everything
- **Copy buttons** — every example command has a one-click copy so you're not manually highlighting text mid-task
- **Cross-references** — related commands link to each other (like `chmod` pointing to `chown`), so clicking one jumps you straight there and expands it instead of making you go hunt for it yourself

## How it works

Just one `index.html` file. No build tools, no dependencies, nothing to install. You can download it and open it offline and it still works fine.

## About me

Cyber security student, building out Linux and network defense skills through competition prep and independent practice.

- GitHub: [@joeantlin](https://github.com/joeantlin)
- LinkedIn: [joe-linares](https://www.linkedin.com/in/joe-linares)
