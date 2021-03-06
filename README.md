# Markdown Exploration

This is a test project to explore the Markdown format and Github flavored Markdown.

## Contents

1. [Introduction](#intro)
2. [Quotes](#quotes)
3. [Headings](#headings)
4. [Lists](#some-list-examples)
5. [Code](#some-code-examples)
6. [Horizontal Rules](#horizontal-rules)
7. [Links](#links)
8. [Emphasis](#emphasis)
9. [Images](#images)
10. [Tables](#markdown-table)
11. [Emoji](#emoji)
12. [Commits](#commits)

## Intro

<table>
  <tr>
    <th>Markdown</th>
    <th>HTML</th>
  </tr>
  <tr>
    <td>Writing format</td>
    <td>Publishing format</td>
  </tr>
  <tr>
    <td>Only uses punctuation for syntax</td>
    <td>Uses tag syntax</td>
  </tr>
</table>

Above is some HTML that was inserted into this .md file.

This is ean example of a <font color='red'>span level</font> HTML tag used in Markdown. However, it doesn't work on Github because Github does not support span level inline HTML for markdown.  

This paragraph features a break tag above it.

## Headings

## This is an example of an H2 heading

#### This is an example of an H4 heading with a closing Hash #


## Quotes

Below is a quote:

> What are these primary dispositions on which Freud himself apparently founders? Are these attributes of an unconscious libidinal organization, and how precisely do the various identifications set up in consequence of the Oedipal conflict work to reinforce or dissolve each of these dispositions? What aspect of “femininity” do we call dispositional, and which is the consequence of identification? Indeed, what is to keep us from understanding the “dispositions” of bisexuality as the effects or productions of a series of internalizations? Moreover, how do we identify a “feminine” or a “masculine” disposition at the outset? By what traces is it known, and to what extent do we assume a “feminine” or a “masculine” disposition as the precondition of a heterosexual object choice? In other words, to what extent do we read the desire for the father as evidence of a feminine disposition only because we begin, despite the postulation of primary bisexuality, with a heterosexual matrix for desire?

And a verbose type nested quote:

> In “Mourning and Melancholia,” the lost object is set up within the ego as a critical voice
> or agency, and the anger originally felt for the object is reversed so that
> the internalized object now berates the ego:
>
> > If one listens patiently to the many and various self-accusations of the
> > melancholic, one cannot in the end avoid the impression that often
> > the most violent of them are hardly applicable to the patient himself,
> > but that with insignificant modifications they do fit someone else,
> > some person whom the patient loves, has loved or ought to love....
> > the self-reproaches are reproaches against a loved object which have
> > been shifted onto the patient’s own ego. (169)
>
> The melancholic refuses the loss of the object, and internalization
> becomes a strategy of magically resuscitating the lost object, not only
> Gender Trouble because the loss is painful, but because the ambivalence felt toward the
> object requires that the object be retained until differences are settled.
> In this early essay, Freud understands grief to be the withdrawal of
> libidinal cathexis from the object and the successful transferral of that
> cathexis onto a fresh object.

And a simple type nested quote:

> The construction of the interior ego ideal involves the internaliProhibition, Psychoanalysis, and the Heterosexual Matrixzation of gender identities as well. Freud remarks that the ego ideal is
a solution to the Oedipal complex and is thus instrumental in the
successful consolidation of masculinity and femininity:
>
> > The super-ego is, however, not simply a residue of the earliest
object-choices of the id: it also represents an energetic reaction-formation against these choices. Its relation to the ego is not exhausted
by the precept: “You ought to be like this (like your father.)” It also
comprises the prohibition: “You may not be like this (like your
father)—that is, you may not do all that he does; some things are his
prerogative.” (24)
>
> The ego ideal thus serves as an interior agency of sanction and
taboo which, according to Freud, works to consolidate gender identity
through the appropriate rechanneling and sublimation of desire.

*Italics Text: Courtesy of Judith Butler, Gender Troubles*

Below is some quote blocks containing Markdown elements:

> This is the first line of my quote what else can I say?
>
> 1. I could talk about markdown allowing lists
> 2. Or even allowing other elements:
>
> > *Here is a nested quote in italics*
>
> How exciting!

You can also quote code:

> The beginning of a quote:
>
> `git make quote`
>
> end quote

## Some list examples

Below is an unordered list:

* 商品
* 秘密の山口
* 筋トレ
* ラーブリー
* 無理夢中

And an unordered list with mixed symbols:

* コーヒー
+ チョコレート
- クリーム

However, these don't work and just create several new lists.

Below is an indented oredered list:

  1. Wake up
  2. Learn Markdown
  3. Push to Github


Below is a list with paragraphs:

1. This is some Markdown that is part of a list.

    And this is some more markdown in the same paragraph.
2. This is another item in the list.
3. And a third item.


Here is a nest list:

1. First list item
   1. Nested list item
   2. Nested list item 2
2. Second main list item


Here is a task list:

- [x] Travel to Alaska
- [ ] Plant some pine trees
- [ ] Ride a moose
- [ ] \(Feed the moose my wedding ring)




## Some code examples

Here is a normal paragraph:

  This is some code.
  
*The above example will not display on github because it doesn't support idented code blocks*


For github use:

```
function func() {
  console.learn('Markdown');
}
```

Here is some code with syntax highlighting enabled:

```ruby
(1..20).each do |x|
  puts "The number is #{x}."
end
```

* Here is some code in a list

    ```
    Some code
    ```
* Here is the next item in the list
* And another one.

Here is some `inline_code()` stuff.

Unfortunately this no longer works on Github:
Here is some `puts inline_code(:my_code)`{:.ruby} with syntax highlighting.

Here is some ``inline_Code(`)`` which contains a backtick literal.

Here is some `` `inline_code()` `` which contains adjacent backtick literals.


## Horizontal Rules

Now lets have a horizontal rule:

---

And another:
***

And on more with HTML
<hr />

Here's some heading text created using rule syntax
---


## Links

Here is an example of [link](https://www.w3schools.com/tags/att_a_href.asp) placed in line.

This is another [link](https://www.pcmag.com/encyclopedia/term/href "PC Mag") but with a Title.

Here is a [link to](#markdown-exploration) the header at the top of this page.

Here is an [example][id] of an ID based link.

Here is a link to [Google][] that uses text content based ID.

[id]: https://www.w3schools.com/html/html_id.asp "ID Link"

[Google]: https://google.com/

Here is an automatic link: <https://eudoxos.github.io/cfitness/html/cfitness.html>

Here is a link to an [external relative resource](info/information.md)


## Emphasis

Here is some _text_ with *different* levels of __emphasis on words__ to demonstrate **HOW** emphasis works.

**Here is some _nested italics_ within bold text for extra emphasis.**

***Here everything is italics and bold***

Here some ~~text that was a mistake~~ stuff that I need to get rid of.

\*You can also escape your emphasis indicators like this\*


## Images

Here is a lovely image of a snooker table: 

![Snooker Image](https://homepages.cae.wisc.edu/~ece533/images/pool.png "Snooker")

Here is a dancing cat ![dancing cat][cat_dance] as an inline image using image ID.

[cat_dance]: https://upload.wikimedia.org/wikipedia/commons/8/8c/Mura.gif "Dancing cat"

Here is an image that has been placed inline with markdown and scaled using the HTML `<img>` tag: <img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Mura.gif" alt="Smiley face" height="42" width="42">

Here is an animated gif of the flag for the state of Maryland. It has been linked to as a relative resource:
![maryland](images/marylandFlag.gif)


## Markdown table

Here is a basic table:

| Markdown  |Table  |Headings |
|---        |---    |---      |
| Info      | fig7  | *899*   |
| MG78      | fig11 | 85      |
| __G0StringIndicator__ | fig14 | 99 |

Here is a table with alignment options:

| Table | with | aligned | columns |
| :----- | :------: | -----: | :------ |
| left aligned | centre aligned | right aligned | back to normal |
| $ | & | £ | 2 |

Here is a table with links and content:

| Markdown  |Link   |Table |
|---        |---    |---      |
| [Location][tlink1]      | [XHVUN-FM][tlink2]  | `do_operation()`   |
| > tiny corgi     | ![corgi][tlink3] | * bullet      |

[tlink1]: https://en.wikipedia.org/wiki/North_Side,_Binghamton "Binghamton"
[tlink2]: https://en.wikipedia.org/wiki/XHVUN-FM "XHVUN-FM"
[tlink3]: https://img.icons8.com/plasticine/100/000000/corgi.png "Tiny Corgi"

## Emoji

Here is a vampire 🧛.

Here is my :bowtie:


## Commits

Here is a link to a commit: https://github.com/dpwdec/markdown-exploration/commit/7a0c1d4733f6220edf5d977bd58518b3504e2a7a
