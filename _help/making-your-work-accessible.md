---
ID: 1549
post_title: Zpřístupnění práce
author: admin
post_excerpt: ""
layout: help
permalink: >
  https://lab.urad.online/help/making-your-work-accessible/
published: true
post_date: 2018-01-15 22:52:07
help_tags:
  - Nepřiřazeno
help_category:
  - Best Practices
  - For Everyone
---
<h3>Making your Work Accessible</h3>
Web accessibility means that people with disabilities can use the Web. More specifically, it means that people with disabilities can perceive, understand, navigate, and interact with the Web, and that they can contribute to the Web.  Web accessibility also benefits others, including older people with changing abilities due to aging (from <a href="https://www.w3.org/WAI/intro/accessibility.php">Web Accessibility Initiative</a>).  Implementing accessible design standards will often improve the experience of everyone using your site.

The post below outlines what you should do to improve accessibility on your own Course, Project, Club, and Portfolio sites.  You can find out more information about accessibility, and improvements the OpenLab has been making, in our post on <a href="https://lab.urad.online/help/summary-of-accessibility-on-the-openlab/">Summary of Accessibility on the OpenLab</a>.  CUNY’s site on accessibility standards also has helpful information on <a href="http://www2.cuny.edu/accessibility/content/">making digital content accessible</a>.
<h4>Documents</h4>
It is important that documents, such as PDF and Microsoft Word files, that you upload to the OpenLab, are accessible.  These  include documents on a Site, or in the Files section of a Course, Project, or Club Profile.  CUNY’s guide to <a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/">creating accessible PDF and Microsoft Office documents</a> provides detailed instructions for how to do this, but a few key points are emphasized below.
<ol>
 	<li>PDF files are the most difficult file format to make accessible, and properly-structured HTML tends to be the most accessible.
<ul>
 	<li>Use or link to a PDF only when you cannot use HTML or Microsoft Office files.</li>
 	<li>Ensuring searchable text and tagging a PDF with hidden labels (tags) that describe the structure of the document are the minimum requirements for PDF document accessibility, in order to be correctly read by a screen reader.</li>
</ul>
</li>
 	<li>If it is necessary to use a PDF, please follow CUNY’s guidelines for:
<ul>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#Save">Saving a Word document as PDF</a></li>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#pdf_scanned">Using a scanned PDF document</a></li>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#pdf_forms">Using PDF forms</a></li>
</ul>
</li>
</ol>
<h4>Images</h4>
<ol>
 	<li>Include alternative text for all images.  Whenever you add a new image to a Post or Page, include short text in the <strong>Alt Text</strong> field in the Insert Media pop-up box (shown in the screenshot below).
<ul>
 	<li>Do not include the words “photo of” or “image of” because the screen reader will already signal that it is an image file. Keep the description short and informative.</li>
 	<li>For images that represent concepts and information, such as photos and illustrations, include alt text that briefly conveys the essential information presented by the image. For more on alt text for different types of images, see <a href="http://www2.cuny.edu/accessibility/content/websites/#images">CUNY’s guide to image accessibility</a>.</li>
 	<li>Rationale: Alternative text, or “alt text” for short, refers to a short description for images that will be read aloud by screen readers, and is required for accessibility.</li>
</ul>
</li>
 	<li>Remove any text in the <strong>Title</strong> field.
<ul>
 	<li>Rationale: WordPress automatically creates an image title that is the same as the image file name. Usually this results in a meaningless title, such as “IMG_5981.” Titles are optional and some browsers  or devices may not support them, so it is better to include only alt text and avoid the screen reader either missing the title or reading the same information twice.</li>
</ul>
</li>
 	<li>Prevent images from opening in their own tab after being clicked, by selecting <strong>none</strong> in the <strong>Link To </strong>dropdown menu.
<ul>
 	<li>Rationale: Images will not have any alt text or other accessibility controls when they open in the new window.</li>
</ul>
</li>
</ol>
&nbsp;

<img class="alignnone size-full wp-image-45616" src="https://openlab.citytech.cuny.edu/wp-content/uploads/2017/10/Alt_Text_1.png" alt="Screenshot showing title, alt text, and link to settings." />
<h4>Video and Animation</h4>
<ol>
 	<li>Do not autoplay video and animated gifs with flashing visual content.
<ul>
 	<li>Rationale: People using screen readers may have difficulty hearing the reader’s output if other audio is playing at the same time.</li>
 	<li>Rationale: Quickly blinking or flashing images  can trigger seizures in people with certain types of seizure disorders.</li>
 	<li>Rationale: Animations can be disorienting to many people, especially those with certain types of cognitive disorders.</li>
