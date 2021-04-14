The best way to tell this story about boundary lines is to show them — within the pages of this book — to make their hidden power more visible.

My desire in mapping the lines is partly driven by my need to visualize how geographic space changes over time.
If you want to tell a story about how neighborhoods change over time, or racial boundaries shift, or demographic patterns rise and fall in adjacent areas, then you need to supplement your narrative with pictures. Show me the map.

Surprisingly, it was relatively uncommon for historians to make or show maps, even simple ones, when I began this project in early 2000s. . . ,
Around that time, I attended the Urban History Association meeting in Pittsburgh PA to learn more about the field. I recall attending at least 18 different paper presentations during that weekend, where scholars stood up and read their papers. Guess how many of them actually showed a map, either on a transparency or paper handout, to communicate their scholarly findings? Only 2 out of 18.
At the same time, the academic book publishing industry was declining, and it became more difficult to persuade editors to include color maps, or even several black-and-white maps, in print books. Even if you were successful, those maps were a limited view of what was possible to show.

Insert Hillier; Colin Gordon

Mapping is still not part of the curriculum for the next generation of historians who are in undergraduate or graduate schools today. So I have tried to make my process as transparent as possible, and as easy as possible, in the How part this book, as well as an introductory textbook-in-progress, Data Visualization for All.

When I first began this project in YEAR, mapping the lines meant learning geographical information system (GIS) mapping tools, commonly used by cartographers and municipal planners to create static maps, either on paper or as PDFs on computer screens.
I learned how to blend historical census data and boundary lines to create basic static maps, which I could insert in the pages of a book, like this:
[INSERT static Hartford thematic map]



Then I learned how to create a website for the Cities, Suburbs and Schools Project, and began to experiment with actively telling more stories with maps online.
The tools were still very limited. ArcGIS was expensive and took me years to learn to do basics, with frustratingly stupid obstacles.
Web editing tools were not much easier: first some MS product I've forgotten(?), then Dreamweaver, which still required me to learn quite a bit of coding in order to do very simple things, like placing text and tables on a page.
All of these tools were not cheap, and had a steep learning curve, meaning that it was not feasible for students to learn, unless they took an entire course and specialized.
Since I wanted to tell historical stories, emphasizing change and continuity over time, I experimented with using ArcGIS to create an animated map of metro Hartford population change over a century, and displayed it as an animated GIF on the web, which looked like this:
[my first animated GIF]

The growth of web technology changed everything during the next few years.
MapQuest and others provided interactive maps on the open web, and allowed users to zoom and pan, and find addresses.
But Google Maps became bigger, partly because creative users could access the code to create "mashups" using their own data.
At first, Google blocked? or ignored? this practice, but then realized their interest in releasing an application programming interface (API), or instructions for how to write your own code to access their platform. Google Maps continues to be a proprietary platform, tightly controlled by the company. But they openly shared and documented their API, meaning that if you could learn some some basic coding of the web -- using HTML, Javascript, and CSS -- and followed Google's guidelines about source credit and access -- you could display an interactive Google Map on your website and modify it to include your own data and images.
	Trinity programmer Jean-Pierre Haeberly created SmartChoices with me and my students in 2008. . .[no longer live site, but see movie of subsequent version]
I did not learn how to do this until I began working with UConn MAGIC. . .  and the first mashup we created was this:
[neighborhood change interactive map]

As a library committed to the free distribution of information and its long-term preservation, MAGIC also serves as the official repository for map data and finished maps for On The Line. In addition, Trinity College librarians also work with me to create digital archives of documents, images, and video collected for this book. We initially began storing essays and documents in PDF format on the Trinity College Digital Library (or whatever it's called), a proprietary platform hosted by BePress, and now we store more items, especially multimedia ones, on CT Digital Archives, a more flexible open-access platform hosted by UConn.

I also learned WordPress, a much easier web authoring platform, basically a word-processor connected to the web.
WordPress also was open-source code, with an active community of people developing plugins and themes to add new features and customize appearances. I learned how to modify WordPress at THATCamp events.
First version of On the Line consisted of web pages and screenshots, with direct links to maps on other sites.

Tools became easier over time. I learned how to create thematic polygon maps, using my own data and geographic boundaries, using Google Fusion Tables in YEAR. This was much easier to teach students how to use. And our maps became more elaborate with Derek Eder's Searchable Map Template
	[insert sample map]

Around this time I learned how to embed iframes (or HTML code snippets to make one website appear seamlessly inside another website)
Then discovered Pressbooks, an open-source WordPress derivative, that simplifies book publishing in multiple formats XYZ
Learned how to embed two versions of maps inside books like this one: a static image (for print and digital book editions) and a live interactive map (for web editions).

Now my MAGIC colleagues and I have shifted our interactive map creation from Google to Leaflet, an open-source library that requires HTML/JS/CSS coding, but offers greater flexibility with open-source base map providers. Furthermore, learned to share our open-source code on GitHub, and host live websites on GitHub Pages, which makes it much easier to share map templates with others.
[insert Leaflet map]

To be clear, most of my mapping work focuses primarily on the visual presentation of data. My collaborator Diane Zannoni and I have done some spatial analysis of schooling and housing data. . . .  Other scholars in geography and history have done much more spatial analysis. But in my mind, a primary goal of this book is to tell the story about lines and show them, to


US School district boundaries since 1995 at NCES nces.ed.gov/programs/edge/…; School Attendance Boundaries (inside districts) since 2009 at SABINS sabinsdata.org; see github.com/EdBuild for R scripts/data for former EdBuild web.archive.org/web/2020062517…
