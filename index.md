---
layout: default
title: Leonardo Ortiz
---
<div class="blurb">
	<h1>Leonardo Ortiz</h1>
	<p>Husband, programmer, father of 2 cats</p>
</div>

{% avatar leohackerman %}

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
