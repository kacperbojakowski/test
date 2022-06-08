---
layout: kb-layout
title: About
nav_order: 11
search_exclude: true
---

## About

[Author⎹](#author) [Project⎹](#project) [References](#references)

---

This is a meta-section with information about the guide. Here you will learn about the project: why I did it, how I did it, and what tools I used. You will also find the list of references further down this page.  

Speaking of references, feel free to use, share, and quote this guide in parts or as a whole. I hope someone finds it useful for the purpose of learning, teaching, or preaching about the value of technical writing and documentation – now that would be cool! If you ever cite my scribbles, I'd appreciate a mention. Thanks!  

### Author

Hi, my name is [Kacper](https://github.com/kacperbojakowski) and I am the author of this guide. As of 2022, I am also on my way to retraining as a technical writer. I wrote this guide as my student project for the [postgraduate course](../06-education/5-degrees/index.md/#technical-communication-at-university) I am currently taking at Vistula University in Warsaw.  

You can contact me at <kacperbojakowski@gmail.com>.  

### Project

**Original topic:** "Od zera do Tech Writera – jak się przebranżowić?"  
**Persona:** Translator retraining as a technical writer     
**Tools:** [Markdown](https://daringfireball.net/projects/markdown/), [Jekyll](https://jekyllrb.com/), [Just the Docs](https://github.com/just-the-docs/just-the-docs/)  
**Publishing:** [GitHub Pages](https://pages.github.com/)  
**Software:** [Visual Studio Code](https://code.visualstudio.com/), [GitHub Desktop](https://desktop.github.com/), [GIMP](https://www.gimp.org/), [Snagit](https://www.techsmith.com/screen-capture.html), [Diagrams.net](https://app.diagrams.net/), [Microsoft PowerPoint](https://www.microsoft.com/en-us/microsoft-365/powerpoint)  
**Supervisor:** Dariusz Drezno  
**Peer reviewer:** Michał Olender  

I selected the topic from a list provided by the class instructors. My choice was self-referential, if not a bit ironic, but with a reason. I wanted to make a reminder for myself and others in training to stay motivated in pursuit of success in the new field. I believe that with a good manual, no matter what the task is, failure is not an option. I should hope, then, that this one here is a good one.  

I decided to go for Markdown with Jekyll, and not Oxygen XML with DITA or MadCap Flare (the two other options available for the projects). With due respect to DITA and HATs, I much prefer the Docs as Code approach. I like the simplicity of raw text, markup, and code without extra layers of abstraction. Take this as an excuse all you want! ☺  

I used [Just the Docs](https://github.com/just-the-docs/just-the-docs/) theme, which I modified to my needs. The changes include:

* Page layout, spacing, colors, typography, etc.
* Modified breadcrumbs to match the structure (mini TOC → Topics).
* Modified YAML file, footer, page 404, and other defaults.
* Manually-added "Next section/ topic" buttons (which I'd love to automate when time permits).
* Manually-added glossary with letter-buttons.
* Modified search (the placeholder disappearing on focus, directories excluded from results, etc.).
* New CSS classes and styling for various elements.  

Much of this happens in `just-the-docs/_layouts` and `_sass` in my [forked repository](https://github.com/kacperbojakowski/just-the-docs). I tried to maintain the order and structure of the theme for future reuse (e.g., global reference values and attributes), but wasn't too strict at that. After all, it's just for my purposes.  

Other technicalities concerned graphic design, e.g., editing images, taking and preparing screenshots, making diagrams, etc.  

> 🖊️ **NOTE:** In places, the content is slightly "polluted" with HTML. This was done on purpose, to overcome Markdown's limitations. Still, the tags I used are purely presentational and you can delete them without losing functionality; the HTML-augmented elements will fall back to simple Markdown formatting. To find the "polluted" areas, search for `<!-- HTML CONTAMINATION-->` in the MD files. Be careful with regex, though – I used HTML in some code-block examples.  

As for the language, there was no specific style guide I followed other than aiming for General American instead of my favored British English (I remained faithful to [n-dashes over m-dashes](https://www.ox.ac.uk/sites/files/oxford/media_wysiwyg/University%20of%20Oxford%20Style%20Guide.pdf), though) I stuck to [Chicago](https://www.chicagomanualofstyle.org/home.html) for the title (lowercase all prepositions), but not for section headers; those I lowercased intentionally, just for the looks (I like it better; [GitHub](https://docs.github.com/en) does it, among others). The style is my regular informal/semi-formal mode: optimistic and humorous, but restrained for instructions; loosely inspired by [Atlassian](https://atlassian.design/content/writing-style).  

The reason why I didn't use Plain English is *plain* – the persona. Translators know the language well and reading longer texts is their daily bread. Unrestrained, I enjoyed this project all the more!  

Thanks to Michał Olender for his peer review and tips on styling, structure, admonitions, etc. What I didn't manage to improve on (time constraints), I will surely keep in mind for the future.  

### References

**PRINT SOURCES**

ITCQF. 2020. *Technical Communication Professional: Foundation Level*. Syllabus (ver. 2.0). [ITCQF](https://itcqf.org/wp-content/uploads/2020/06/ITCQF_Syllabus_v2_0Jun2020.pdf).   
ITCQF. 2020. *The Value of Technical Writing*. [ITCQF](https://itcqf.org/wp-content/uploads/2021/02/ITCQF-The-Value-of-Techwriting.pdf).  
Lindsell-Roberts, S. 2001. *Technical Writing for Dummies*. Hoboken: Wiley & Sons.  

**UNIVERSITY MATERIALS**

Barrio Fierro, D. 2021-2022. *Techniki i narzędzia stosowane w dokumentacji technicznej*. Presentation slides. Warsaw: Vistula University.  
Barrio Fierro, D. 2021-2022. *Praca z tekstem technicznym*. Presentation slides. Warsaw: Vistula University.  
Barrio Fierro, D. 2021-2022. *Podstawowe technologie komunikacji technicznej*. Presentation slides. Warsaw: Vistula University.  
Bartnicka, M. 2021-2022. *Podstawowe technologie komunikacji technicznej*. Presentation slides. Warsaw: Vistula University.  
Drezno, D. 2021. *Komunikacja Techniczna: podstawy*. Presentation slides. Warsaw: Vistula University.  
Prus, T. 2021. *Podstawowe zagadnienia komunikacji technicznej*. Presentation slides. Warsaw: Vistula University.  
Prus, T. 2022. *Praca z tekstem technicznym*. Presentation slides. Warsaw: Vistula University.  
Górski, M. 2022. *Technical Writing at Google*. Lecture. Warsaw: Vistula University (23 April 2022).  

**COURSES**

Brandt, A. 2021. *Agile i Scrum od podstaw*. MOOC course. [Udemy](https://www.udemy.com/course/agile-i-scrum-od-podstaw/).    
Prus, T. 2021. *ITCQF Certified Technical Communication Professional: Foundation Level*. [ITtraining](http://edu.ittraining.pl/szkolenie/ITCQF_Poziom_Podstawowy) (2-3 August 2021).  
Róg, G. 2018. *HTML i CSS - poznaj podstawy i zacznij programować!*. MOOC course. [Udemy](https://www.udemy.com/course/kurs-html-i-css-od-podstaw/).  
Szuszkiewicz, A. 2021. *GIT od podstaw dla każdego*. MOOC course. [Udemy](https://www.udemy.com/course/git-od-podstaw-dla-kazdego/).  

**GRAPHICS**

Home page header: [ClearVoice](https://www.clearvoice.com/blog/niche-freelancers-tech-writers/) (modified)   
Section headers: [Unsplash](https://unsplash.com/) (modified)  
Movie photo: *Forrest Gump* (1994), dir. R. Zemeckis  
ITCQF banner: [ITCQF](https://itcqf.org/wp-content/uploads/2021/02/ITCQF-The-Value-of-Techwriting.pdf)
Engineer image: [Vecteezy](https://www.vecteezy.com/) (by Iyi Kon)  
Screenshots: own, unless stated otherwise  

**ONLINE SOURCES**

<http://public2.brighttalk.com/resource/core/217857/the-state-of-technical-communication_474463.pdf>  
<http://techwriter.pl/cv-najwazniejszy-dokument-tech-writera/>  
<http://techwriter.pl/jak-dostac-pierwsza-prace-jako-technical-writer/>  
<http://techwriter.pl/kilka-pytan-do-czesc-15/>  
<https://clickhelp.com/clickhelp-technical-writing-blog/importance-of-accessibility-in-technical-writing/>  
<https://clickhelp.com/online-software-documentation-tool/single-sourcing-and-content-reuse/>  
<https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics>  
<https://www.geeksforgeeks.org/centralized-vs-distributed-version-control-which-one-should-we-choose/>
<https://heretto.com/what-is-a-component-content-management-system/>
<https://idratherbewriting.com/2016/05/05/visualcommunication_noun_project/>  
<https://idratherbewriting.com/blog/evolving-roles-of-technical-wrters/>
<https://idratherbewriting.com/trends/trends-to-follow-or-forget-every-page-is-page-one.html>  
<https://idratherbewriting.com/trends/trends-to-follow-or-forget-hats.html>  
<https://idratherbewriting.com/trends/trends-to-follow-or-forget-wordpress.html>  
<https://medium.com/level-up-web/visual-communication-in-technical-writing-821565caa8f4>  
<https://opensource.com/article/21/11/technical-writing-open-source>  
<https://techwhirl.com/what-is-dita/>  
<https://uvacollab.screenstepslive.com/m/gettingstarted/l/451374-what-does-it-mean-to-make-content-accessible>  
<https://www.careereducation.columbia.edu/resources/how-write-resume-profile-or-summary-statement>  
<https://www.editha.it/en/accessibility-in-technical-writing/>
<https://www.linkedin.com/pulse/5-principles-single-sourcing-technical-documentation-anders-svensson>  
<https://www.markdownguide.org/getting-started/>  
<https://www.techsmith.com/blog/how-to-make-user-manual/>  
<https://www.usability.gov/what-and-why/information-architecture.html>
<https://www.w3schools.com/xml/xml_whatis.asp>   
<https://xd.adobe.com/ideas/process/information-architecture/information-ux-architect/>  
