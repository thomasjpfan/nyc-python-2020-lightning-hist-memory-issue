title: Collaborative Debugging and Fixing A 🐛 in Open Source
use_katex: False
class: title-slide

# Collaborative Debugging and Fixing A 🐛 in Open Source

![](images/scikit-learn-logo-notext.png)

.larger[Thomas J. Fan]<br>
@thomasjpfan<br>
<a href="https://www.github.com/thomasjpfan" target="_blank"><span class="icon icon-github icon-left"></span></a>
<a href="https://www.twitter.com/thomasjpfan" target="_blank"><span class="icon icon-twitter"></span></a>
<a class="this-talk-link", href="https://github.com/thomasjpfan/nyc-python-2020-lightning-hist-memory-issue" target="_blank">
This talk on Github: thomasjpfan/nyc-python-2020-lightning-hist-memory-issue</a>

---

class: center, middle

![:scale 100%](images/all-issues.png)

---

![:scale 65%](images/issue.png)

.footnote-back[https://github.com/scikit-learn/scikit-learn/issues/18152]

---

![:scale 65%](images/issue-code.png)

---

![:scale 65%](images/issue-memory.png)

---

class: middle, center

![:scale 50%](images/amueller.png)
![:scale 50%](images/thomasjpfan.png)
![:scale 50%](images/ogrisel.png)

---

class: middle, center

# How did we choose the solution?

![:scale 50%](images/amueller.png)
![:scale 50%](images/thomasjpfan.png)
![:scale 50%](images/ogrisel.png)

---

class: middle

![:scale 100%](images/amueller.png)

---

class: center, middle

# Reference cycles

![:scale 40%](images/cycle.png)

---

class: center, middle

![:scale 100%](images/amueller-benchmark.png)

## 850 MB

---
class: middle, center

![:scale 100%](images/thomasjpfan.png)

---

class: middle, center

![:scale 90%](images/swimming_pool.jpg)

---

class: middle, center

![:scale 100%](images/improvement.png)

---

class: middle, center

![:scale 100%](images/ogrisel.png)

---

class: middle, center

![:scale 100%](images/simplier-benchmark.png)

---

class: middle, center

![:scale 100%](images/solution.png)

---

class: middle

.g.g-middle[
.g-8[
# Conclusion
![:scale 30%](images/scikit-learn-logo-notext.png)
- Bug report with reproducible code 🐛
- Many solutions based on different approaches 💻
- Picked solution based on benchmarking + maintainability 🪑
]
.g-4.g-center[
.larger[Thomas J. Fan]<br>
@thomasjpfan<br>
<a href="https://www.github.com/thomasjpfan" target="_blank"><span class="icon icon-github icon-left"></span></a>
<a href="https://www.twitter.com/thomasjpfan" target="_blank"><span class="icon icon-twitter"></span></a>
<a class="this-talk-link", href="https://github.com/thomasjpfan/nyc-python-2020-lightning-hist-memory-issue" target="_blank">
This talk on Github: thomasjpfan/nyc-python-2020-lightning-hist-memory-issue</a>
]
]
