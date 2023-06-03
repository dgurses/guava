# Guava: An exciting delicacy across Southeast Asian cultures
<param ve-config 
       title="Guava Essay"
       author="Dünya Gürses"
       banner="https://raw.githubusercontent.com/dgurses/guava/main/pictures/guava2.png"
       layout="vertical">
       
Although not native to Southeast Asia, the guava has become a delicacy across many of the region’s cultures. From street names to cocktail recipes to traditional poetry, the guava has garnered culinary and cultural significance in Southeast Asia over the years. 
<param ve-image 
       url="https://raw.githubusercontent.com/dgurses/guava/main/pictures/guava2.png"
       title="Guava drawing" 
       description="William Farquhar Collection of Natural History Drawings"
       attribution="National Museum of Singapore"
       license="CC BY-NC">

Guava trees are small to medium-sized trees that can grow up to 10 meters tall. They have a short, thick trunk with smooth, brownish bark and a broad, spreading crown of branches. The leaves are oval-shaped and glossy, with a prominent midrib and veins. The flowers are white and have five petals, and the fruit is round to pear-shaped, with a thin, yellow or greenish skin and sweet, juicy flesh that turns from white to red as the fruit ripens. The fruit tree is native to Central America, northern South America, and the Caribbean but is widely cultivated throughout all of the tropics and subtropics.
<param ve-image 
       url="https://raw.githubusercontent.com/dgurses/guava/main/pictures/guava2.png"
       title="Guava drawing" 
       description="William Farquhar Collection of Natural History Drawings"
       attribution="National Museum of Singapore"
       license="CC BY-NC">

The guava was likely brought to Southeast Asia by Spanish and Portuguese colonizers in the 15th and 16th centuries who introduced various tropical crops to the region during the colonial era. The exact details of how guava was brought over are unclear, but it is believed that the Spanish introduced it to the Philippines and the Portuguese into India.[^1] The guava tree thrived in Southeast Asia due to its adaptability to the region's tropical climate and soil conditions. Over time, the guava tree became naturalized, and it is now widely grown throughout the region, especially in countries like Indonesia, Malaysia, and the Philippines. With a long history in the region, the plant has become ingrained in many Southeast Asian cultures, whether it be traditional medicine or local food cultures, and is still enjoyed today by many.
<param ve-image 
       url="https://www.nas.gov.sg/archivesonline/watermark/picas_data/tn_pcd/19980007350-8262-3202-1113/img0086.jpg"
       title="Guava fruit" 
       description="Photo taken in 1989"
       attribution="National Archives of Singapore"
       license="CC BY-NC">

In Malay/Indonesian the guava is called *jambu batu*, the word *jambu* having originated from Sanskrit. In Sanskrit jambu refers to a fruit or a rose apple, and is used to refer to a range of apple species in the Malay-speaking world. Of the “jambu (a species of apple) there are the jam bukling merah, (red) ayer mawa, (which tastes like rose water,) jambu bija, the guava, irong the cashew apple, another sort called britis”.[^2] Jambu batu is the name of the common guava with white flesh. When its flesh ripens and turns red the fruit is then referred to as *jambu batu merah* which simply translates to red guava. Jambu is used colloquially in Singapore to say pretty/beautiful and batu means rock in Malay so jambu batu literally means pretty rock. 
<param ve-image 
       url="https://www.nas.gov.sg/archivesonline/watermark/picas_data/tn_pcd/19980007350-8262-3202-1113/img0086.jpg"
       title="Guava fruit" 
       description="Photo taken in 1989"
       attribution="National Archives of Singapore"
       license="CC BY-NC">


## This is a quick Markdown tutorial. Two hashes precede a heading. You can use these headings to divide sections of your essay.

*This makes things italics*. 

This is how you add a footnote. [^1]

