---
layout: default
title: BibTex
permalink: /bibtex/
---

<div style="max-width: 1000px; margin: 0 auto; padding: 20px;">
  <h3 style="text-align: center;">BibTex</h3>

  <!-- Copy Button -->
  <button class="copy-btn" onclick="copyCode()">Copy</button>

  <pre><code id="bibtex-code" class="language-bibtex">
@inproceedings{zhou2024less,
  title={Less Is More: Vision Representation Compression for Efficient Video Generation with Large Language Models},
  author={Yucheng Zhou and Jihai Zhang and Guanjie Chen and Jianbing Shen and Yu Cheng},
  booktitle={OpenReview},
  year={2024},
  url={https://openreview.net/pdf?id=S7yRfgmnpm},
}
  </code></pre>
</div>

<!-- JavaScript -->
<script>
  function copyCode() {
    // Get the code from the code block
    var code = document.getElementById('bibtex-code').innerText;
    
    // Create a temporary textarea element to copy the text
    var textArea = document.createElement('textarea');
    textArea.value = code;
    document.body.appendChild(textArea);

    // Select the text inside the textarea
    textArea.select();
    textArea.setSelectionRange(0, 99999); // For mobile devices

    // Execute the copy command
    document.execCommand('copy');

    // Remove the temporary textarea element
    document.body.removeChild(textArea);

    // Alert the user that the code has been copied
    alert('BibTex code has been copied!');
  }
</script>

<!-- Styles -->
<style>
  .copy-btn {
    background-color: #4CAF50; /* Button background color */
    color: white;              /* Button text color */
    border: none;              /* Remove button border */
    padding: 10px 20px;        /* Button padding */
    font-size: 14px;           /* Button text size */
    cursor: pointer;          /* Pointer cursor on hover */
    border-radius: 5px;        /* Button border radius */
    margin-top: 10px;          /* Space between the button and code block */
  }

  .copy-btn:hover {
    background-color: #45a049; /* Darker background on hover */
  }
</style>
