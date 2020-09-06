---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```python
def get_chibi_object(name):
    """Get a chibi object by its character's name."""
    name = "{}_chibi".format(name)
    c = getattr(renpy.store, name, None)
    if c and isinstance(c, Chibi):
        return c
    else:
        raise Exception("Chibi object not found. {}".format(name))
```

```renpy
    call sna_main("Good thing though is that we'll be able to bring a little something to keep us occupied.", "snape_20")
    call hide_characters
    with d3

    # Show wine
    call give_reward(text=">Not grape-juice.",gift="interface/icons/item_wine.webp")

    m "That's all the persuasion I needed my friend!"
    hide screen bld1
    with d3
    pause .2

    # Teleport to door
    call play_sound("kick")
    show screen chair_left
    show screen desk
    call gen_chibi("hide")
    with d3
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head 1       | head two          | three |
|:-------------|:------------------|:------|
| item 1       | snitch            | nice  |
| other stuff  | broom riding      | nice  |
| item 2       | bad `muggles`     | hmm   |
| item 3       | good `witches`    | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Logo](/assets/title.webp)

### Large image

![Cho on a broom](/assets/cho-broom.webp)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
