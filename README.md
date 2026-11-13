# Learning about the box model

The box model is a concept in css guiding layouts and the shape of contents

## contents
- [parts](#parts-of-a-box-box-model)
- [Qualities of a box model](#qualities-of-the-box-model)
- [Things to check out for](#things-to-check-out-for)
- [Tabular description](#tabular-description-of-the-box-model-parts)
- [Code samples](#code-sample-representing-a-box)


## Parts of a box Box model

- Margin
- Padding
- Boder
- Content

### Qualities of the Box Model.

1. Presence of a proper box
2. Bordes defined.box
3. Contents within the box borders
4.  Spaces if required

### Things to check out for

- [x] Confirm box size 
- [x] Apply any sizing if required.
- [] Spaces can be applied

### Tabular description of the box model parts
| Part | Purpose |
|----|----|
| __Box__ | Represent the elements container |
|Padding | spacing between the content and the element's border|
|Border| Defines the boundary of the box
|Margin | specifies the spacing around the box element |

### Code sample representing a box

```
<div>

```
```css
.box {
    /*defines the box size*/
    width: value;
    height: value;

    /* border*/
    border: 1px solid black;

    /* spacing within & out*/
    padding:20px
    margin:20px
}
```

>### **Note**

>If peradventure you'd like to understand more about the box model, you can go to [Resource](https://w3schools.com)
>> _Research it at your discretion. Just sharing what i know for now._

<a href="#learning-about-the-box-model" style="text-align: right;">Top</a>