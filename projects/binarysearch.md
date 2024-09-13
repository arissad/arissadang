---
layout: project
type: project
image: ../img/searchpaper.png
title: "Word Frequency Finder"
date: 2024
published: true
labels:
  - Binary Trees
  - Java
  - Class Project
summary: "A binary search tree project I made for ICS 211."
---

<img class="img-fluid" src="../img/binary-search-tree11.jpg">

In this project I made for my ICS 211 class, I used a binary search tree to make a word finder that will count the amount of times words were used in a document.

Here is some code that was used in the search:

```cpp
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
