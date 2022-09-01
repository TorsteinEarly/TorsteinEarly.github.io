---
layout: post
title: HTML Table of Contents
subtitle: Use PowerShell to generate a starting shell for your KB articles or Website
cover-img: /assets/html_toc/HTMLTOC.png
thumbnail-img: /assets/img/thumb.png
share-img: /assets/html_toc/HTMLTOC.png
tags: [powershell, html, kb, ]
---

<br>

- **Who Would This Be Of Interest To:** Web Devs and Knowledge Base Article Authors
- **What Is This:** 
  - A PowerShell Script to convert a list of headings into HTML code for a Table of Contents with linked headings. 
  - [See this Walkthrough explaining how it works](assets/posts/html_toc/script_kb_example)
- **Why Should We Care:** 
  - It saves you time that would otherwise be spent on formatting, copying, pasting, anchoring, linking, multiple times over multiple headings. 
  - I've made a KB article available to you so that you can share the info with others that may benifit.
  - I get to enjoy eperimenting with PowerShell, learning HTML, and now learning GitHub and GitHub.oi. 

<br>



***Disclaimers:*** 
- You are now entering *PowerShell Land.* 
  - If you are unfamiliar with PowerShell or scripting in general, plaese have someone who is reivew this before using at your institution. 
  - The code is working well within my environment, both for TDX KB Articles and for GitHub HTML Pages, but I have not tested it elseware: I consider myself a novice-to-intermidiate with PowerShell, and would appreciate any feedback or bugs you encounter.
- ConvertTo-TitleCase function:
  - Review the $SpecialCase and $LowerCase arrays for words that require special case as well as words that typically remain lowercase.

<br>

**Resources:**
- Scripts:
  - [Copy and Paste in to a PowerShell Console ](assets/posts/html_toc/copy_and_paste)
  - [Create a Batch File](assets/posts/html_toc/save_as_batch_file)
    - This is a PowerShell script that you will run to generate the batch file commands; The batch file requires an encoded command, so you get to encode it yourself as I belive that allows you to review the code and feel more secure. 
    - The script is essentially the encoding commands wrapped arround the Copy and Paste script.
    - You would then save it's output, which is coppied to your computer clipboard, to a "Save as Batch File.txt" file that you can attach to the KB. Or, if you are only performing this to yourself, just save the output as a batch file.
  - [Save the functions to your PowerShell Profile](assets/posts/html_toc/save_to_psprofile)
- Walk Through KB Article
  - [Example KB Detailing the Scripts and How to Run Them](assets/posts/html_toc/script_kb_example)
  - [KB Template for you to save in your own KB](assets/posts/html_toc/kb_html_template)
    - Same as the above Example KB, but raw HTML.
    - If you publish the KB article, be sure to edit it to your own institution standards, remove any script methods you do not want to publish, and attach text files for any script methods you do want to publish.
    - I am no master of HTML, so your milage may verry: This was generated using the TDX KB editor, which runs on Bootstrap 3.4.1. If you are having trouble making the controlls work, see the [Bootstrap Basic HTML Template](https://getbootstrap.com/docs/3.4/getting-started/#template) that I used to make the code work on GitHub for the [Example KB Detailing the Scripts and How to Run Them](assets/posts/html_toc/script_kb_example)








**The Story**

I like to share knowledge, which has resulted in my writing extensive kB articles for my institution. We use TeamDynamix as our Knowledge Base, which has a markdown editor with HTML source view. As my 





