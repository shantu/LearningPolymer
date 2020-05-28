# LearningPolymer

https://43081j.com/2018/08/future-of-polymer


The future of Polymer is something many people have been wondering about since the introduction of version 3, and the creation of lit-html.

On one of our largest projects, I started to (slowly) migrate from 1.x to 2.x around the same time the Polymer team were working on building 3.x and lit-html.

Polymer 3.x and lit-element seem to achieve the same goal in different ways.

So where do we go after Polymer 2.x?

For a while, this question had no clear answer. However, it seems we now have a rough idea:

    If coming from Polymer 2, Polymer 3 is something you should upgrade to, as it can be mostly automated through the modulizer
    If starting from new, you should use lit-element
    If you want to go all in, do a full conversion and drink buckets of coffee (like I may have done), go straight to lit-element

It looks to me like Polymer 3 will be the last Polymer standalone library. Going forward, it will likely be split into a “legacy” (PolymerElement) and a “core”, which is the core library without the opinionated element classes.

What I figured I’ll do with this post is summarise the basic migration from Polymer to Lit.
