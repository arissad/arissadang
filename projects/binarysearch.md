---
layout: project
type: project
image: ../img/binary-search-tree11.jpg
title: "Word Frequency Finder"
date: 2024
published: true
labels:
  - binary trees
  - java
summary: "A binary search tree project I made for ICS 211."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

In this project I made for my ICS 211 class, I used a binary search tree to make a word finder that will count the amount of times words were used in a document.

Here is some code that was used in the search:

```cpp
byte ADCRead(byte ch)
public BinaryStringTree(String fileName) {
		root = null;
		size = 0;
		try {
			File file = new File(fileName);
			Scanner scanner = new Scanner(file);
			while (scanner.hasNext()) {
				StringBuilder fixedWord = new StringBuilder();
				String word = scanner.next();
				for (char c : word.toCharArray()) {
					if (Character.isLetter(c)) {
						fixedWord.append(c);
					}
				}
				if (fixedWord.length() > 0) {
					add(fixedWord.toString());
				}
			}
```
This project overall helped me to better understand how binary search trees worked. It was a pretty difficult concept at first and I remember having a hard time with this project, but ultimately it helped me in the long run.
