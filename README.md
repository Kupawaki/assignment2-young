# Kooper Young

### Favorite Team Sport - Football
I like football mostly because it requires a group of people to be **perfectly coordinated** with eachother to preform successfully. Now you might be thinking - "But don't all team sports require the team to be in sync with themselvels?" And you are correct, but in **football** you get to physically batter the other team, which is fun to watch.

------------------------------------
#### Favorite Team / Players
Kansas City Chiefs

Best Players
1. Patrick Mahomes 
2. Travis Kelce
3. Harrison Butker

Other Fun Teams
* Green Bay Packers
* Buffalo Bills
* San Francisco 49ers

About Me Markdown [AboutMe.md](AboutMe.md)

--------------------------
### Tables!
| Country     | Why to Visit?                               | How Long? |
| ------------| ------------------------------------------- | ----------|
| Japan       | Amazing food, great culture                 | 3 weeks   |
| Netherlands | My friend Tom lives there, and he is great  | 2 days    |
| Italy       | Amazing food with amazing views             | 7 hours   |

-------------------------------------------------
### Quotes!

>"This isn't a chicken or an egg problem, Kooper is just wrong." ~ *Charles Hoot*

>"There is a significant overlap between the dumbest tourist and the smartest bear." ~ *Yellowstone National Park Ranger, on the subject of bear-proof trashbins*

-------------------------------------------------
### CSS Custom Checkbox - Stack Overflow Question

>How to style a checkbox using CSS?
>>I am trying to style a checkbox using the following:

>>```<input type="checkbox" style="border:2px dotted #00f;display:block;background:#ff0000;" />```

>>But the style is not applied. The checkbox still displays its default style. How do I give it the specified style?

```
li:not(#foo) > fieldset > div > span > input[type='radio'],
li:not(#foo) > fieldset > div > span > input[type='checkbox'] {
  /* Hide the input, but have it still be clickable */
  opacity: 0;

  float: left;
  width: 18px;
}


li:not(#foo) > fieldset > div > span > input[type='radio'] + label,
li:not(#foo) > fieldset > div > span > input[type='checkbox'] + label {
  margin: 0;
  clear: none;

  /* Left padding makes room for image */
  padding: 5px 0 4px 24px;

  /* Make look clickable because they are */
  cursor: pointer;

  background: url(off.png) left center no-repeat;
}

/* Change from unchecked to checked graphic */
li:not(#foo) > fieldset > div > span > input[type='radio']:checked + label {
  background-image: url(radio.png);
}
li:not(#foo) > fieldset > div > span > input[type='checkbox']:checked + label {
  background-image: url(check.png);
}
```
Source of code [Source](https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons/)
