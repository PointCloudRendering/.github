# Point Cloud Rendering in Unity

## Members:
- Isak Mäkimartti | IsakMakimartti
- Miro Hannikainen | MiroHann
- Noel Vähäjylkkä | NoelVahajylkka
- Märt Rahu | martrahu

## Introduction:
The idea of this project was to create a Unity application in which we would import some point cloud data and render it. We were given a bunch of point cloud data files from which we chose those that ran the best on Unity; some of the files were quite large and would require resources we didn't have. Another goal was to possibly export the model using glTF. We didn't end up implementing this, due to time constraints.

## Additional tools or Unity Plugins used:
- Pcx | https://github.com/keijiro/Pcx
  - Pcx is the tool we used to import and render the point cloud data in Unity. One small issue we noticed was that, as mentioned on the GitHub page, Pcx only accepts files in PLY format, while the files given to us were either LAS or E57 format. We used other tools to convert these to PLY in order to fix this issue.
- CloudCompare | https://www.cloudcompare.org/
  - Cloudcompare was used to both convert point-cloud data to another format; in our case PLY, and separate different parts of the data into their own objects (segmentation). Cloudcompare had many plugins which turned out to be useful in this.
- MeshLab | https://www.meshlab.net/
  - Meshlab, like CloudCompare, was also used for converting files to the correct format, in our case PLY.

## Tools we tested but didn't end up using:
- Point Cloud Unity Plugin | https://ccom.unh.edu/vislab/tools/point_cloud_plugin/
  - This Plugin was originally our other option for bringing point cloud data into Unity. After trying to get it to work with Unity and our data, we were not able to make it work as intended, which is why we decided to use the above-mentioned Pcx instead.
    
## Tidbits:
## Conclusion:
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
