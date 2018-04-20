# CSS

## Selectors
- tag name
- id
- class

## Lengths and Percentages

- px (such as font-size: 12px) is the unit for pixels.
- em (such as font-size: 2em) is the unit for the calculated 
size of a font. So “2em”, for example, is two times the 
current font size.
- % (such as width: 80%) is the unit for percentages.

## Margins and padding

margin and padding are the two most commonly used properties 
for spacing-out elements. A margin is the space outside 
something, whereas padding is the space inside something.

## Pseudo Classes

- link
- visited
- hover
- focus - for form elements

## Background Images

- background-color
- background-image
- background-repeat
    - repeat, repeat-x, repeat-y
    - no-repeat
- background-position
    - which can be top, center, bottom, left, right, a length, or 
    a percentage, or any sensible combination, such as top right.

## Shadows

### Box Shadows

```css
box-shadow: 5px 5px 3px 1px grey;
```
- horizontal offset — how far the shadow is nudged to the right.
- vertical offset — how far the shadow is nudged downwards.
- blur radius — the higher the value the less sharp the shadow. 
- spread distance — the higher the value, the larger the shadow.
- color.

### Text Shadows

```css
text-shadow: -2px 2px 2px grey;
```
Same as above. Except that there is no spread-distance.


## Gradients

### Linear gradients

```css
background: linear-gradient(yellow, red);
```

### Radial gradients

```css
background: radial-gradient(yellow, green);
```

## CSS Animations

```css
transition: all 1s linear 0s;
```

- transition-property: which property (or properties) will transition.
- transition-duration: how long the transition takes.
- transition-timing-function: if the transition takes place at a constant speed or if it accelerates and decelerates.
- transition-delay: how long to wait until the transition takes place.
