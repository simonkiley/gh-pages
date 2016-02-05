---
layout: post
title: Learn about Countries!
description: "This script opens a random country's wikipedia page."
modified: 2015-09-15
tags: [wiki, wikipedia, countries, python]
image:
  feature:
  credit:
  creditlink: 
---
Mostly a test post...

This python script selects a random country from a list of countries in [countries.txt](https://gist.github.com/marijn/396531#file-countries-txt) (compiled by Github user [marijn](https://github.com/marijn)) and opens it in your default browser.

Here is the short and simple code:

```python
 import webbrowser
 import random
 
 def main():
	 with open("countries.txt") as f:
		countries = f.readlines() # 241 countries
		random_list_value = random.randint(0, 241)

		country_name = countries[random_list_value][3:]
		country_name = country_name.replace(" ", "_")
		webbrowser.open_new("https://en.wikipedia.org/wiki/"+country_name)

 if __name__ == '__main__':
	main()
```

Check it out on [Github](https://github.com/simonkiley/random-wiki-countries)



