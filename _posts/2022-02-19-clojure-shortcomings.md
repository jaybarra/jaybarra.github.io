---
layout: post
title:  "Clojure Is Great, but..."
date:   2022-02-12 16:32:58 -0500
categories: clojure
---

Clojure is a fantastic language, functional, simple, hooked into the Java ecosystem. 

But Clojure is likely to remain a niche and boutique language for as long as Lisp languages remain seen as fringe.

{% highlight clojure %}
(defn- helper-fn
  "private helper function"
  [x]
  (foo x))

(defn exposed-fn
  "Some exposed function"
  [x y]
  (bar x (helpe-fn y)))
{% endhighlight %}