</ul>
</li>
 	<li>Include captions for video.  Captions provide text versions of the words spoken in a video.  It is essential for people who cannot hear the audio, and can be helpful for all users of your site, including people not fluent in the language used in the video/audio, or people who are working in a quiet space.
<ul>
 	<li><a href="https://www.youtube.com/">YouTube</a> and <a href="https://vimeo.com/">Vimeo</a> are the suggested video platforms for the OpenLab, and both allow you to add captions.  YouTube provides instructions for <a href="https://support.google.com/youtube/answer/2734796?hl=en">adding your own subtitles and closed captions</a> and Vimeo also has help on <a href="https://help.vimeo.com/hc/en-us/articles/224968828-Captions-and-subtitles">captions and subtitles</a>.</li>
 	<li>You can find information on additional tools in CUNY’s guide to <a href="http://www2.cuny.edu/accessibility/content/videos/#video_captioning_tools">video captioning tools</a>.</li>
</ul>
</li>
</ol>
<h4>Site Organization<strong>
</strong></h4>
<h5>Links</h5>
<ol>
 	<li>Use informative and specific wording for the text that the user will click on, to describe where the link will take them.  For example, if you are linking to an accessibility article, use descriptive text such as “Article on Accessibility.”
<ul>
 	<li>Avoid vague phrases like “Click here.”</li>
 	<li>Avoid using the word “link” because screen readers will already alert the user that the text is a link.</li>
 	<li>Avoid using URLs in the link text, because they are cumbersome when read aloud.  E.g. Use “W3C Tutorial on Functional Images” rather than “https://www.w3.org/WAI/tutorials/images/functional”.</li>
 	<li>Rationale: If someone is using a screen reader, which will read the links out loud, the user will be able to know where a link will take them before clicking.</li>
</ul>
</li>
</ol>
<h5>Information Design</h5>
<ol>
 	<li>Organize content in a Post or Page using Headings to structure the information you present to create a clear visual hierarchy.
<ul>
 	<li>Rationale: using a logical structure will benefit everyone who visits your site. The information is easier to scan for sighted users. People using screen readers can use headings to navigate among the different sections.</li>
</ul>
</li>
 	<li>Use the Heading styles in the Post or Page editor dropdown, rather than bold or italics to indicate a heading (see screenshot below).
<ul>
 	<li>The Heading 1 style should only be used once per page. Don’t use Heading 2 styles too often; they should be reserved just for sub-section titles.</li>
</ul>
</li>
 	<li>Use common, recognizable fonts that provide a strong contrast with the background color of the page.  This will not be an issue for most OpenLab members if you stick to the default fonts and colors for your theme.  However, if you’re using one of our font plugins, such as Easy Google Fonts, or changing the text or background colors, you can find more information about contrast in <a href="https://webaim.org/articles/visual/lowvision#highcontrast">WebAim: Visual Disabilities: High Contrast</a>.
<ul>
 	<li>Avoid using colors that create a low contrast; for example, light color fonts on a white background.</li>
 	<li>Avoid script fonts, which can be difficult to read for everyone; and especially people with visual impairments.</li>
 	<li>Try viewing your site while zoomed in, which is a common practice to increase readability.  You can do this by pressing the ctrl and + keys together, or command + on a Mac.</li>
</ul>
</li>
</ol>
&nbsp;

<img class="alignnone size-full wp-image-45617" src="https://openlab.citytech.cuny.edu/wp-content/uploads/2017/10/Headings_2.png" alt="Screenshot showing heading styles" />
<h4>Additional Resources</h4>
Below are some more helpful resources on how to make your site more accessible:
<ul>
 	<li><a href="http://blogaccessibility.com/a-super-simple-way-to-make-images-accessible-alt-text-versus-title-explained/">A Super Simple Way to Make Images Accessible: Alt Text versus Title Explained</a></li>
 	<li><a href="https://www.w3.org/WAI/tutorials/images/functional/">W3C Tutorial on Functional Images </a></li>
 	<li><a href="http://www.interactiveaccessibility.com/blog/making-images-visible-blind-users#.WAfrZNwqH8U">Making Images Visible to Blind Users</a></li>
 	<li>CUNY Guide to accessible uses of <a href="http://cats.cuny.edu/reasonableaccommodations/TechnologyintheClassroom.html">Technology in the Classroom and for Online Courses</a></li>
 	<li><a href="https://er.educause.edu/articles/2017/1/ada-compliance-for-online-course-design">ADA Compliance for Online Course Design</a></li>
 	<li><a href="http://wave.webaim.org/">Web Accessibility Evaluation Tool</a> (WAVE) – can be used to find any accessibility errors on your Site</li>
 	<li><a href="https://webaim.org/resources/contrastchecker/">WebAIM Color Contrast Checker</a> – can be used to verify color contrasts match accessibility standards</li>
</ul>
