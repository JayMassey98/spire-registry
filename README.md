# SPIRE Registry


Structured Project Indexed Reference Entries (**SPIRE**) is a simple, plain-text knowledge base registry for keeping a project's information organised and easy to find.

This can start as a standalone repository, but is designed to slot right into a larger one, for example as a submodule or a copied plain folder under `docs/spire-registry`.


## Starting Point

Open **`0000_Registry_Overview.txt`** first; it holds the rules for the knowledge base, and almost never changes.

Open **`0100_Project_Summary.txt`** after; it holds the live summary of the project, which may change frequently.


## Why Use SPIRE?

As a project grows, its information tends to scatter, duplicate, and drift out of date; SPIRE solves this by giving you:
 
- **Fast Familiarisation** - You, new team members, or even AI assistants can get up to speed from just a few focused documents instead of one daunting file
- **Predictable by Design** - Every document follows the same template in an indexed structure, so reading one document teaches you how to read them all
- **Single Source of Truth** - Each piece of information has exactly one designated home, making it easy to find the right answer in the right place, every time
- **Separated by Purpose** - Established knowledge, open resolutions, active work, and past evidence are deliberately kept siloed within their dedicated series
- **No Lessons Lost** - Past evidence, including failed attempts and dead ends, is intentionally preserved to avoid accidentally covering the same ground twice
- **Traceable Changes** - All document edits show up as clean, readable diffs, so you can see exactly what changed and when at any point in the project's life
- **No Dependencies** - Since every document is just a version-controlled plain text file, no special tools are required to read, write, or maintain any of them
- **No Lock-In** - If you ever decide to stop using the SPIRE framework, no knowledge is lost, because the documents simply remain readable plain text files