# Comparing and Handling the Network Complexities in Massively Multiplayer Online Games (MMOGs)

## Purpose

MMOs are a huge market, from long running MMORPGs like Final Fantasy XI and World of Warcraft, to more modern takes on the MMO stage with the likes of Fortnite, PlayerUnknown's Battlegrounds and the more recently released New World. Each of these games has a large userbase, numbering from the tens of thousands to millions of players. While they all vary heavily from each other, they all have many things in common as well, such as requiring stable netcode and enabling hundreds to thousands of players to meet and play together all at once. From the smallest to the largest, they all require companies to invest a lot of time, money and resources into developing the server infrastructure to ensre that their players have a stable, smooth experience.

This repository is for my research into a number of MMOs, exploring common issues they encounter and focusing on the network arcitecture and connection types they may use. MMOs by their nature must have a heavy reliance on a users connection, and as such the flow of data from the server to the client must be carefully managed. This data must not be too heavy on the bandwidth, and quick enough to avoid a desyncronisation issue, rubber banding, or other similar connectionr elated problems that online games can frequently encounter.

For this project, I ultimately focused on three games, all making use of mainstream IP using publicly available data, albeit with the caveat that this data might not be entirely accurate as a result of companies picking and choosing what they reveal.

| Game              | Genre         |
| -----------       | -----------   |
| Final Fantasy XIV | RPG           |
| Fortnite          | TPS Battle Royale |
| Apex Legends      | FPS Battle Royale |


## Design Methodology

A variety of methods were used, from exploring prior research to scraping data myself. Each of these methods is listed in the final document, but are focused on these key areas:

- Latency
- Version Control
- Cross-platform
- Genre
- Packet size and load
- Topology
- Security

## Findings and Results

Much like the methods used, the findings were condensed into the same key areas, then analysed to examine what techniques they use and how they can benefit the other games in the study. Ultimately it was found that FInal Fantasy XIV had the most room to improve in the connections area, particularly after its massive influx of players during the latter half of 2021, while Fortnite is in the most stable area. Apex Legends has a lot of room for improvement as wlel, particularly in security and anti-DDOS measures.




