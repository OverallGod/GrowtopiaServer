# Growtopia Server
First Growtopia Private Server made with ENet.

This project has been compiled with Visual Studio 2015 (Visual Studio 2013 or older won't work!) and newer versions of VS or other compilers weren't been tested.

This project has been published under GNU AFFERO GPL license, so you need to **publish whole source code and citate orginal authors name, even if you are using your server as service**!

**TODO list:**
1. Refactor whole code, it is very hard readable and there might be problems with maintaining it
2. Try get some normal DB working or atleast save all files as BSON or some binary format
3. Write load balancer, it is very CPU expensive part because it calculates BCrypt hashes and access to database
4. Try possible to write multiple servers which only share between themselves possibly world list, player list and boradcast queue
5. Extend data which are saved now - there should be saved current clothes, inventory, login time, register time and maybe tracing hashes if you want to do proper ban system also in worlds there should be saved block extras (enabled, water, fire, etc.) and dropped items
6. Write event pool - this is needed to make delayed actions like respawning
7. Make heavy events asynchronous with possibly some good thread count (probably one or two) and connect them to event pool or use callbacks
8. Daily news (Growtopia Gazzete) should be saved to external file and not in source for easier modifying
9. Disable all loging to console and log everything to file, this will free up console for CLI

If you want to support development of this server, then make sure you contribute to this repo!

Make that sure that you subscribe my channel https://www.youtube.com/channel/UCLXtuoBlrXFDRtFU8vPy35g and enjoy :+1:

# Issue Template

Issue tracker is **ONLY** used for reporting bugs.

<!--- Provide a general summary of the issue in the Title above -->

## Expected Behavior
<!--- Tell us what should happen -->

## Current Behavior
<!--- Tell us what happens instead of the expected behavior -->

## Possible Solution
<!--- Not obligatory, but suggest a fix/reason for the bug, -->

## Steps to Reproduce
<!--- Provide a link to a live example, or an unambiguous set of steps to -->
<!--- reproduce this bug. Include code to reproduce, if relevant -->
1.
1.
1.
1.

## Context (Environment)
<!--- How has this issue affected you? What are you trying to accomplish? -->
<!--- Providing context helps us come up with a solution that is most useful in the real world -->

<!--- Provide a general summary of the issue in the Title above -->

## Detailed Description
<!--- Provide a detailed description of the change or addition you are proposing -->

## Possible Implementation
<!--- Not obligatory, but suggest an idea for implementing addition or change -->


