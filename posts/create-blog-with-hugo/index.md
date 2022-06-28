# Hola Mundo | Creating Blog with Hugo and GitHub Pages 👷🏻‍♀️


</head>

<body lang=EN-US link="#0563C1" vlink="#954F72" style='tab-interval:.5in;
word-wrap:break-word'>

<div class=WordSection1>

<table class=MsoTableGrid border=0 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-yfti-tbllook:1184;mso-padding-alt:
 0in 5.4pt 0in 5.4pt;mso-border-insideh:none;mso-border-insidev:none'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><i><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN";color:black;mso-color-alt:windowtext;
  background:#D9D9D9;mso-shading:white;mso-pattern:gray-15 auto'>This post
  shares the steps that I performed to build personal blog on GitHub Pages using
  Hugo theme.</span></i><i><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'><o:p></o:p></span></i></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:.75in;mso-add-space:auto;
text-indent:-.5in;line-height:115%;mso-list:l0 level1 lfo3'><![if !supportLists]><b><span
style='font-family:"Arial",sans-serif;mso-fareast-font-family:Arial;color:#2E75B6;
mso-themecolor:accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;
mso-style-textfill-fill-themecolor:accent5;mso-style-textfill-fill-alpha:100.0%;
mso-style-textfill-fill-colortransforms:lumm=75000'><span style='mso-list:Ignore'>I.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span></b><![endif]><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E75B6;mso-themecolor:
accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;mso-style-textfill-fill-themecolor:
accent5;mso-style-textfill-fill-alpha:100.0%;mso-style-textfill-fill-colortransforms:
lumm=75000'>Create Hugo Site<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>cd ~/Documents<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span class=SpellE><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>hugo</span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  new site <span class=SpellE>lluvia</span>-blog <o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:.75in;mso-add-space:auto;
text-indent:-.5in;line-height:115%;mso-list:l0 level1 lfo3'><![if !supportLists]><b><span
style='font-family:"Arial",sans-serif;mso-fareast-font-family:Arial;color:#2E75B6;
mso-themecolor:accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;
mso-style-textfill-fill-themecolor:accent5;mso-style-textfill-fill-alpha:100.0%;
mso-style-textfill-fill-colortransforms:lumm=75000'><span style='mso-list:Ignore'>II.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span></b><![endif]><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E75B6;mso-themecolor:
accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;mso-style-textfill-fill-themecolor:
accent5;mso-style-textfill-fill-alpha:100.0%;mso-style-textfill-fill-colortransforms:
lumm=75000'>Choose Hugo Theme &amp; Clone + Edit Configuration File<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>cd themes<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git <span class=SpellE>init</span><o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git submodule add <span
  class=SpellE><span class=GramE>git@github.com:HEIGE-PCloud</span></span><span
  class=GramE>/<span class=SpellE>DoIt.git</span></span> <span class=SpellE>DoIt</span><o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='margin-left:.75in;mso-add-space:auto;
text-indent:-.5in;line-height:115%;mso-list:l0 level1 lfo3'><![if !supportLists]><b><span
style='font-family:"Arial",sans-serif;mso-fareast-font-family:Arial;color:#2E75B6;
mso-themecolor:accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;
mso-style-textfill-fill-themecolor:accent5;mso-style-textfill-fill-alpha:100.0%;
mso-style-textfill-fill-colortransforms:lumm=75000'><span style='mso-list:Ignore'>III.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span></b><![endif]><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E75B6;mso-themecolor:
accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;mso-style-textfill-fill-themecolor:
accent5;mso-style-textfill-fill-alpha:100.0%;mso-style-textfill-fill-colortransforms:
lumm=75000'>Create New Post<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpLast style='margin-left:.75in;mso-add-space:auto;
line-height:115%'><span style='font-family:"Arial",sans-serif;mso-fareast-font-family:
"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>cd ~/Documents<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>cd <span class=SpellE>lluvia</span>-blog<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span class=SpellE><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>hugo</span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  new posts/my-first-post.md<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:.75in;mso-add-space:auto;
text-indent:-.5in;line-height:115%;mso-list:l0 level1 lfo3'><![if !supportLists]><b><span
style='font-family:"Arial",sans-serif;mso-fareast-font-family:Arial;color:#2E75B6;
mso-themecolor:accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;
mso-style-textfill-fill-themecolor:accent5;mso-style-textfill-fill-alpha:100.0%;
mso-style-textfill-fill-colortransforms:lumm=75000'><span style='mso-list:Ignore'>IV.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span></b><![endif]><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E75B6;mso-themecolor:
accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;mso-style-textfill-fill-themecolor:
accent5;mso-style-textfill-fill-alpha:100.0%;mso-style-textfill-fill-colortransforms:
lumm=75000'>Create GitHub Repository + Setting<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>new repository </span><span
  style='font-family:Wingdings;mso-ascii-font-family:Arial;mso-fareast-font-family:
  "Source Han Serif CN";mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;
  mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  vaya-lluvia/vaya-lluvia.github.io </span><span style='font-family:Wingdings;
  mso-ascii-font-family:Arial;mso-fareast-font-family:"Source Han Serif CN";
  mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;mso-char-type:symbol;
  mso-symbol-font-family:Wingdings'><span style='mso-char-type:symbol;
  mso-symbol-font-family:Wingdings'></span></span><span style='font-family:
  "Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'> public </span><span
  style='font-family:Wingdings;mso-ascii-font-family:Arial;mso-fareast-font-family:
  "Source Han Serif CN";mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;
  mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  add a README file <o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>repository settings </span><span
  style='font-family:Wingdings;mso-ascii-font-family:Arial;mso-fareast-font-family:
  "Source Han Serif CN";mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;
  mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  pages </span><span style='font-family:Wingdings;mso-ascii-font-family:Arial;
  mso-fareast-font-family:"Source Han Serif CN";mso-hansi-font-family:Arial;
  mso-bidi-font-family:Arial;mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  branch: main; /(root); change theme </span><span style='font-family:Wingdings;
  mso-ascii-font-family:Arial;mso-fareast-font-family:"Source Han Serif CN";
  mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;mso-char-type:symbol;
  mso-symbol-font-family:Wingdings'><span style='mso-char-type:symbol;
  mso-symbol-font-family:Wingdings'></span></span><span style='font-family:
  "Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'> download _<span
  class=SpellE>config.yml</span> &amp; README.md<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:.75in;mso-add-space:auto;
