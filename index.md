---
layout: default
---

<h1><b>Software is supposed to help businesses work smarter, faster, and cheaper... right? So why do software budgets get blown even faster than deadlines?</b></h1>

<p>What if your software organization could deliver <b>information, asset protection, and revenue</b> - <i>quickly</i>?</p>

<p>I've spent over a decade helping <b>great people make great teams</b>, so they can <b>make great software</b>.</p>

<p><b>I can help you too. <a href="mailto:pat@patmaddox.com">Email me</a>.</b></p>

<p><i>Are you an individual looking to become an expert Ruby on Rails developer? <a href="http://www.rubysteps.com">I've got just the thing</a>...</i></p>

<p><img src="/images/bj_and_pat.jpeg"/></p><p><i>That's me on the right, working through a Ruby on Rails programming problem with one of my friends, BJ Clark</i></p>

<a name="testimonials"></a>

<h2>What it's like to work with me</h2>

<blockquote>Pat and I met at a conference, his disarming demeanor is a character that allows him to fold into most teams and build close relationships. It was several years later when we came to work together that I really began to understand his technical prowess, dedication to delivering the best possible outcome, and desire to share his knowledge. - Jim Remsik, <a href="http://adorable.io">Adorable</a></blockquote>

<blockquote>I worked with Pat on a large-scale consumer analytics and authentication project for an internationally-recognized music brand. It was a great honor to work along side of him and benefit from his insights and opinions into the code, APIs and design we were working with, as well as effective ways to test-drive out code. I’ve also had the opportunity to work and watch with Pat in various workshops and sessions, and have always found it beneficial. In short, Pat is someone high up on my list when I talk about teams I’ve been lucky to work with, and I’m sure he’ll be high on yours, too! - Cory Foy, <a href="http://theironyard.com">The Iron Yard</a></blockquote>

<a name="start-here"></a>

<h2>New to this site? Start here</h2>

<p>These are the articles that people have found most useful over the years</p>

<ul>
<li><a href="/2014/11/24/pro-tips-for-full-stack-developers.html">So you want to become a full-stack developer...</a></li>
<li><a href="/2014/10/03/mob-programming-w-alistair-cockburn-videos.html">Mob Programming w/ Alistair Cockburn videos</a></li>
<li><a href="/2014/08/05/company-sponsored-learning.html">Investing in our industry's future with company-sponsored learning</a></li>
<li><a href="/2014/08/02/young-programmers.html">"Young" programmers</a></li>
<li><a href="/2014/05/15/poof-and-then-rails-was-gone.html">*poof*... and then Rails was gone</a></li>
<li><a href="/2013/11/16/what-peyton-manning-can-teach-us-about-agile-development.html">What Peyton Manning can teach us about agile development</a></li>
<li><a href="/2012/03/27/some-books-for-software-oriented-humans.html">Some Books for Software-oriented Humans</a></li>
<li><a href="/2011/10/12/the-hidden-agile-value-respect.html">The Hidden Agile Value: Respect</a></li>
<li><a href="/2011/07/26/one-doctors-model-for-continuing-education.html">One Doctor's Model for Continuing Education</a></li>
<li><a href="/2011/05/09/how-to-hire-programmers.html">How to Hire Programmers</a></li>
<li><a href="/2010/11/15/four-lessons-from-the-rails-rumble.html">Four Lessons From the Rails Rumble</a></li>
<li><a href="/2010/10/13/technical-debt.html">Technical Debt</a></li>
<li><a href="/2010/10/29/behavioral-methods-in-activerecord.html">Behavioral Methods in ActiveRecord</a></li>
<li><a href="/2010/05/19/are-you-punching-your-users-in-the-face.html">Are You Punching Your Users in the Face?</a></li>
<li><a href="/2010/04/16/if-i-were-submitting-my-resume-for-a-rubyrails-job.html">If I Were Submitting My Resume for a Ruby/Rails Job...</a></li>
<li><a href="/2009/10/24/whats-needed-in-rails-maturity-or-excellence.html">What's Needed in Rails - Maturity, or Excellence?</a></li>
<li><a href="/2008/02/03/its-not-about-state-or-interactions-its-about-behavior.html">It's Not About State or Interactions, It's About Behavior</a></li>
<li><a href="/2006/12/28/hint-expert-rails-books-arent-about-rails.html">Hint: Expert Rails Books Aren't About Rails</a></li>
</ul>

<div class="home">

  <a name="articles"></a>

  <h2>Articles</h2>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
