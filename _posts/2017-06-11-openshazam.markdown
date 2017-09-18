---
layout: post
title: An open source song comparison tool</a>
git: https://github.com/kirtivr/osshazam
---

Audio fingerprinting to find how similiar two songs are. An interesting use case was the Led Zeppelin v/s Tarus plagiarism <a href="http://www.rollingstone.com/music/news/led-zeppelin-prevail-in-stairway-to-heaven-lawsuit-20160623">lawsuit</a>.
I used a parallelizable FFT based fingerprinting algorithm based on Shazam's <a href="http://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf">paper</a>, with some significant modifications.
The fun part was running the FFT based algorithm on our CS cluster at Dartmouth.
The results have been encouraging.