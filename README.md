# from-mukku
markdown
# Deepika
###### favourite restaurant: Simply Siam Thai Restaurant
The **bearcat** commons is very Taste food for a **good price**. sitting place is very clean. Truly remarkable.

---

# My Favorite Dishes at Barcats

1. Grilled Salmon Salad
2. Spicy Shrimp Tacos
3. BBQ Chicken Pizza

## My Favorite Dishes at Barcats

1. Grilled Salmon Salad
2. Spicy Shrimp Tacos
3. BBQ Chicken Pizza

### Places to Visit Near Barcats

- City Park
- Artisan Coffee House
- Riverfront Plaza
---

## Books Recommendations

I've curated a list of diverse books, songs, and videos that I highly recommend. Each recommendation has its unique appeal, whether it's the compelling storyline, the melodic tunes, or the thought-provoking content. Take a look at the table below to discover some enriching content.

| Name               | Reason for Recommendation                                 | Creator                   |
| ------------------ | --------------------------------------------------------- | ------------------------- |
| "The Alchemist"    | A timeless tale of self-discovery and following one's dreams. | Paulo Coelho             |
| "Bohemian Rhapsody" | An iconic rock masterpiece with a blend of genres and emotions. | Queen                    |
| "Inception"         | Mind-bending sci-fi thriller that challenges your perception. | Christopher Nolan        |
| "Thinking, Fast and Slow" | Explores the two systems that drive the way we think.  | Daniel Kahneman          |

---

## Inspirational Quotes

> "Be the change that you wish to see in the world."
> - *Mahatma Gandhi*

> "Spread love everywhere you go. Let no one ever come to you without leaving happier."
> - *Mother Teresa*

---
### Code fencing

Decorator to create a singleton class.

```
def singleton(myClass):
	instances = {}
	def getInstance(*args, **kwargs):
		if myClass not in instances:
			instances[myClass] = myClass(*args, **kwargs)
		return instances[myClass]
	return getInstance

@singleton
class TestClass(object):
	pass

```
Link to snippet source is <https://code.pieces.app/collections/python>
