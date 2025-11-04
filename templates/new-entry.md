---
headline: Enter Your Title Here
intro: Short description of the story.
issue: 
channel: 
featured: '"true" or "false"'
author(s): 
started-writing: <% tp.file.creation_date('YYYY-MM-DD') %> <% tp.file.creation_date('HH:mm') %>
ZID: <% tp.file.creation_date('YYYYMMDDHHmmss') %>
---
"<% await tp.file.rename(tp.file.creation_date('YYYYMMDDHHmmss')) %>  

```
## Introduction 
Briefly introduce the topic of the post. 

## Main Content 
Develop your main ideas here. 

### Subheading 
Details about a specific aspect of the main content. 

## Conclusion 
Summarize the main points. 

#### References (if any) 
- Reference 1 
- Reference 2 
```

> `⌘ + 0` to enter a footnote
> `⌘ + -` to return to location in file