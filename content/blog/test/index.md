+++
title = "Test blog"
date = 2021-10-03

[taxonomies]
tags = ["futures", "other"]
+++

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

<!-- more -->

Nunc eu feugiat sapien. Aenean ligula nunc, laoreet id sem in, interdum bibendum felis. Donec vel dui neque. Praesent ac sem ut justo volutpat rutrum a imperdiet tellus. Nam lobortis massa non hendrerit hendrerit. Vivamus porttitor dignissim turpis, eget aliquam urna tincidunt non. Aliquam et fringilla turpis. Nullam eros est, eleifend in ornare sed, hendrerit eget est. Aliquam tellus felis, suscipit vitae ex vel, fringilla tempus massa. Nulla facilisi. Pellentesque lobortis consequat lectus. Maecenas ac libero elit.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Blockquote

> This is a blockquote
> with several lines

## Tables

Tables aren't part of the core Markdown spec, but Zola supports them out-of-the-box.

   | Name  | Age |
   | ----- | --- |
   | Bob   | 27  |
   | Alice | 23  |

### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp; | Markdown&nbsp;&nbsp;&nbsp; | In&nbsp;&nbsp;&nbsp;                | Table  |
| ------------------------ | -------------------------- | ----------------------------------- | ------ |
| *italics*                | **bold**                   | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code` |

## Code Blocks

#### Code block with backticks

```python
prices = {'apple': 0.40, 'banana': 0.50}
my_purchase = {
  'apple': 1,
  'banana': 6
}
grocery_bill = sum(prices[fruit] * my_purchase[fruit]
                   for fruit in my_purchase)
print('I owe the grocer $%.2f' % grocery_bill)
```

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Item
    1. First Sub-item
    2. Second Sub-item

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

<mark>Skinks</mark> can often hide easily in their habitat because of their protective colouring (camouflage).

