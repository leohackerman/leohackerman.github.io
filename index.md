---
layout: default
title: Leonardo Ortiz
---
<div class="blurb">
	<img class="avatar avatar-small" src="https://avatars2.githubusercontent.com/u/42592238?v=4" alt="Leonardo Ortiz" width="40" height="40" />
	<h1>Leonardo Ortiz</h1>
	<p>Husband, programmer, father of 2 cats</p>
</div>


```ruby
def show
  puts "Outputting ... "
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
```
