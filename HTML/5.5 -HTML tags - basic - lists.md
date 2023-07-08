# **Lists are a great way to organize information on your web page.**

HTML supports two types of lists: **unordered (bulleted) lists** and **ordered (numbered) lists**. Additionally, HTML also **supports definition lists.**

## **Unordered Lists**
Use the `<ul>` tag to start an unordered list. Each item within the list is placed between `<li>` (list item) tags. For example:

```HTML
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```
This will display as:

- Coffee
- Tea
- Milk

## **Ordered Lists**
Use the `<ol>` tag to start an ordered list. Just like with an unordered list, each item within the list is placed between `<li>` tags. For example:

```HTML
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

This will display as:

1. Coffee
2. Tea
3. Milk

## **Definition Lists**
These are slightly more complex. They are used to define a list of terms, with a description of each term. The `<dl>` tag is used to start the list, `<dt>` for the term itself, and `<dd>` for the term's description. For example:

```HTML
<dl>
  <dt>Coffee</dt>
  <dd>A hot beverage made from the roasted and ground seeds of a tropical shrub.</dd>
  <dt>Milk</dt>
  <dd>A white liquid produced by the mammary glands of mammals.</dd>
</dl>
```

This will display as:

Coffee 
	: A hot beverage made from the roasted and ground seeds of a tropical shrub.
Milk 
	: A white liquid produced by the mammary glands of mammals.

###### Nested lists are also possible, where you can place lists inside other lists for more complex structures.

