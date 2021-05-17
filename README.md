
# doubleloopgames.github.io
![Push continuous integration](https://github.com/doubleloopgames/doubleloopgames.github.io/workflows/Push%20continuous%20integration/badge.svg)

Double Loop Games website instructions

---

**To add team members**

1) Resize and crop profile image to width: 552px ; height: 368px.
2) Optimize the photo (if you can) and save it in the `/images` folder.
3) In the code below, replace the text in [BRACKETS].
4) In `index.html`, place the new code block along with the other `<li>`'s in the "Who we are" section, in the order you'd like.
5) Commit the code into the Github Repo.
```
<li class="bio-[NAME]">
  <img src="images/[IMAGE_FILENAME]" alt="[FIRST LASTNAME]">
  <strong class="name">[FIRST LASTNAME]</strong>
  <span class="title h5 h5-alt">[TITLE]</span>
  <p class="bio">
    [BIO - ABOUT 100 CHARACTERS]
    <a href="[TWITTER_URL]" class="twitter" target="_blank">[@TWITTER_HANDLE]</a>
  </p>
</li>
```
Example:
```
<li class="bio-emily">
  <img src="images/bio-emily.jpg" alt="Emily Greer">
  <strong class="name">Emily Greer</strong>
  <span class="title h5 h5-alt">Co-Founder, <span class="title-2">CEO - Business Lead</span></span>
  <p class="bio">
    Loves tower defense, match-3s, knitting, data, and figure skating
    <a href="https://www.twitter.com/EmilyG" class="twitter" target="_blank">@EmilyG</a>
  </p>
</li>
```

---

**To add news articles**

1) Resize and crop article image to width: 375px ; height: 300px.
2) Optimize the photo (if you can) and save it in the `/images` folder.
3) Copy and paste the code below and replace the text in [BRACKETS].
4) In `index.html`, place the new code block with the other `<a>`'s (with class of 'article' in the "News" section, in the order you'd like.
5) Commit the code into the Github Repo.
```
<a href="[ARTICLE_URL]" class="article" target="_blank">
  <div class="image">
    <img src="images/[IMAGE_FILENAME]">
  </div>
  <div class="content">
    <p class="inner-content">
      <span class="date h5">[DATE]</span>
      <span class="title">[ARTICLE TITLE]</span>
      <span class="full-post h5 h5-alt">Learn more</span>
    </p>
  </div>
</a>
```
```
<a href="https://venturebeat.com/2020/02/12/double-loop-games-raises-2-5-million-to-make-mobile-games-for-everyone/" class="article" target="_blank">
  <div class="image">
    <img src="images/news-2020_02_10.jpg">
  </div>
  <div class="content">
    <p class="inner-content">
      <span class="date h5">February 12, 2020</span>
      <span class="title">Double Loop Games Announces $2.5M Seed Investment Led by London Venture Partners</span>
      <span class="full-post h5 h5-alt">Learn more</span>
    </p>
  </div>
</a>
```
---

**Work is needed for**

+ Add more job postings
+ Have no job postings listed
+ Change or add a game to the games section
