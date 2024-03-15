# 01 Shrinking scroll

> Working Period : 20240315 ~
> Steal From:

## what is "Shrinking Scroll"

My Youtube feed algorithm recommends a video in which some Youtube editor recommends her desk setup.
This project is steal from that video, but, actually, I don't know the content of the video.
Because the very beginning of the video, I see cool video effect, and I'm gonna try to mimic it in web, as a scrolling effect.

And that Video effect is this.

[대충 뭐 하는 비디오 gif](source)

I think the layout of this video effect is very similar to the layout of the website.
So if it's possible to integrate it into the first part of the website, I think that's a pretty impressive start.

## Tear Down

To make it, first things to do is break down.

The screen shrinks, showing the nav items at the top and the title element at the bottom.
If we define the title and the top menu as 'additional elements'

1. Screen Shrinks
2. 'Additional Elements' revel (pops up?)

## Blue Screen

The configuration of the implementation is simple.
However, the implementation of scrolling can be a bit ambiguous.
Should be considered whether to implement the collapse and add elements at the **same time** or **_separately_**.

First, making each element separately and then trying it out on a mockup page and see how it works together.
Additionally, finally result may have to consider the pagination.
