---
# Change these five lines as soon as you copy this starter.
title: Student Union Building
author: Victor Sanchez-Valdez
category: Student Resource                # change to a category from the student guide
header-image: UNM SUB (old).jpg  # the filename of your own image
header-caption: New Mexico's Digital Collection

# Fill these in later, once your research is under way.
card-description: From used and old to new and larger. The student union rises after years of a cramped building due to the increase of students. 
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---
The Student Union Building (SUB) at the University of New Mexico (UNM) has been an important part of student life for decades. Located on UNM’s main campus in Albuquerque, New Mexico, the SUB serves as a place where students can eat, study, socialize, and participate in campus activities. However, the building has also witnessed major historical events, including student protests, renovations, and changes in university culture. Its history reflects the growth of UNM and the changing needs of its students.

## Main Story

The history of the SUB began before the current building existed. In 1936, construction began on UNM's original Student Union Building, designed by architect John Gaw Meem in the Pueblo Revival style. The building opened in 1937 and included a ballroom where students could attend dances and social gatherings. Today, that original building houses the Department of Anthropology and the Maxwell Museum of Anthropology. Following World War II, UNM experienced significant enrollment growth, creating a need for a larger student center. 



In 1956, UNM's Student Council voted to support a student fee that would help finance construction of a new Student Union Building. The current SUB was completed in 1959, with a dedication ceremony held on November 14, 1959. The new building offered students larger dining areas, meeting spaces, and a twelve-lane bowling alley. These additions made the SUB a central gathering place for students outside the classroom. 


One of the most significant events in the SUB's history occurred during the Vietnam War. On May 6, 1970, UNM students occupied the building to protest the war and the killing of four students at Kent State University on May 4. Actress and antiwar activist Jane Fonda had also visited UNM to support student organizing. At the time, UNM's president was Ferrel Heady. On May 8, law enforcement and National Guard soldiers moved to clear the occupied building. A violent confrontation followed, with approximately ten people injured by bayonets and 131 protesters arrested. The event became one of the most controversial moments in UNM's history and demonstrated how the SUB could serve as a center for political activism. 


During the 1970s, the building underwent several changes. Students had begun criticizing its conditions and atmosphere, including concerns about drug activity. In 1976, UNM began a major renovation that introduced new dining facilities. On November 21, 1977, the bowling alley was demolished after declining student interest. Pool tables and ping-pong areas eventually replaced the bowling facilities, reflecting changing recreational preferences. 


Another major transformation began in October 2000. UNM recognized that the SUB needed modernization to accommodate its growing student population. Walter Miller, a longtime university administrator, helped lead the renovation efforts. Construction continued into 2003, introducing additional restaurants, meeting rooms, student government spaces, and a central atrium. The renovated building provided students with more opportunities to gather and participate in campus life. 


The SUB continued to evolve in the following decades. In 2019, Cheryl Wallace became its director after serving as operations manager since 2009. Her work included improvements to technology, accessibility, and building maintenance. In August 2023, UNM celebrated the twentieth anniversary of the SUB's major renovation with three days of activities, including music, games, giveaways, and fundraising for student scholarships.

Today, the Student Union Building remains one of the busiest locations at UNM, welcoming more than 10,000 visitors daily, according to the university. From its beginnings as a student gathering space to its involvement in historic protests and campus development, the SUB represents more than just a building. It reflects the history, culture, and experiences of generations of UNM students.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
