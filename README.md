# Ingredient-Recommendation
I figured out what ingredient you should add to your recipe!

## Why?
I love food and cooking. I came across the book [The Flavor Bible](https://www.amazon.com/Flavor-Bible-Essential-Creativity-Imaginative/dp/0316118400) a while ago and was super excited about the ingredient pairings. But that was it, I didn't use it. I came across the book again and realized the reason I wasn't using this resource was because it wasn't really conveninet, so I set to make a tool that does the heavy lifting for me. This is what this project is all about. 

## What I did:
I got an epub version of the book and scraped the ingredient pairings into an sqlite database. Since the pairings were essentially edges in a graph, I had a quick look at the number of connections per nodes and saw that it wasn't great (the book had comments on many ingredients that, while helpful for a reader, were not great for scraping). So I added a component before uploading the data to format the ingredients better. 

## What I did that I didn't like:
1.  I wanted to use this project to learn SQL better, which I definitely did, but could have done more of the preprocessing directly using SQL

## How I would fix the above: 
1.  Use even more SQL
