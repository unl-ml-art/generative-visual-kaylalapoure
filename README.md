# Project 3 Generative Visual: Creation

Kayla LaPoure, klapoure2@huskers.unl.edu

## Abstract

Many creation stories have similar undertones, I am curious if AI, machine learning will pick that up. Taking multiple creation stories from a variety of cultures and/ or religions, I created images using text to image generation. I am curious about the differences the AI sees among each story. The creation stories I chose are Christianity, Islam, Taoism, The Ute’s creation story, and Babylonian creation story. I chose this group of religions to include a variety of stories that weren't Eurocentric. I chose Christianity because that's the religion I personally follow, Islam because a large percentage of the world believes in it, Taoism because it's something that isn't necessarily known or as common in America, Ute because it's a Native American community from where I am from and including their voices is incredibly valuable, and I included Babyonian creation story to include something that isn't familiar with modern day people. As I mentioned I wanted to include a wide variety of religions from across the world, some of which are familiar and others that are not. 

This project isn’t to sway people one way or another to specific religious spaces, but to recognize the differences and similarities to what people believe about our creation. I think recognizing this and finding the beauty in it even if you don’t inherently believe it would help give a better perspective of what and how others think. 

To make this project I will feed the first few sentences in chunks to produce five images for each creation story. For open studios, these images will be printed out and arranged in a grid. 


## Model/Data

I used BigGAN, a text-to-image synthesis. 
I changed the prompts to small chunks of each creation story. I predominantly used the beginnings of each creation story. Here are the chunks of each creation story that I used:

Christianity: "1 In the beginning, when God created the universe,[a] 2 the earth was formless and desolate. The raging ocean that covered everything was engulfed in total darkness, and the Spirit of God[b] was moving over the water. 3 Then God commanded, “Let there be light”—and light appeared. 4 God was pleased with what he saw. Then he separated the light from the darkness," [Genesis 1:1-4]

Islam: “It is He Who has created you from dust then from a sperm-drop, then from a leech-like clot; then does he get you out (into the light) as a child: then lets you (grow and) reach your age of full strength; then lets you become old,- though of you there are some who die before;- and lets you reach a term appointed; in order that you may learn wisdom.” [40:67]

Taoism: "In the beginning of time, there was only chaos. The elements and gasses of the heavens and earth freely mingled, and the organizing principle was dormant. It lay dormant somewhere inside this elemental cosmos, awaiting the right moment to begin the transformation. The shape of this primeval mass was something like an egg.
For 18,000 years the universe remained in this state, until the incubation was finally complete, and the egg hatched. Then the heavens and the earth came into existence. The lighter, most pure substances floated upward and became the heavens. These elements were named yang. The heavier, more impure substances descended and became the earth. These were named yin."

Ute Creation Story: "The Utes trace their origin to Sinauf, a god who is half man, half wolf. Along with his brothers, Coyote and Wolf, Sinauf kept the world in balance. In preparation for a long journey, Sinauf made a magical bag that he filled with sticks. All the sticks were different, and when placed in the bag they became people. As Sinauf put more sticks in the bag, the people became noisy. Sinauf’s brother Coyote grew curious from the noise, so he cut a little hole in the bag with his flint knife and peeked in. He laughed at the strange new creations and their many songs and languages." 

Babylonian Creation Story: "Before anything had a name, before there was firm ground or sky or the sun and moon there was Apsu, the sweet water sea and Tiamat, the salt water sea. When these two seas mingled, they created the gods Lahmu and Lahamu, who rose from the silt at the edge of the water. When Lahmu and Lahamu joined, they created the great gods Anshar, Kishar and Anu. From this generation of gods there arose mighty Ea and his many brothers.
Each text block was broken down into logical breaks in the sentences."

## Code

Jupyter Notebook: https://crane-ood.unl.edu/node/c2613.crane.hcc.unl.edu/4530/lab/tree/ml-art-code/clip-biggan/text_to_image_CLIP_BigGAN.ipynb

It also is included in the files

## Results

I included the images digitally and what specific code that generated them. As mentioned, I chose to use the beginnings of Christianity, Islam, Taoism, The Ute’s creation story, and Babylonian creation stories. 
There’s a lot of similarities with circles early in the story that then progresses into something different, which in some sense is the essence of a lot of these stories. 

First Photo for Christianity:

![cv1](https://user-images.githubusercontent.com/78117204/166503270-372396fd-a50c-4f70-a8eb-f80b299f0d55.jpg)

First Photo for Islam:

![iv1](https://user-images.githubusercontent.com/78117204/166503340-17095e6a-4aed-4757-a0ba-dfbceb49720a.jpg)


First Photo for Taoism:

![ti2](https://user-images.githubusercontent.com/78117204/166503367-f7dc23c9-4719-4b66-b741-f8023018970c.jpg)


First Photo for the Ute Creation Story:

![ui](https://user-images.githubusercontent.com/78117204/166503402-910859cd-64b2-4e16-8144-d1a7bc2a58f0.jpg)


First Photo for the Babylonian Creation Story:

![bi](https://user-images.githubusercontent.com/78117204/166503430-19675cc6-7e80-45df-9ef7-75e92790f1c7.jpg)


## Technical Notes

I included the elements used to create each image; in order to create it, include it in the folder when you run it. 

## Reference

https://www.biblegateway.com/passage/?search=Genesis%201&version=GNT

https://www.worldhistoryedu.com/creation-myths-from-around-the-world/

https://muslimmatters.org/2012/02/03/the-creation-of-man-as-mentioned-in-the-quran/

https://creationstoriesmyths.weebly.com/taoism.html?c=mkt_w_chnl:aff_geo:all_prtnr:sas_subprtnr:1538097_camp:brand_adtype:txtlnk_ag:weebly_lptype:hp_var:358504&sscid=41k6_txi11
https://utahindians.org/archives/ute/earlyPeoples.html#:~:text=The%20Utes%20trace%20their%20origin%20to%20Sinauf%2C%20a,a%20magical%20bag%20that%20he%20filled%20with%20sticks.

http://www.bigmyth.com/download/BABYLONIAN_CREATION.pdf
