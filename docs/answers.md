layout: page
title: "Answers"
permalink: /assignments/Answers/


## Exercise 1

### Italics and bold
Writing in Markdown is _not_ that hard!

I **will** complete these lessons!

"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.


### Headers

# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six

#### Colombian Symbolism in _One Hundred Years of Solitude_

Here's some words about the book _One Hundred Years..._.

### Links
[Search for it.](www.google.com)

[You're **really, really** going to want to see this.](www.dailykitten.com)

#### The Latest News from [the BBC](www.bbc.com/news)


Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com


### Images
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

### Blockquotes

I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
His father told him that story: his father looked at him through a glass: he had a hairy face.
>
He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!


### Lists

* Flour
* Cheese
* Tomatoes

1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

* Calculus
    * A professor
    * Has no hair
    * Often wears green
* Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell

<!-- for some reason the next part of this exercise has different intendation in the test window and in VSC for me, and I can't seem to figure out why... -->

1. Cut the cheese

 Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes

 Be careful when holding the knife.
 
 For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

### Paragraphs

We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

1. Crack three eggs over a bowl.  
Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
Basically, take the same guidance as above: don't be messy, but if you are, clean it up!


## Exercise 2

### ColdFusion
**ColdFusion Markup Language** or CFML is a Java-based scripting language used mainly for web development. It augments standard HTML files with database commands, conditional operators, high-level functions etc. CFML has multiple commercial as well as open source implementations such as **Adobe ColdFusion**, **Lucee** and **Railo**. CFML was originally designed back in _1995_ by [Jeremy Allaire](https://en.wikipedia.org/wiki/Jeremy_Allaire) at the company the _Allaire Corporation_ he and his brother ran before being aquired by Adobe in 2005, hence the afformentinoned _Adobe ColdFusion_.

### Fountain
**Fountain** is a free and open-source markup language for screenplay editing _inside a text editor_ instead of having to buy licenses for dedicated screenplay tools like [Final Draft](https://en.wikipedia.org/wiki/Final_Draft_(software)) (which at time of writing [_**costs 200€**_](https://store.finaldraft.com/final-draft-12.html)). Fountain was released in 2012 after the developers of the WordPress plug-in _Scrippets_ and the developer of _Screenplay Markdown_ merged their editors into one. Since then, Fountain has been implemented in many different editors such as **Emacs**, **Vim** and **Visual Studio Code**.


## Exercise 3

[![Youtube video](http://img.youtube.com/vi/IdkCEioCp24?t=70/0.jpg)](http://www.youtube.com/watch?v=IdkCEioCp24?t=70)

<!-- video embed/thumbnail loading doesn't work 100% for me, but that is probably a permission issue-->

![Puppy pic](https://i.redd.it/ii9co6rw2ky71.jpg)

## Exercise 4

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