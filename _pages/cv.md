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
  <object id="cv-object" data="/files/CV_Hanbang_io_en.pdf" type="application/pdf" width="100%" height="800px">
    <p>Your browser does not support viewing PDFs.
      <a href="/files/CV_Hanbang_io_en.pdf">Download the PDF</a>.
    </p>
  </object>
</div>

<script>
function showCV(lang) {
  var cvObject = document.getElementById('cv-object');
  if (lang === 'en') {
    cvObject.setAttribute('data', '/files/CV_Hanbang_io_en.pdf');
  } else if (lang === 'fr') {
    cvObject.setAttribute('data', '/files/CV_Hanbang_io_fr.pdf');
  }
}
</script>

