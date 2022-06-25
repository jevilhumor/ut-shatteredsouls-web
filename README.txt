Hey, heres a few tips on how to manage this website!

---

(NOTE: please have basic HTML/CSS knowledge before editing
 pre-existing documents or files! Thank you!)

PRE-EQUISITES:
 - Notepad++ or Visual Studio to edit documents
 - Basic HTML/CSS knowledge
 - A GitHub account
 - GitHub Desktop application to commit builds

---

CREATING A NEW PAGE:
  To create a new page, you can simply duplicate "template.html"
  and rename it. You can cross-reference other pages for further
  markdown tips.

BOLD FONTS:
  To make a font bold, I actually used two different fonts:
   - 8BitOperator JVE (the BOLD font)
   - 8BitOperator Reg (the NORMAL font)
  If you wanna take the easier route, you can simply type "<b>" to
  begin bold lettering, and use "</b> to cancel the bold lettering.
  However, the way I do it uses a different font. So, if you want to
  keep the bolding similar to how it is on UNDERTALE and DELTARUNEs
  sites, copy and paste the following:
   - <font style="font-size:150%;font-family:'8bitoperator JVE';">
  This allows you to enable 8BitOperator JVE boldness, and can be
  closed after typing by using </font>

CREATING NEW DEVLOGS:
  After creating a new page by duplicating "template.html", you need
  a way to access it. Here's a template for the devlog thumbnail seen
  in "devlog.html":
  
	    <a href="DEVLOG LOCATION"><button class="dev-thumb">
			<image src="asset/images/DEVLOG THUMBNAIL IMAGE" class="dev-img"></img>
			<font style="color:gray;">DATE -</font> TITLE<br>
			<div class = "dev-thumb-subtxt">
				DEVLOG SUBTEXT/DESCRIPTION
			</div>
		</button></a>
  
  Just fill in the pretty obvious and self-explanitory "blanks", and
  you're good!

LINKS:
  Links are easy-peasy. Just put:
   - <a href="LINK">
  before writing something, putting an image, etc. Just be sure to
  close the link using </a> after putting whatever you wanted as a link
  there. The "LINK" can be either:
   - A local file in the ROOT directory
   - A file from the internet (webpage, image, etc.)
  That goes for all uses of "href" and "src" that you've seen so far.
  
---

Aaaaand I think that's about it! If you need more questions, feel free
to ask me on Discord or whatever. 