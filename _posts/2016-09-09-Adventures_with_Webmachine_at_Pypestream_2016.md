---
layout: post
title: Web frameworks - exploration at Pypestream Inc.
date: 2016-09-09
---

### On-site at a client, Pypestream, last year we explored various Web frameworks for REST, Webmachine based on Erlang's Cowboy httpd, was one of the final candidates chosen to power their Public API 

... here is the html of the Keynote

If you'd like to see the [presentation click here](http://agentidea.com/presentations/GS/erlang/assets/player/KeynoteDHTMLPlayer.html#0)

Basically Webmachine is the "Existential" framework!
``` 
-module( petite_shorten_resource). 
-export([ init/ 1, allowed_methods/ 2, process_post/ 2, content_types_provided/ 2, to_text/ 2]). 
-include_lib(" webmachine/ include/ webmachine.hrl").
```

###### Moffitt, Jack; Daoud, Frederic (2013-12-31). Seven Web Frameworks in Seven Weeks: Adventures in Better Web Apps (Pragmatic Programmers) (p. 173). Pragmatic Bookshelf. Kindle Edition. 

This book was a really a good resource which was used in preparation of this talk.

Other framewors we considered:  HapiJS, Python Flask and Yaws
We also considered using our very own [AgentIdea Web Framework](https://github.com/agentidea/AgentIdea-WebFramework)