text-indent:-.5in;line-height:115%;mso-list:l0 level1 lfo3'><![if !supportLists]><b><span
style='font-family:"Arial",sans-serif;mso-fareast-font-family:Arial;color:#2E75B6;
mso-themecolor:accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;
mso-style-textfill-fill-themecolor:accent5;mso-style-textfill-fill-alpha:100.0%;
mso-style-textfill-fill-colortransforms:lumm=75000'><span style='mso-list:Ignore'>V.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span></b><![endif]><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E75B6;mso-themecolor:
accent5;mso-themeshade:191;mso-style-textfill-fill-color:#2E75B6;mso-style-textfill-fill-themecolor:
accent5;mso-style-textfill-fill-alpha:100.0%;mso-style-textfill-fill-colortransforms:
lumm=75000'>Preview + Build Hugo Site + Convert Site Folder to Git Repository <o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0in 5.4pt 0in 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td width=623 valign=top style='width:467.5pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0in 5.4pt 0in 5.4pt'>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span class=SpellE><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>hugo</span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  <o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>[move _<span class=SpellE>config.yml</span>
  &amp; README.md to public folder]<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>cd public<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git <span class=SpellE>init</span><o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git <span class=GramE>add .</span><o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git commit -m “new blog added”<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git remote add origin <span
  class=SpellE><span class=GramE>git@github.com:vaya-lluvia</span></span><span
  class=GramE>/<span class=SpellE>vaya-lluvia.github.io.git</span></span><span
  style='color:black;mso-themecolor:text1'><a
  href="mailto:git@github.com:vaya-lluvia/vaya-lluvia.github.io.git"></a></span><o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git pull –rebase origin master<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git pull origin master<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>git push -u origin master<o:p></o:p></span></p>
  <p class=MsoNormal style='margin-top:3.0pt;margin-right:0in;margin-bottom:
  3.0pt;margin-left:0in;line-height:115%'><span style='font-family:"Arial",sans-serif;
  mso-fareast-font-family:"Source Han Serif CN"'>[repository settings </span><span
  style='font-family:Wingdings;mso-ascii-font-family:Arial;mso-fareast-font-family:
  "Source Han Serif CN";mso-hansi-font-family:Arial;mso-bidi-font-family:Arial;
  mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  pages </span><span style='font-family:Wingdings;mso-ascii-font-family:Arial;
  mso-fareast-font-family:"Source Han Serif CN";mso-hansi-font-family:Arial;
  mso-bidi-font-family:Arial;mso-char-type:symbol;mso-symbol-font-family:Wingdings'><span
  style='mso-char-type:symbol;mso-symbol-font-family:Wingdings'></span></span><span
  style='font-family:"Arial",sans-serif;mso-fareast-font-family:"Source Han Serif CN"'>
  branch: master; /(root)]<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='line-height:115%'><b><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN";color:#2E74B5;mso-themecolor:
accent5;mso-themeshade:191'>References <o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Arial",sans-serif;
mso-fareast-font-family:"Source Han Serif CN"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Source Han Serif CN",serif;
mso-bidi-font-family:Arial'><a
href="https://mp.weixin.qq.com/s?src=11&amp;timestamp=1656432496&amp;ver=3888&amp;signature=R057QVwURCYG1tl6WQBAMfsHmc6gXA27RWJ2pVXIWPP5OBqTC0wZtbx-2Y-rbGbKHLEZZuVuWQYEeF6pOufnYJ5L9wrPwYfvqawqPPB2HOETYNQKIoEegIO*7TxGtTsP&amp;new=1"><span
lang=ZH-CN>用</span><span class=SpellE>Github</span><span lang=ZH-CN>做了个免费永久博客，超详细过程！</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Source Han Serif CN",serif;
mso-bidi-font-family:Arial'><a
href="https://mp.weixin.qq.com/s/3DBIJh21Une_FwyprVB2XQ?forceh5=1"><span
class=SpellE>HuGo+Github</span>-<span lang=ZH-CN>快速搭建个人博客</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Source Han Serif CN",serif;
mso-bidi-font-family:Arial'><a
href="https://mp.weixin.qq.com/s?src=11&amp;timestamp=1656455173&amp;ver=3889&amp;signature=acljkOMk91v0Wbtk9obloE*aqvyrmxDBVC1XiTZHO6NNmTKAqIA3*Iv69sQ1a*ECO1DzS2iscHetq1pkpP02q35rl3SKsoXa5ggqg1vsQCmyTHLY6p3mFhhkMJQwCMi8&amp;new=1"><span
lang=ZH-CN>如何利用</span> GitHub Pages <span lang=ZH-CN>和</span> Hugo <span
lang=ZH-CN>轻松搭建个人博客？</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:115%'><span style='font-family:"Source Han Serif CN",serif;
mso-bidi-font-family:Arial'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
