# NoDo <Note-Doc>

> Fastest, most performant, individual contribution space, that evolves with contributors

### Philosophy -

There are, fundamentally, 2 classes of software
- standalone and used by one person to create information
- networked software - used to distribute information and collaborate. 
    
This means that the primary force driving the software forward should differ for both the classes of software.


Notes is primarily a standalone product, wherein a user can take notes, as quickly as possible. 
The collaboration built on top of the Notes is flawed, this makes the standalone product suck, by overloading it with all the collaboration overhead.


NoDo is an old way of thinking about the notes, that is notes as standalone software, and fundamentally a new way of thinking about how to add collaboration to the notes. Collaboration should not be a performance overhead or distraction, every new node or collaborator should add value to the complete doc.

  
# NoDo is a replacement for - Paper, Confluence, GDocs, Coda?

## Use Case -
- A personal [ Notes + Tasks ] writing app
- Clean, minimal, functional
- A collaboration app, that works with the collaborator’s own tools, that is, their own notes app, or tasks app
- Helping remote teams collaborate, while being productive with their own set of tools
    

### Features - 
- Fast, beautiful, minimal, distraction-free
- Never come in between a user and their note-taking flow
- 2 way, deep integration with other tools
- Everyone can bring their own tool - BYOT  ¯\_(ツ)_/¯
- Notes tool 
- Task List
- [PLUGINS] - below
- [SPACES] - below
- [TABLES] - below

#### Inspirations

![](https://lh5.googleusercontent.com/kckRAQOjuRq25LTUo8VAc5dgNy0nXKouLfgyiy-utVdcFPZ0TDDfSEXBEMuVUxsmhAwWlHkeRsAZq4BF2jjoce4niBoxGFSr009jEzFKhdgRDDdz3Sl5OucOhBGyhWFYITU3L4Un)

![](https://lh5.googleusercontent.com/O-x6Ru5mwbovN2Ng0xXfeoUcTGeslY5BrecvoA6nCvtE2AUerBbn89mRVqS4g1twhHT4UdpVTbKMrzGbAFBlK_2_cl6zJ-f4nrpJdB16ztzhHmn0MKGvr0_zu8UXTk-21OvRFlVl)

![](https://lh3.googleusercontent.com/pGOqzFlQzCxnPceTOkY8HXQRIESVj2JX1h8saNq6-VSkqwfKa54mielGw3fo3M0TEQcRGSy4Z36f4zv2GJzJCsYfz6Q_Am4BGHj1lR5WlwusfhGBdYTppvv2kYdv2T5uOm9gXUdW)

![](https://lh3.googleusercontent.com/yGNtavYOTCVpL4sNk579TH9Y4ZVFaO43_395693J9lxDhFzMyCHrZinJ5AQ_0K4Q7VSelaelgjyc0OHd40IJi7f9eV6Dt5nvMEdXNNnfXbbApA_9g2D-kOmXSem7jYrX0-E7A92r)

![](https://lh6.googleusercontent.com/CfrQy210KN9Acvt-gVkDs0ejel9KAERIJY9DFMDO83bbS7724L9D_55RFN8RpS5RmmtJCqh2gmO78f8Tj3g4UEF_AtZrIM2lfd1eFsXrUCMeOTzVrEaXBnpbZiEvOp6EP-io0mor)

  

-   Contd...
- Runs on any platform
	- Old laptop
	- Old browser
- Write first, sync later    
- Slash commands
	- /image from <url> place <left side> size <30x30>
	- /table from <url> with columns <x, y, z>
	- /mute
	- /section for <collaborator>
	- /todo <id> completed
- Plugins like FIGMA, help a user extend the NoDo with useful components
	- Whiteboard plugins
	- Calendar plugins
	- Named-entity recognition tool
	- Compile to HTML, Publish as a webpage
	- Image component
		- OCR for handwritten scans
		- Write over images
-   Integration | a continuously evolving web of user’s information
	- Tweets
	- Photos
	- Screenshots
	- Posts
	- Kindle highlights
- Two-way syncing tables, connected to external data sources
	- Databases
	- Excel
	- GSheets
    
-   <SPACE> - private spaces for collaborators, to write their own notes, and build their own agenda
	- Space/ Section/ - something
	- A hierarchical web of documents
	- Expand/ Collapse the <SPACE> from the main doc, to view the complete contents
	- The collapsed state would show the highlights from the SPACE
	- <SPACE> would always be owned by a single <OWNER>
	- <SPACE> sections could be marked - public, private
	- To add to the <SPACE> - use the <COLLABORATION TOOLBAR> - similar to writing on the margins of a book’s page
    

### Challenge
- Every collaborator would be using their own set of tools, this makes live-syncing extremely hard, but we have decided to prioritize the note-taking experience, so take notes and sync later is a perfect mechanism
- <SPACES> are lazily loaded
- The NoDo can be extremely large, only load 3 pages in the memory at a time - The page Visible, the page-up page and the page-down page. Unload any pages beyond these 3 pages from the memory.

### Interface - 

![](https://lh5.googleusercontent.com/UlvfYFcMoqIIL9tYCYFoJw7J42jx2-5Kfg0tHybKe4liODLEX5b4aV5A6z2LOg4KzT84zYPwRt4d86iJ5s2cuJsca3V53ZBe4xc_3VjpLOz_0BNRsmrL9HB6OX4SsHkxc8Dc4X5F)

![](https://lh4.googleusercontent.com/PqQndCIs3nN_NZoNf-DGTjN-auWf0toJnzR_FvAJpf0Y6b__dvnjbokc1qQIOw4dudlEE6KNQn0RauDTqvJf56KKwIpgDwivTDFwgqMTVv3Ng0mwcWa35KpxGfPXS0boR-SeoJ8z)