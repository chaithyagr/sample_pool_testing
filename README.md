# Sample Pool Testing

This repository holds multiple sample codes to model pool testing for Covid 2019

Here are some refrences:
Pool testing of clos families: https://m.hindustantimes.com/india-news/govt-mulls-new-testing-approach/story-eD4ZiGlrdaynBRPSebpJoO.html

Original research :
https://healthcare-in-europe.com/en/news/corona-pool-testing-increases-worldwide-capacities-many-times-over.html
https://eurekalert.org/pub_releases/2020-03/guf-pto033020.php

Some first code by Teju: https://gist.github.com/teju85/0c9a16b8ccf31d6155211d0e276672a3


# Ideas

1) Try to see how to split up a large population to pools, if we have prior probablities.
2) Compressed sensing implementable? Note that the result is `A or B or C` and not A + B + C. This could be a limiting factor.
3) Overlapping groups? Can we have overlapping groups? The issue in 2) could limit us here also.
