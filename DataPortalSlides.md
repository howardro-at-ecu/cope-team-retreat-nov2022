---
marp: true
theme: default
author: "Rob Howard"
title: "So you're thinking about building a geospatial data portal?"
footer: "CoPe Team Retreat — Rob Howard — November 4th, 2022"
paginate: true
---

<style>
    :root {
        font-family: Quattrocento;
    }

    a {
        color: #592A8A;
        text-decoration: underline solid #FEC923 0.2em;
    }

    strong {
        color: #592A8A;
        font-size: 1.2em;
        font-weight: 900;
        text-decoration: underline solid #FEC923 0.2em;
    }

    strong.tag {
        color: #FFFFFF;
        background-color: #FEC923;
        border-radius: 2px 18px 4px 18px;
        padding: 4px 8px 4px 8px;
    }

    em {
        font-style: normal;
        font-weight: bold;
    }

    h1, h2, h3, h4, h5, h6 {
        color: #592A8A;
        font-family: Oswald !important;
    }

    h1 > strong,
    h2 > strong,
    h3 > strong,
    h4 > strong,
    h5 > strong,
    h6 > strong {
        color: #FEC923 !important;
        background-color: transparent !important;
        font-family: Oswald !important;
        font-size: 1.2em;
        line-height: 0.9em;
        text-decoration: none;
    }

    ul li::before {

    }

    ol > li::marker {

    }

    section.masthead {
        padding-left: 15%;
        padding-right: 15%;
        /* padding-top: 15%; */
        text-align: center;
    }

    section.masthead h1 {
        font-size: 2.25em;
    }

    section.masthead h1 strong,
    section.masthead h2 strong,
    section.masthead h3 strong,
    section.masthead h4 strong,
    section.masthead h5 strong,
    section.masthead h6 strong {
          padding: none !important;
          text-shadow:
           -1px -1px 0 #592A8A,  
            1px -1px 0 #592A8A,
           -1px  1px 0 #592A8A,
            1px  1px 0 #592A8A;
    }

    section.no-footer footer {
        display: none !important;
    }

    section.section-purple {
        background-color: #592A8A;
    }

    section.section-purple h1 {
        color: #FFF;
        font-size: 4em;
        text-align: center;
    }

    section.section-purple h2 {
        color: #FFF;
        font-size: 2em;
        font-style: italic;
        text-align: center;
    }

    section.section-purple footer {
        display: none;
    }

    section.thank-you h1 {
        font-size: 4em;
        text-align: center;
    }

    section.thank-you h2 {
        font-size: 2em;
        text-align: center;
    }

    section.thank-you footer {
        display: none;
    }
</style>

<!-- _paginate: false -->
<!-- _class: masthead no-footer -->
![bg opacity:0.3](ncca_beach.jpg)
# So, you're thinking about building a geospatial __data portal__?
### <br><br><br><br><br>
### __Rob Howard__<br>Department of Geography, Planning<br>and Environment

---
<!-- _class: no-footer -->
![bg left:38% drop-shadow](me.jpg)
# Who is __Rob Howard__?
* __Research Associate__ in the _Department of Geography, Planning and Environment_
* __Co-Director__ of the _ECU Center for Geographic Information Science_
* Original __developer__ of the _North Carolina Coastal Atlas_ along with Dr. Tom Allen
* I do mappy things...

<!-- ---
# The __game plan__
1) In the beginning...
1) ArcGIS Online, OpenData, Hubs and more...
1)   -->

---
<!-- _class: section-purple -->
# In the beginning
## ( there were developers )

---
![bg left:38%](gis_split.png)
# In the early days
* The UNM MapServer, ArcIMS, and eventually ArcGIS Server were our go-to solutions for hosting web maps. 
* Geospatial data portals were rare, but those that existed were typically static assemblages of layers.
* No solution existed that combined maps, narrative and multimedia.
* Very IT intensive: server management, networking, and infrastructure. 

---
# Our proposed solution
![bg right 90%](ncca_logoswarm.png)
For all of these reasons, web GIS was relegated to organizations with immense resources.

In the summer of 2012, Dr. Tom Allen approached me about developing the North Carolina Coastal Atlas. Our goal was to make this technology accessible to anyone living, working or recreating in ENC.

---
![bg left](ncca_needs.png)
# Needs assesment
A needs assesment survey was distributed to potential stakeholders to determine how they might use a web-base data portal.

A summary of the responses is seen at left.

---
<!-- _class: no-footer -->
![bg 90%](ncca_homepage.jpg)
![bg 99%](ncca_catalog.jpg)

---
<!-- _class: no-footer -->
![bg fit](ncca_flowchart.png)

---

# Key takeaways
* _Thousands_ of person-hours were invested in developing the NC Coastal Atlas platform.
* Many functions had to be implemented _from scratch_. 
* _Thousands_ of lines of code were written. Most of them were in ES/ActionScript for the map viewer. Those were the days.
* Server hardware was the largest non-labor expendature.
* More than a year between concept and product.

---
<!-- _class: no-footer -->
![bg](ncca_beach.jpg)

---
<!-- _class: section-purple -->
# Is there a better way?
## Not back in 2012. Now, absolutely!
---
# Zero coding required
Today, almost everything proposed in the original NC Coastal Atlas information model can be accomplished with little or no custom code.
* _ArcGIS OpenData_
  A built-in feature of ArcGIS Online that allows rapid deployment of data portals from existing catalogs of data.
* _ArcGIS Hub_
  An easy-to-configure cloud platform that organizes people, data, and tools to accomplish Initiatives and goals.
* _ArcGIS StoryMap_
  Immersive, map-centric stories right in your web browser.

---
![bg right:38%](MapPinIntheDesert_Half.png)
# So, that's it?
Not if you want your data portal to be successful.
* Data portals are now a commodity. Anybody came build one very quickly.
* The key differentiator is user experience (UX). If possible, conduct a usability study with a prototype of your portal.
* Build thematic applications targeted to specific problem spaces, e.g., a decision support tool for municipal governments to monitor flooding.

---
<!-- _class: section-purple -->
# Questions?

---
<!-- _class: thank-you -->
# Thank you!!
## If you have any delayed questions or comments, please feel free to reach out to me at howardro@ecu.edu