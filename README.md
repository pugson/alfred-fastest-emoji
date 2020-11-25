# FAstest eMOji Search (FAMOS)

### FAMOS speaks many languages!
![](demo-images/multilingual.png)
FAMOS uses [emojibase][3], which is an excellent library, meticulously
curated. So, all the languages that [emojibase][3] supports, FAMOS automatically
does too.


### FAMOS is the fastest!
**10x** to **20x** faster compared to [alfred-emoji][1] and [EmojiTaco][2]!

FAMOS launches in under 20 miliseconds (imperceptible), while both
the other workflows take hundreds of milliseconds to launch (very
much perceptible).

The reason FAMOS exists is that I wanted my emoji picker to:
 - launch instantly
 - search with zero lag
 - let me pick skin-tones for each individual emoji


### Skin-tone prefs for each individual emoji
I like my emojis to reflect my skin-tone correctly. **And also hair color!**
That means, I might not always get both. So, I want hand-emojis to
have my skin-tone, but all face-emojis to have my hair-color
(and wrong skin-tone). In addition, if you're a stickler like me,
you will understand that I want one skin-tone for the palm and
a different one for the back of the hand. Back of the hand is a shade darker
than the palm, isn't it!

1. Search results show if an emoji has multiple tones available:
   ![](demo-images/skin-tone-1.png)
2. Hold command:
   ![](demo-images/skin-tone-2.png)
3. After pressing command+enter:
   ![](demo-images/skin-tone-3.png)
4. From now on, the chosen tone becomes the default tone for this emoji:
   ![](demo-images/skin-tone-4.png)


### Feature comparison
Both [alfred-emoji][1] and [EmojiTaco][2] are excellent workflows, and they
have tonnes of features that FAMOS doesn't have presently, and has no plans
of implementing. You should definitely check them out!


#### Latest and Greatest
|            | FAMOS         | [alfred-emoji][1]  |   [EmojiTaco][2]   |
|-----------:|:-------------:|:------------------:|:------------------:|
| workflow-auto-update | :x: | :white_check_mark: | :white_check_mark: |
| emoji-auto-update                   | :x: | :x: | :white_check_mark: |
| warns for unsupported emoji         | :x: | :x: | :white_check_mark: |
| simply don't show unsupported emoji | :x: | :white_check_mark: | :x: |


#### Ease of Use
|            | FAMOS         | [alfred-emoji][1]  |   [EmojiTaco][2]   |
|-----------:|:-------------:|:------------------:|:------------------:|
| remember frequently used emoji   | :white_check_mark: | :white_check_mark: | :x: |
| keyword-based search             | :white_check_mark: | :white_check_mark: | :x: |
| show keywords used for searching | :white_check_mark: | :x:                | :x: |
| instant launch, instant search   | :white_check_mark: | :x:                | :x: |

#### Skin-tones
|            | FAMOS         | [alfred-emoji][1]  |   [EmojiTaco][2]   |
|-----------:|:-------------:|:------------------:|:------------------:|
| global skin-tone preference                     | :x: | :white_check_mark: | :x: |
| all skin-tones always accessible | :white_check_mark: | :x: | :white_check_mark: |
| setting default skin-tone for individual emoji  | :white_check_mark: | :x: | :x: |

#### Other Goodies
|            | FAMOS        | [alfred-emoji][1]  |   [EmojiTaco][2]   |
|-----------:|:------------:|:------------------:|:------------------:|
| non-english languages              | :white_check_mark: | :x: | :x: |
| copy python string                 | :x: | :x: | :white_check_mark: |
| copy decoded python string         | :x: | :x: | :white_check_mark: |
| copy unicode value                 | :x: | :x: | :white_check_mark: |
| copy slack/github code             | :x: | :white_check_mark: | :x: |
| copy without skintone              | :x: | :white_check_mark: | :x: |
| default copy with autopaste option | :x: | :white_check_mark: | :x: |
| emoji icons              | apple, joypixels | any installed | apple |

[1]: https://github.com/jsumners/alfred-emoji
[2]: https://github.com/jeeftor/EmojiTaco
[3]: https://github.com/milesj/emojibase