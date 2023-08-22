---
layout: default
---



<center><font size="6"> Abstract </font><br/> </center>

We propose a foundation model named BPT for modeling intracranial recordings, which learns powerful representations of intracranial neural signals by pre-training, providing a large-scale, off-the-shelf model for medicine. BPT is the largest model in the field of brain signals and is pre-trained on a large corpus of intracranial data collected by us. The design of BPT is to capture long-term temporal dependency and spatial correlation from neural signals, combining the information in both time and frequency domains. As a foundation model, BPT achieves SOTA performance on various downstream tasks (i.e. neural signal forecasting, frequency-phase forecasting, imputation and seizure detection), showing the generalization ability to a broad range of tasks. The low-resource label analysis and representation visualization further illustrate the effectiveness of our pre-training strategy. In addition, we explore the effect of model size to show that a larger model with a higher capacity can lead to performance improvements on our dataset. The source code and pre-trained weights are available at https://anonymous.4open.science/r/BPT-30AB.



<center><font size="6"> Contributions </font><br/> </center>

- We propose a foundation model for intracranial neural signals named BPT, which is the largest model on brain signals (shown in Fig. 1) and pre-trained on a large intracranial dataset collected by us, providing a large-scale and off-the-shelf model for medicine.

- To our knowledge, BPT is the first to date that attends long-term dependency and captures spatial correlation across channels, while combining the information from both time and frequency domains.

- Extensive experiments show that BPT generalizes well to various downstream tasks w.r.t. several medical scenarios, showing the great potential in neural recordings modeling. Further analysis illustrates the effectiveness of large-scale pre-trained model, demonstrating the medical value of our work.









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
```
-->
