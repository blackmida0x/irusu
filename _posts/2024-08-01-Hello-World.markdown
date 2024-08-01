---
layout: post
title:  "Syntax highlighting"
date:   2019-11-06 01:11:00 +0100
categories:
---


# Syntax highlighting
This theme supports syntax respectively code highlighting. Below you find some examples of different programming languages.

<br />ruby:
{% highlight ruby %}
def foo
  puts 'foo'
end

def bubble_sort(list)
  return list if list.size <= 1 # already sorted
  swapped = true
  while swapped do
    swapped = false
    0.upto(list.size-2) do |i|
      if list[i] > list[i+1]
        list[i], list[i+1] = list[i+1], list[i] # swap values
        swapped = true
      end
    end
  end

  list
end
{% endhighlight %}
