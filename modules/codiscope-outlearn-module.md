<!--
{
"name": "codiscope-outlearn-module",
"version" : "0.1",
"title" : "A Codiscope Module",
"description" : "Testing 123",
"homepage" : "https://github.com/outlearn-content/outlearn-modules",
"freshnessDate" : 2015-05-18,
"license" : "CC BY 4.0"
}
-->

<!-- @section, "title": "A1-Injection" -->

# Bugs vs Flaws

Software is a complex system of components, and inevitably contains defects. Some of these defects constitute security vulnerabilities that, in turn, introduce risk.

Security defects are divided into two different types: bugs and flaws.

Bugs are implementation errors found in the code. Flaws are design errors relating to the software architecture.

![OWASP screenshot](https://codiscope.com/wp-content/uploads/2015/01/owasp-4.jpg)



GitHub-flavored markdown will work just fine, and you can preview your files in your favorite text editor or Markdown preview tool before uploading them to Outlearn for final proof-reading.

If you want to enrich your content with more features, this sample module has a few examples, including the Unfurled Link above, and the interactive features described in the next section.

> Block quotes get special styling on Outlearn. They turn into highlight boxes.


<!-- @section -->

# Images and videos

You can include images using Markdown syntax.

![sea](https://raw.githubusercontent.com/outlearn-content/outlearn-modules/master/assets/sea.jpg)


You can embed hosted videos in your paths using Outlearn @asset syntax. Here is a Vimeo video:

<!-- @asset, "contentType": "outlearn/video", "provider": "vimeo", "url": "https://player.vimeo.com/video/67325705" -->

And here is another one form YouTube:

<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/embed/CmjeCchGRQo" -->

<!-- @section -->

# Let's make our module Fancy

If you want to get your audience to practice what you preach, give them a task.

```python
# Transpose a matrix:
>>> l = [[1, 2, 3], [4, 5, 6]]
>>> zip(*l)
[(1, 4), (2, 5), (3, 6)]

# Divide a list into groups of n:
>>> l = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5, 8]
>>> zip(*[iter(l)] * 3)
[(3, 1, 4), (1, 5, 9), (2, 6, 5), (3, 5, 8)]
```

<!-- @task, "text" : "Go and run these clever code examples on your own machine, lazy bones!"-->

And if they are making something worth sharing, why not let them share it with you?

<!-- @task, "hasDeliverable" : true, "text" : "Write and submit a haiku about your favorite compiler."-->

If you need more details on how to author, please visit the [Outlearn Publishing Guide](https://pilot.outlearn.com/learn/outlearn/outlearn-publishing), where you'll find more examples along with the full specification for the format used by this sample module.
