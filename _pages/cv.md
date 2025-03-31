---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div id="cv-selector" style="margin-bottom: 20px;">
  <button onclick="showCV('en')">English</button>
  <button onclick="showCV('fr')">Français</button>
</div>

<div id="cv-container">
  <iframe id="cv-object" src="/files/CV_Hanbang_io_en.pdf" width="100%" height="800px">
    Your browser does not support viewing PDFs.
    <a href="/files/CV_Hanbang_io_en.pdf">Download the PDF</a>.
  </iframe>
</div>

<script>
function showCV(lang) {
  var cvObject = document.getElementById('cv-object');
  if (lang === 'en') {
    cvObject.setAttribute('src', '/files/CV_Hanbang_io_en.pdf');
  } else if (lang === 'fr') {
    cvObject.setAttribute('src', '/files/CV_Hanbang_io_fr.pdf');
  }
}
</script>


