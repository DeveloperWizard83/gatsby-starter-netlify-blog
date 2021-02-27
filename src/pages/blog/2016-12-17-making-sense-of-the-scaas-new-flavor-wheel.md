---
templateKey: blog-post
title: Learning to code blog day 1
date: 2021-02-25T09:58:16.435Z
description: |+
  What I learned today.

featuredpost: false
featuredimage: /img/flavor_wheel.jpg
tags:
  - coding
  - boolean
  - javascript
---
![flavor wheel](/img/flavor_wheel.jpg)

Previously I have always tried to get the return value of true or false, but now I understood that I can only get a number and check it and get the true or false from that. This is new logic I gained.

I think the most fun thing in programming is to develop the logical thinking and the best way to do that is to do these coding challenges. I like to use edabit because the challenges are not too hard.

function forbiddenLetter(char, arr) { 
	let check = arr.join('').search(char)
	if(check < 0){
		return true
	}else{
		return false
	}
	
}