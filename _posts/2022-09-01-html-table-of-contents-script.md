---
layout: post
title: HTML Table of Contents
subtitle: Use PowerShell to generate a starting shell for your KB articles or Website
cover-img: /assets/img/ThePower.jpg
thumbnail-img: /assets/img/ThePowerCropped.jpg
share-img: /assets/img/ThePower.jpg
tags: [powershell, html, kb, ]
---



<div><strong>Table of Contents to Rule All Table of Contents<a id="TOC" name="TOC"></a></strong></div>
<ul>
<li><a href="#Who,What,When,Where,2">Who, What, When, Where, Why</a></li>
<li><a href="#Disclaimers3">Disclaimers</a></li>
<li><a href="#Resources4">Resources</a></li>

</ul>
<br><br><br>

<h2>Quickly Generate a Table of Contents for HTML pages via PowerShell<a id="Who,What,When,Where,2" name="Who,What,When,Where,2"></a></h2></p>

- **Who:** Web Devs and Knowledge Base Article Authors
- **What:** 
  - A PowerShell Script for making HTML Table of Contents.
  - In goes a list of headings > Out goes HTML code for a Table of Content and coroponding linked/anchored Section Headings. 
  - [See this Walkthrough explaining how it works](/assets/posts/html_toc/script_kb_example)
- **Why:** 
  - It saves you time that would otherwise be spent on formatting, copying, pasting, anchoring, linking, multiple times over multiple headings. 
  - I've made a KB article template available to you so that you can share the info with others that may benefit.
  - I get to enjoy experimenting with PowerShell, learning HTML, and now learning GitHub and GitHub.oi. 
          
          
<br><br><br>
            
<p><a href="#TOC">Return to the Article Table of Contents above</a>
          
<p>&nbsp; </p><h2>Disclaimers<a id="Disclaimers3" name="Disclaimers3"></a></h2></p>
 
- Are you unfamiliar with PowerShell or scripting in general?
  - Ask someone that is to review the code with you; It's a learning opportunity for you, and your institution will know that they can trust you to ask before running random scripts found on the internet ( We IT People like that 😁 )  
  - The code is working well within my environment, both for TDX KB Articles and GitHub HTML/Markdown Pages, but I have not tested it elsewhere.
    - The Return to TOC links do not appear to work within GitHub Markdown Preview, but they will work on the live page.
- ConvertTo-TitleCase function:
  - Review the $SpecialCase and $LowerCase arrays for words that require specific case or that typically remain lowercase.
- I consider myself a novice-to-intermediate PowerShell user and would appreciate any feedback or bugs you encounter.



<br><br><br>
<p><a href="#TOC">Return to the Article Table of Contents above</a>
          
          
<p>&nbsp; </p><h2>Resources<a id="Resources4" name="Resources4"></a></h2></p>

- Scripts:
  - [Copy and Paste in to a PowerShell Console ](/assets/posts/html_toc/copy_and_paste)
  - [Create a Batch File](/assets/posts/html_toc/save_as_batch_file)
    - This is a PowerShell script that you will run to generate the batch file commands; The batch file requires an encoded command, so you get to encode it yourself as I believe that allows you to review the code and feel more secure. 
    - The script is essentially the encoding commands wrapped around the Copy and Paste script.
    - You would then save its output, which is copied to your computer clipboard, to a "Save as Batch File.txt" file that you can attach to the KB. Or, if you are only performing this to yourself, just save the output as a batch file.
  - [Save the functions to your PowerShell Profile](/assets/posts/html_toc/save_to_psprofile)
- Walk Through KB Article
  - [Example KB Detailing the Scripts and How to Run Them](/assets/posts/html_toc/script_kb_example)
  - [KB Template for you to save in your own KB](/assets/posts/html_toc/kb_html_template)
    - Same as the above Example KB, but raw HTML.
    - If you publish the KB article, be sure to edit it to your own institution's standards, remove any script methods you do not want to publish, and attach text files for any script methods you do want to publish.
    - I am no master of HTML, so your mileage may vary: This was generated using the TDX KB editor, which runs on Bootstrap 3.4.1. If you are having trouble making the controls work, see the [Bootstrap Basic HTML Template](https://getbootstrap.com/docs/3.4/getting-started/#template) that I used to make the code work on GitHub for the [Example KB Detailing the Scripts and How to Run Them](/assets/posts/html_toc/script_kb_example)


<br><br><br>
<p><a href="#TOC">Return to the Article Table of Contents above</a>
<p>&nbsp; </p>
















