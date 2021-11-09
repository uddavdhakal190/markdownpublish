### Exercise 1

# Italics and Bold

1. Writing in Markdown is _not_ that hard!
2. I **will** complete these lessons!
3. "__Of course__," she whispered. Then, she shouted: "All I need is **a little moxie**!"
4. If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.


# Headers

1. 
#Header one
##Header two
###Header three
####Header four
#####Header five
######Header six

2. 
#Colombian Symbolism in _One Hundred Years_ of Solitude

Here's some words about the book _One Hundred Years..._.


# Links

1. [Search for it.](www.google.com)
2. [You're **really, really** going to want to see this.](www.dailykitten.com)
3. ####[The Latest News from the BBC](www.bbc.com/news)
4. 
Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com


# Images

1. ![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)
2. 
![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png


# Blockquotes
1. 
I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

2. 
>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
His father told him that story: his father looked at him through a glass: he had a hairy face.
>
He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

3. 
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: *VIVE L'IRLANDE*!


# Lists

1. 
* Flour
* Cheese
* Tomatoes

2. 
  1. Cut the cheese
  2. Slice the tomatoes
  3. Rub the tomatoes in flour

3. 
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

4. 
* Calculus
    * A professor
    * Has no hair
    * Often wears green
* Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell

5. 
1. Cut the cheese
  >Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes
  > Be careful when holding the knife.
  For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

# Paragraphs

1. 
We pictured the meek mild creatures where   
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

2. 
1. Crack three eggs over a bowl.

 * Now, you're going to want to crack the eggs in such a way that you don't make a mess.

 * If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 * Basically, take the same guidance as above: don't be messy, but if you are, clean it up!



### Exercise 2

_Markdown_ is a lightweight markup language for creating formatted text using a _plain-text editor_. **John Gruber** and **Aaron Swartz** created _Markdown_ in __2004__ as a markup language that is appealing to <u>human readers in its source code form</u>.



### Exercise 3

![My favourite  pet](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

[![My Video : Click here](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=i2kdIbn0Uoc)

## Exercise 4

```
public class Person
{
  private string name;
  private int age;
  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}

```