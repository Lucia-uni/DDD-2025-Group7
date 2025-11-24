# DDD-2025-Group7
Edoardo Carlani, Lucia Ciapessoni, Sara Deriu
## Ufo shapes
### Data Collection
+ Where did you get your data from? [https://nuforc.org/databank/]
+ What’s your data about? [describe]
+ Who is/are the sources/creators of your data?
### Data Organization
+ Have you combined data from different sources? How did you merge them?
+ What columns are more relevant for your project?
+ Have you used any AI-based tool to understand or manipulate your data? if yes, what and how?

# Intraspace

### Visualisation
![ScreenRecording](/DOC/screen.mp4)

### Abstract 
This research explores the question: Does AI believe in UFOs? Using photos from the National UFO Reporting Center (NUFORC) database—where individual users upload images of what they identify as unidentified flying objects, categorized by shape—we analyzed them with object-recognition software. However, since these images are often decontextualized from their original source, the results we obtained differed from the original intended meaning. So our question became: depending on the UFO’s shape, what does the AI actually see?

### Protocol Diagram
mermaid
flowchart TB
    n1["Topic: AI object detector and ufo"] --> n2["Research site"]
    n2 --> n3["Collect data"]
    n3 --> n4["NUFORC archive"]
    n4 --> n5["Organize &amp; archive"]
    n5 --> n6["Analyze images with AI"] & n7["Divide in group by form"]
    n7 --> n6 & n8["Use photoshop AI"]
    n8 --> n9["Interpretation"]
    n6 --> n9
    n9 --> n10["Insights"]
    n1@{ shape: rect}
    n3@{ shape: diam}
    n5@{ shape: diam}
    n9@{ shape: diam}


### What topic does the project address?
The project explores the tool of AI, in this case object recognition. Images of varying quality, taken in different situations and contexts, were often used. This allows us to observe how the machine reacts to these shapes, which are often strange and unusual.

### What data have you considered?
We used the existing database of the National UFO Reporting Center (NUFORC), a non-profit organization that specializes in UFO sightings. On their website, users can submit a report of a possible UFO sighting, providing various details such as the UFO’s shape, date, time, duration of the sighting, and more. The website also allows users not only to upload possible photos or videos of the event, but also to view the images submitted as evidence.
We had to make a careful selection of the images, excluding any photos of drawings, three-dimensional replicas, and similar material. We used only the photos of the alleged UFOs.

<img alt="Screenshot Dataset" src="/DOC/screen.png" />

#### Link to the dataset
[\[Dataset\]](https://docs.google.com/spreadsheets/d/1mFJQY0Uly0rblv_2mHryVKnJKPaWtteHuqaW7feRPbI/edit?usp=sharing)

### What does the visualisation show?
-More sightings occur at night, or at least more UFOs are photographed at night.

– At night, the artificial intelligence has more difficulty analyzing the images. There were many cases in which the object (clearly visible to the naked eye) was not detected; the only way to get it analyzed was by cropping the image.

– Most of the AI’s interpretations are “kites.” There were no cases in which the AI identified the photos of the alleged sightings as UFOs (even when the AI could have recognized them). We can say that AI does not believe in UFOs, or rather, it does not recognize as a UFO something that a human being might interpret as such.
