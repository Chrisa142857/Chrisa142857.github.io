---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<!--<embed src="https://github.com/Chrisa142857/Chrisa142857.github.io/blob/293786f0fafaf79812a6d8d550477bfbfe0e2ebb/files/ziquanwei_cv.pdf" width="500" height="375" type="application/pdf">!-->

<embed src="/files/ziquanwei_cv.pdf" width="100%" height="auto" type="application/pdf">

<!--<script src="//mozilla.github.io/pdf.js/build/pdf.mjs" type="module"></script>

<script type="module">
  var url = 'https://raw.githubusercontent.com/Chrisa142857/Chrisa142857.github.io/main/files/ziquanwei_cv.pdf';

  var { pdfjsLib } = globalThis;

  pdfjsLib.GlobalWorkerOptions.workerSrc = '//mozilla.github.io/pdf.js/build/pdf.worker.mjs';

  var loadingTask = pdfjsLib.getDocument(url);
  loadingTask.promise.then(function(pdf) {
    console.log('PDF loaded');

    var pageNumber = 1;
    pdf.getPage(pageNumber).then(function(page) {
      console.log('Page loaded');

      var scale = 1.5;
      var viewport = page.getViewport({scale: scale});

      var canvas = document.getElementById('the-canvas');
      var context = canvas.getContext('2d');
      canvas.height = viewport.height;
      canvas.width = viewport.width;

      var renderContext = {
        canvasContext: context,
        viewport: viewport
      };
      var renderTask = page.render(renderContext);
      renderTask.promise.then(function () {
        console.log('Page rendered');
      });
    });
  }, function (reason) {
    console.error(reason);
  });
</script>!-->

<canvas id="the-canvas"></canvas>


{% include base_path %}

