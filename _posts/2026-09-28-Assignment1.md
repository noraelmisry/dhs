---
title: "Assignment 1"
last_modified_at: 2026-09-24T12:00:00-05:00
tags:
  - static sites
  - Markdown
  - Interactive Map
  - R
  - F26
---

Maps are useful visual tools that help individuals understand different places. However, maps are not always complete or entirely objective, as the information they contain can be influenced by the sources used to create them. For Assignment 1, I used GeoNames data to create a map of Egypt, a country that I am familiar with. I filtered the dataset using feature codes to highlight geographic features that I found interesting. Through this process, I explored how the way geographic data is collected, categorized, and displayed can influence how we understand human space.

Before actually beginning this assignment, I knew I had to choose Egypt. I was born and raised in that country, my whole family is Egyptian, and it is the only place I have truly known before coming to the UAE to study at New York University Abu Dhabi. Since I have lived in Egypt my whole life, I have come to know many different areas within the country. I have visited the pyramids on multiple occasions, and I have seen both seas that border the country. I felt very confident about choosing Egypt to help build my first map. I also thought that choosing a country I already knew well would make it easier for me to recognize when the data seemed unusual or incomplete.

<div style="width:100%; height:70vh;">
  <iframe
    src="{{ '/assets/maps/EG_mountain.html' | relative_url }}"
    style="width:100%; height:100%; border:0;"
    loading="lazy">
  </iframe>
</div>



When looking at the data, I was shocked to see that it had 35,025 rows. A lot of this data consisted of places I had never heard of before. I saw that there were many places listed as mountains, about 3,000, even though I never knew that Egypt had that many mountains. I decided to use mountains as one of my feature codes, along with pyramids, since that is what Egypt is known for. I also chose to use sections of lakes as my third feature code to showcase that even though Egypt is a dry country, it still has many bodies of water. I specifically chose sections of lakes instead of lakes to better populate the map, since if I chose to only put lakes, it would only show two lakes, even though Egypt has more lakes than that. I wanted my map to show some of the diversity within Egypt rather than focusing only on the features that are most commonly associated with the country.

However, when I saw the map, I realized that I had to change the mountain feature code since there were too many points, and it was essentially the only data that could be seen on the map. Thus, to not overpopulate my map with dots representing mountains, I decided that hills were the second-best option to highlight the variability of my country in terms of its flatness.


<div style="width:100%; height:70vh;">
  <iframe
    src="{{ '/assets/maps/EG_featuremap.html' | relative_url }}"
    style="width:100%; height:100%; border:0;"
    loading="lazy">
  </iframe>
</div>


When looking at the final map, I realized that I was learning new things about my country, but there were also many points missing. For instance, I had no idea that Egypt had that many hills. When plugging in the feature codes, it said that there were 99 hills. When I Googled this, it turned out that we actually have over 3,000 mountains and hills. So, the 3,000 mountain data points were also a mix of hills, and now this data only represents hills. However, I noticed that many pyramids were missing from this map. It only showed 24 pyramids when, in reality, there are over a hundred. The only data I believe was mostly accurately represented was the sections of lakes. This is because Egypt has about 15 major named lake systems, so by sectioning them off into 57 points, the data looks more scattered, and it becomes clearer to see that Egypt is not all desert and does actually have some bodies of water.


I partially regret not choosing to add borders as a feature code, though. I chose not to add them since they did not come with that much data, but the border between Egypt and Sudan truly has significant history to it. If you look closely at the map, you will see that there is a small piece of land sitting between the borders that is completely unclaimed. This unusual border between Egypt and Sudan dates back to the period of British control in the region. In 1899, Britain and Egypt established a border between Egypt and Sudan along the 22nd parallel. However, in 1902, Britain created a separate administrative boundary to account for local tribal and administrative arrangements, which placed some areas differently from the original border. This resulted in two disputed areas: the larger Hala’ib Triangle, which is claimed by both Egypt and Sudan, and Bir Tawil, which neither country claims. Egypt generally follows the 1899 boundary because it places the Hala’ib Triangle within Egypt, while Sudan follows the 1902 boundary because it places Hala’ib within Sudan. As a result, claiming Bir Tawil would weaken either country's position regarding Hala’ib, leaving Bir Tawil as one of the few pieces of land in the world that is not claimed by a recognized state.

This proves that beyond Egypt’s natural features and pyramids, even the border has so much history to it. It also made me realize that I initially thought of geographic features mainly in terms of physical features such as mountains, lakes, and pyramids. However, borders can also be viewed as important geographic features because they have political and historical meanings.

Throughout this assignment, I was incredibly impressed by how GeoNames has such a significant amount of data for every country worldwide. I saw that a lot of countries on the website have their own ambassador, meaning that there are people who help GeoNames with geographic information about that country. GeoNames says an ambassador can help with questions about administrative divisions and finding data sources, such as postal services, statistical offices, national mapping agencies, universities, etc. This makes GeoNames a data assemblage due to the fact that there are many people and organizations working together to compile data from various sources.

For Egypt, I found that GeoNames does not currently list an ambassador, which raises questions about where the information about Egypt comes from and whose geographic knowledge is represented in the database. When researching this, I found that the data mainly comes from National Geospatial-Intelligence Agency (NGA) data, international organizations and datasets, geographic databases such as Wikidata, and other government and mapping agencies. This was especially interesting to me because I initially assumed that information about Egypt would primarily come from Egyptian sources. Instead, I found that geographic information about Egypt can be produced and organized by institutions outside of Egypt. This made me think more critically about the idea that a map is simply showing objective facts, when in reality, decisions about what gets recorded and how it gets categorized can affect what we see.

After completing this assignment, I have developed several new skills. This was my first time ever coding anything, so even being able to follow the instructions on the Posit notebook was a personal challenge, but I was able to accomplish it successfully. I found that navigating between Visual Studio Code, GitHub Desktop, and my GitHub website was the hardest part of this assignment. Nevertheless, with the help of my peer and dear friend Nahla Omran, who provided me with technical assistance, I was able to navigate between each of these websites and apps to create my own website and map. Although the technical part of the assignment was difficult at first, I became more comfortable with the process as I continued working on it.

I can also definitely apply these new skills to my future as a Legal Studies major. After learning how to create a map with various features, I can build maps for my international law and genocide classes to provide a visual demonstration of areas in which mass violence occurs or has occurred. Maps could help me understand how geography, borders, and proximity to different locations can affect historical events.

Overall, this assignment showed me that maps are more than just visual representations of places. Although I was already very familiar with Egypt, creating my own map allowed me to discover geographic features that I had never heard of before, while also making me question why some features were missing or inaccurately represented. The differences between the number of features in GeoNames and the numbers I found through additional research demonstrated how the sources and categories used to create a dataset can influence the way a country is represented. Learning that GeoNames is a data assemblage also made me realize that geographic information is not produced by one single source, but is instead collected and combined from many different organizations, databases, and individuals. This means that the map I created represents only one version of Egypt rather than a complete picture of the country. At the same time, learning how to work with geographic data and create a map was a valuable new skill for me. As a Legal Studies major, I can see myself using these skills in the future to visualize borders, territories, and locations in my international law and genocide courses and eventually in my career as an international lawyer. Ultimately, this assignment taught me not only how to create a map, but also to think more critically about where the information on a map comes from and how it shapes our understanding of a place.

Thank you for taking a look at the wonderful map of Egypt that I was able to create!