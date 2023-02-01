---
layout: default
---

**EFRI BRAID: Using Proto-Object Based Saliency Inspired by Cortical Local Circuits to Limit the Hypothesis Space for Deep Learning Models**

The object of this project is to use the biologically plausible [proto-object saliency](https://doi.org/10.1016/j.visres.2013.10.005) for sparsifying connectivity in Deep Neural Networks to ultimately achieve parsimonious yet efficient training and inference compute.

<!-- <a href="url", style>link text</a> -->

<p style="text-align: center;"> <a href="./team.html">[See the Team]</a> </p>

<p style="text-align: center;"> More Content coming soon!</p>

**Project Abstract:** <br>
Deep learning has achieved impressive performance in many tasks, which is driven by the capacity for backpropagation to “assign credit” to a vast array of parameters. Typical networks have immensely complex computational graphs, with many options to assign credit for every computation. A large number of options comes with the benefits of being very flexible in learning, but also with costs of large energy consumption and many needed examples for learning. A selection of important (salient) features will cause inductive biases in learning, but such biases, when appropriately conditioned, can be optimally selected, as is done in biology via evolution or development. For our project, the selection mechanism will be inspired by biology (Aims 1&2) or learned (Aims 3&4), and will be instantiated in software and hardware.
The process of selection is akin to the attention mechanisms of mammals. We previously developed state-of-the art models, based on neurophysiology, of bottom-up and top-down attention and suggested how perceptual organization can reshape and focus attention. We showed how such mechanisms of attention which can predict human behaviors can be implemented using local circuits in the cortex and in neuromorphic hardware.
We propose to construct a hybrid architecture, where local circuits implement a bottom-up attention, or saliency module that provides a “gate” for selecting features for a global learning network with a convolutional architecture. The saliency module will decrease the number of features considered for inference and for learning by including a learned prior of what features are important. We hypothesize that after determining and implementing optimal attentional mechanisms for a set of tasks/input statistics, they will substantially reduce power requirement for both inference and learning, as well as allowing learning with considerably fewer examples than traditional methods.
Such a model can also help answer the question of why some visual cortex neurons have their properties explained by convolutional neural networks while others mimic saliency models, and why biology learns with few examples. We can also answer determine optimal learning architecture for hardware and benchmark them against existing systems.

<!-- 
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

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
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

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

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

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


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
``` -->
