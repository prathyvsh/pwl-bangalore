---
layout: default
---

<div class="home white">

  <section id="welcome-content" class="narrow">
      <p>
          What was the last paper within the realm of computing you read and
          loved? What did it inspire you to build or tinker with?
      </p>

      <p>
          Come join our community to discuss and share ideas about that awesome
          research paper with fellow engineers, programmers and learners.
      </p>

      <div id="call-to-action">
        <a id="join-community"
           target="_blank"
           href="https://www.meetup.com/Papers-we-love-Bangalore">
         Join our Community
        </a>
        <a id="propose-talk" href="#propose-talk">Propose a Talk</a>
      </div>

  <section id="faq" class="narrow">

    <!-- Cannot include markdown the obvious way.  -->
    <!-- https://github.com/jekyll/jekyll/issues/1303 -->

    {% capture my_include %}{% include FAQ.md %}{% endcapture %}
    {{ my_include | markdownify }}

  </section>
</div>
