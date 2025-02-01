---
title: "3 techniques to create easy figures for your research paper."
date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["markdown","pandoc","presentation","time-saving"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: true
draft: false
mermaid : true
hidemeta: false
comments: True
description: "Presentation of three framework that allow you to create figure for your paper only using text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
math: true
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: false
cover:
    image: data/images/featured.png 
    # image path/url
    alt: "Image test" # alt text
    caption: "Image of a feature" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
    
# editPost:
#     URL: "https://github.com/<path_to_repo>/content"
#     Text: "Suggest Changes" # edit text
#     appendFilePath: true # to append file path to Edit link
---

Some description associated with the article it should be long enough in order to be displayed but not too long 



{{< mermaid >}}
graph LR
    A --> B
    B --> C
{{< /mermaid >}}



{{< mermaid >}}
flowchart LR
    y("👫 You") --> h{"🤝 Found this helpful?"}
    h --> |Yes| r[/"⭐ Check out my featured posts!"/]
    h --> |No| su[/"📝 Suggest changes by clicking near the title"/]
    click r "/categories/featured" _blank
{{< /mermaid >}}




{{< mermaid >}}
timeline
title Plan du Cortège et Réception
13h10 : 🚗 Rendez-vous au Parking Mégarama (44 Av de la Longue Bertrane).  ➡️ Organiser le cortège et attendre les voitures.

13h20 : 🚗 Départ pour la Mairie de Saint-Ouen (~13/14 min).

13h45 : 📍 Arrivée à la Mairie.  ➡️ Tour du rond-point avec klaxons. 🅿️ Parking payant ou à proximité.

14h20 : 🎉 Entrée à la Mairie.  ➡️ Confettis & alignement.

14h45 : 🎊Sortie avec Confettis.

18h20 : 🏠 Rendez-vous à La Scena (2 Av Henri Barbusse, Bobigny).  🅿️ 4 places dédiées + rue.  🎉 Réception.
{{< /mermaid >}}