[This is how you add a link](https://www.juncture-digital.org/KatherineMEnright/speciesstories/)

This is how you add a mouse-over information panel from Wiki data: <span eid="Q170662">Mangosteen</span>
You can find the wikidata IDs by searching for proper nouns [here](https://www.wikidata.org/wiki/Wikidata:Main_Page). The ID is the series of digits following the letter Q.

**There's no spell-check feature built in, so keep a careful eye out!**

## Adding Images
       
You can use the QID tag within a sentence. For example: The <span eid="Q170662">mangosteen</span> is a non-native fruit found in Singapore. This is the code you use to add an image. Make sure to **close the tag**. It starts with **<param ve-image** and ends with a closing **>**. Within these tags, you can add information to help the program locate and describe the image. **While these examples are images, we can also include textual sources (particularly primary sources) in the media viewer where appropriate.**
<param ve-image 
       url="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       title="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection.">
       
<span eid="Q271648">Marianne North</span> painted this painting of a 'Singapore monkey' amongst mangosteen fruits in 1875. You can also include "attribution" in the image information.
<param ve-image 
       url="https://d3d00swyhr67nd.cloudfront.net/w1200h1200/collection/LSW/RBGM/LSW_RBGM_MN_CD6_577-001.jpg"
       title="Flowers and Fruit of the Mangosteen, and a Singapore Monkey" 
       description="Held by Kew Gardens."
       attribution="Marianne North"
       license="CC BY-NC">
       
These are both examples of images added *from urls*. This is the preferred method. However, there might be some images you have to upload yourself. That's totally fine! Ideally, these files should be *as small as possible* and only .jpg or .png files will work. You should create a folder in your repository called "media" and upload the file there. Then, for the url, just copy and paste the item path: "media/{filename}.jpg". For more information on adding multiple images, comparisons, curtain sliders, and for how to zoom into particular sections of an image, check out the documentation [here](https://github.com/JSTOR-Labs/juncture/wiki/Visual-Essay-Image-Tag).
<param ve-image 
       url="https://raw.githubusercontent.com/dgurses/guava/1add87395eb2bc0a4e8d2c8b8bb362cbe91cedf2/pictures/guava.png"
       title="Victoria crowned pigeon"
       attribution="Katherine Enright">     
## Map

Mangosteens are found in Singapore. This takes a base map and sets the center to Singapore. The code after creates markers for different species, for instance, or to mark particular places on a map.
<param ve-map center="1.35, 103.9" zoom="11">
<param ve-map-marker
       url="https://leafletjs.com/examples/custom-icons/leaf-green.png"
       coords="1.3621, 103.8198"
       size="38, 95"
       iconAnchor="22, 94"
       shadowUrl="https://leafletjs.com/examples/custom-icons/leaf-shadow.png"
       shadowSize="50, 64">
<param ve-map-marker
url="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Pinz%C3%B3n_azul_de_Gran_Canaria_%28macho%29%2C_M._A._Pe%C3%B1a.jpg/220px-Pinz%C3%B3n_azul_de_Gran_Canaria_%28macho%29%2C_M._A._Pe%C3%B1a.jpg"
       coords="1.4126, 103.9577"
       size="129, 170"
       circle="true">
    
    
You can create custom regions just by drawing shapes (no coding needed) using [geojson.io](https://geojson.io/#map=2/0/20). Then you can download the shape file and add it to your juncture media file as a map layer. Let's imagine this is the distribution range of your species.

<param ve-map center="1.35, 103.9" zoom="2">
<param ve-map-layer geojson url="/media/demomap.geojson" title="Sample Distribution"> 

## Add a YouTube Video
You can take the id from the YouTube URL. You can also define the start time with start="0:20" (for instance).
<param ve-video id="5upF4rJUxC4" title="NYBG 2019 Corpse Flower Timelapse">

## Add a Timeline
This uses the [Knightlab platform](https://timeline.knightlab.com/). The back-end, for you to use, will just be a googlesheets (so it's user friendly!). Here's an example:
<param ve-knightlab-timeline source="1T9E8QZRT7ZFFmb55uLpJUSnELKuqSsXlLmNuVXvOC_I" timenav-position="bottom" hash-bookmark="false" initial-zoom="1" height="640">


## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       url="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       title="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection.">
<param ve-map center="Q334" zoom="11" prefer-geojson>

# References

[^1]: David Mead, “Types of jambu,” Sulang Language Data and Working Papers: Topics in Lexicography, no. 21 (2013): 1-11.
[^2]: “Anderson’s Malayan Peninsula,” Singapore Chronicle and Commercial Register, January 16, 1836, Page 1, https://eresources.nlb.gov.sg/newspapers/Digitised/Article/singchronicle18360116-1.2.2?ST=1&AT=search&k=jambu%20batu&SortBy=Oldest&filterS=0&Display=0&QT=jambu,batu&oref=article.
