---
layout: post
title:  "Roda versus Rails"
author: neeraj
categories: [ Ruby, Rails, Roda ]
tags: [ruby, rails, Roda, jeremy evans]
image: assets/images/roda.svg
description: "Rails is old web framework with MVC architecture. It is more stable, mature and popular. Roda is relatively new and claims to be a substitute of Rails. Is it really better than Rails?"
hidden: true
featured: true
rating: 4.5
comments: true
---

Few days back, I heard about [Roda](http://roda.jeremyevans.net/) which could suppose to be a replacement of [Rails](guides.rubyonrails.org). [Roda](http://roda.jeremyevans.net/) is a routing tree web toolkit, designed for building fast and maintainable web applications in ruby. The creator of [Roda](http://roda.jeremyevans.net/) is [Jeremy Evans](https://github.com/jeremyevans). ```Rails is dead``` we hear it every years and it is more widespread after twitter's jump from [Rails](guides.rubyonrails.org) to Scala. 

According to [Jeremy Evans](https://github.com/jeremyevans), [Roda](http://roda.jeremyevans.net/) provides Simplicity, Reliability, Extensibility and Performance. [Roda](http://roda.jeremyevans.net/) has low per-request overhead, and the use of a routing tree and intelligent caching of internal datastructures makes it significantly faster than popular ruby web frameworks. But as per my opinion, Rails is good and getting more mature, stable and popularity every year. Here I will compare these two over some points.

### Prerequisites
---
I am assuming that you have some basic knowledge of Roda and have built at least one app in Roda. Otherwise, please have a look at http://roda.jeremyevans.net.

### Comparison
---

<div class="row">
	<div class="col-md-6">
		<a href="guides.rubyonrails.org">Rails</a> is a stable framework which is very old and already having a large community support. Also it supports lot of different rubygems.
	</div>
	<div class="col-md-6">
		Most of rubygems are independent ruby libraries. Therefore all rubygems which are not tightly tied with Rails and activerecord can be used with <a href="http://roda.jeremyevans.net">Roda</a> too. Additionally, <a href="http://roda.jeremyevans.net">Roda</a> has its own compatible rubygems e.g. roda-i18n, newrelic-roda, roda-basic-auth, roda-rest_api, rodauth etc. But still these are not having proper documentation.
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		<a href="guides.rubyonrails.org">Rails</a> is a stable framework which is very old and already having a large community support. Also it supports lot of different rubygems.
	</div>
	<div class="col-md-6">
		Most of rubygems are independent ruby libraries. Therefore all rubygems which are not tightly tied with Rails and activerecord can be used with <a href="http://roda.jeremyevans.net">Roda</a> too. Additionally, <a href="http://roda.jeremyevans.net">Roda</a> has its own compatible rubygems e.g. roda-i18n, newrelic-roda, roda-basic-auth, roda-rest_api, rodauth etc. But still these are not having proper documentation.
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		<a href="https://github.com/plataformatec/devise">devise</a> is a rubygem which we use for our authentication purpose. It provides not only the authentication, but it also provides lot of flexibility while integration. It also opens the scope of integration of authentication of different social networking e.g. facebook, twitter, google etc.
	</div>
	<div class="col-md-6">
		<a href="http://roda.jeremyevans.net">Roda</a> also comes with <a href="https://github.com/beno/roda-auth">roda-auth</a> which provides simple authentication. It contains omniauth, but not maintaining any documentation to implement in <a href="http://roda.jeremyevans.net">Roda</a> app.
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		The size of core contributors (with at least 3 commits) is more than 100. | The size of core contributors (with at least 3 commits) is significantly lesser. 
	</div>
	<div class="col-md-6">
		It is good for mid level as well as bigger application. | As compared over http://roda.jeremyevans.net/why.html with Sinatra, <a href="http://roda.jeremyevans.net">Roda</a> is good for small applications.
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		It is good for mid level as well as bigger application.
	</div>
	<div class="col-md-6">
		As compared over http://roda.jeremyevans.net/why.html with Sinatra, <a href="http://roda.jeremyevans.net">Roda</a> is good for small applications.
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		People are having more interest to search about <a href="guides.rubyonrails.org">Rails</a>.
	</div>
	<div class="col-md-6">
		Interest on <a href="http://roda.jeremyevans.net">Roda</a> is significantly less.
	</div>
</div>
<br />
<img src="/assets/images/roda-vs-rails.png" alt="Interest over time of Roda and Ruby on Rails" width="740" height="338" class='img-responsive'>


### Conclusion
---
I think every rails programmer should try [Roda](http://roda.jeremyevans.net/) once. It will provide you a better understanding and knowledge about different rubygems. You can get the opportunity to dig deeper into ruby libraries and their usage too. 
