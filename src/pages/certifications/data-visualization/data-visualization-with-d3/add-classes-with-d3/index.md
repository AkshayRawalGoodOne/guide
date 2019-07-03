---
title: Add Classes with D3
---
## Add Classes with D3


This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/data-visualization/data-visualization-with-d3/add-classes-with-d3/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

```<script>
    const dataset = [12, 31, 22, 17, 25, 18, 29, 14, 9];
    
    d3.select("body").selectAll("div")
      .data(dataset)
      .enter()
      .append("div")
      // Add your code below this line
      .attr("class", "bar");
      
      
      // Add your code above this line
  </script>```
  
  Reference :- 
  https://benclinkinbeard.com/d3tips/attrclass-vs-classed/
