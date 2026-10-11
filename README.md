# Personal site (static HTML, no build step)

Edit the .html files directly on GitHub (pencil icon) or locally, then re-upload.
- Home: index.html · Research list: research.html · Project pages: projects/*.html
- Photo: assets/img/profile.svg → replace (update src in index.html if the file name changes)
- Thumbnails: assets/img/thumbs/<project>.svg → replace with square images, update src in index.html and research.html
- Figures: replace <div class="figure-ph">…</div> with
  <figure><img src="../assets/img/fig/xxx.png"><figcaption>…</figcaption></figure>
- Blue status line: <p class="venue">…</p>
- Styles: assets/css/style.css

Search engines are blocked (noindex meta + robots.txt). To make the site searchable later,
delete the noindex line from every .html file and delete robots.txt.
