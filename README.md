# ekstep-plugins

## Ideas for plugins

### Geography - Insert Map Plugin
**Problem**
- Almost all boards like MSERT have at-least district level syllabus for Geography for 1st to 4th grade. Since it is district level, it needs to be differnt for every district.
- As a teacher, how do I bring some fun to learn maps in easier way?
- How do I easily create interactive maps?

**Solution / Idea**
- Imagine a plugin that lets you choose state -> choose district -> and insert map of the district in the content editor.
- The maps being inserted will be based on some JS library that will do map rendering using SVG and offer interactions around map.
- This can enable teachers from all over India to create interactive maps for every district. 

**Idea inspired from**
Take a look at this interactive map - you will love it https://rawgit.com/neveldo/jQuery-Mapael/2.1.0/examples/advanced/multiple_legends_plotted_cities.html

**We can either take inspiration from or use these plugins**
- Mapael https://www.vincentbroute.fr/mapael/
 - Create custom vector map https://www.vincentbroute.fr/mapael/create-map.php
- JVectorMap http://jvectormap.com/

**Challenges**
- Getting SVG maps for all districts (Generating correct SVG paths to plot maps)
