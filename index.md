---
layout: default
title: Leonardo Ortiz
---
<div class="blurb">
	<h1>Leonardo Ortiz</h1>
	<p>Husband, programmer, father of 2 cats</p>
</div>
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```