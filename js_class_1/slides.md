% title: Programing from Zero to Repo Hero
% subtitle: via Javascript
% author: Paige Hubbell
% author: Other info to put on the author line
% thankyou: Thanks everyone!
% thankyou_details: And especially these people:
% contact: <span>www</span> <a href="http://www.google.edu/">website</a>
% contact: <span>github</span> <a href="http://github.com">username</a>
% favicon: http://www.stanford.edu/favicon.ico

---
title: Debunking some Myths
build_lists: true

- you don't need to be good at math
- only super nerds can bend computers to their will
- programming is only for developers/programers/evil genuises
- goal: understanding variables and how to get started in Javascript
- star power bonus level: logic, **if** we've gotten this far **then** we're doing great!

---
title: What is a Program?
subtitle: via JavaScript
build_lists: true

program or  ( sometimes ) programme  (ˈprəʊɡræm)
 
 — n
 1.   a sequence of coded instructions fed into a computer, enabling it to perform specified logical and arithmetical operations on data 

---
title: So How Do You Give A Computer Instructions?
subtitle: via a language
build_lists: true

- computers only know one real language, on and off
- luckily we have built ontop of that!
- participation time! Name some computerlanguages you've heard of.

---
title: So how do you give instrucitons to Computers?
subtitle: Subtitles are cool too
class: img-top-center

<img height=150 src=figures/200px-6n-graf.svg.png />

- Some point to make about about this figure from wikipedia
- This slide has a class that was defined in theme/css/custom.css

<footer class="source"> Always cite your sources! </footer>

---
title: What is Javascript
subtitle: and what is it good for?
class: img-top-center

> JavaScript (JS) is a dynamic computer programming language.[5] It is most commonly used as part of web browsers, whose implementations allow client-side scripts to interact with the user, control the browser, communicate asynchronously, and alter the document content that is displayed.[5] It is also being used in server-side network programming (with Node.js), game development and the creation of desktop and mobile applications.

- don't forget Javascript =/= Java!

<footer class="source"> wikipedia </footer>

---
title: Segue slide
subtitle: I can haz subtitlz?
class: segue dark nobackground

---
title: Maybe some code?

press 'h' to highlight an important section (that is highlighted
with &lt;b&gt;...&lt;/b&gt; tags)

<pre class="prettyprint" data-lang="javascript">
function isSmall() {
  return window.matchMedia("(min-device-width: ???)").matches;
}

<b>function hasTouch() {
  return Modernizr.touch;
}</b>

function detectFormFactor() {
  var device = DESKTOP;
  if (hasTouch()) {
    device = isSmall() ? PHONE : TABLET;
  }
  return device;
}
</pre>

