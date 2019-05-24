# Web Design @cmda-minor-web 1819

### The assignment
The assignment is to build a prototype that is accessible for a blind person.

Larissa is blind. She is using a braille and a screen reader. Many of the common design patterns do not work optimally for her because they are designed from a visual point of view.


### Deskresearch
before I made an accessible website, the first thing what was done, is a deskresearch. See here the results: <br>
• Jump from header to header. <br>
• Use high contrast.<br>
• Some people likes to zoom in with 600%. <br>
• Images need alt text. <br>
• Tables are hard to read -> Give them attributes. <br>
• Forms give them a valid and invalid states. <br>
• H2 and H3 for sections. <br>
• Give your links (if possible) one word that describes the whole link. <br>
• Search results place them at the end. <br>

• Make use of a big fonts and numbers. <br>
• Make use of audio. <br>
• Make use of scent. <br>

### First test
In the first week, I builded two prototypes to see if it is better to put the navigation at the top or bottom of the page (HTML structure).

#### Navigation at the top
<img width="1280" alt="Screenshot 2019-04-25 21 08 20" src="https://user-images.githubusercontent.com/32538678/56761706-4f091600-679e-11e9-991a-8513029025f0.png">

#### Navigation at the bottom
<img width="1280" alt="Screenshot 2019-04-25 21 08 36" src="https://user-images.githubusercontent.com/32538678/56761707-4f091600-679e-11e9-92a3-99c14ace87af.png">


During the first test round Larissa came to meet us. She told something about herself, also there was room for questions.

She said the following things: <br>

Don't think I have to make something accessible but think the website must be accessible.

*What she sees*
• Color contrast.  <br>
• Light and dark <br>

*Some basic rules* <br>
• Good descriptive headings and only use H1 one time per page!.<br>
• Use focus, loaders and sounds for feedback. <br>
• Apply the braille rules (actually the basic html rules). <br>
• Images give them an alt tag.<br>
• Don't let audio start automatically. <br>
• Script language. <br>
• Braille is for readingtext and numbers. <br>

*What she thinks*<br>
• Dropdown in navigation are bottom necks.  <br>
• Every page needs a skip to main content button.  <br>
• Navigation ALWAYS in the top of the page (html structure).  <br>
• Use voice for using the website? <br>
• Websites must provide more feedbacks. <br>

*How she experience the website*<br>
• Sometimes she lost the navigation (some pages put their navigation in the middle of their html structure.) <br>
• Airlines websites are not accessible and very complex to use. <br>
• Buienradar is not accessible. <br>
• NS is very accessible! <br>


*How she use screenreader* 
• Does not look at the page. <br>
• First reads headings, then links and lastly random tabbing.

*Golden tips* 
• NVDA is a great plugin for testing your prototype.  <br>
• It would be awesome if there is a shortcut for opening your navigation. <br>
• IFrames -> not done!

### User scenario
Larissa, 24 years old, from Texel. She is a Dutch cyclist and track cyclist who is active in para-cycling. She has a vision impairment, which means she can only see contrasts and the difference between dark and light.

Like everyone else on the web, Larissa is using the internet. Instead looking at the screen, she is using a braille and a screen reader. The only problem by using this equipment is that not every website is accessible. That is also the reason why Larissa gets lost in the web or she doesn't know what to do.

Now she wants to book a ticket by Transavia, but by doing this, she has to enter her personal information. To do this easily, there is an form created that provides feedback through sounds.

### Second test
For the second week I chose the Transavia website. From the Transavia website I chose to recreate the forms.

<img width="1280" alt="Screenshot 2019-04-25 21 29 41" src="https://user-images.githubusercontent.com/32538678/56762896-4239f180-67a1-11e9-993a-9321f1f3a813.png">

During testing I received the following feedback points:
• Give feedback when the user is done with typing. <br>
• Backspace don't give feedback. <br>
• Mobile inpupt = only numbers. <br>
• Screenreaders reads by every input article. 

*Extra points that stood out*
• To take into consideration with Braille = Tempo and keyboard (when it is new).<br>
• First go to all links. <br>
• Give good ARIA labels, other wise it will be confusing. <br>
• Make one P element and no multiple. Instead use css :) <br>
 
### Third testing
For the last testing, the feedback points have been adjusted. During testing she gave the following feedback: <br>
• Use loud and excessive sounds for feedback. <br>
• Some random audio on page? 

<img width="1280" alt="Screenshot 2019-04-26 10 23 43" src="https://user-images.githubusercontent.com/32538678/56793942-73500b80-680d-11e9-9fdc-25782b6bf261.png">


### Principles of User Interface Design

*Keep users in control*
In the prototype, feedback is provided on each input field by means of sound.

*Direct manipulation is best / Help people inline*
As manipulation there is a skip to main content and a shortcut for navigation build in.

*Consistency matters*
By using sounds what we all know, it ensures that the user does need to learn how to respond to certain sounds.

### Exclusive Design Principles

##### Study situation
Larissa is visually impaired, since I build this whole prototype for her and not for anyone else I made some research and asked her some questions. 

By building this application the deskresearch have been taken into consideration. Also Larissa has told us something that she would really like to have in a website: <br>
• It would be nice if the website gives feedback to me. <br>
• How handy it would be when a shortcut is introduced for the navigation. <br>

##### Ignore conventions
Because you are creating an application for one user, I started by ignoring some conventions how to write semantic html and css.

For example: by the first test, the screen reader literally reads all the elements what is in the HTML. To prevent this problem, there is checked whether HTML elements needs to be written on the "right" way. 

So for in my application I did not use fieldset, while correctly writing code everything must be grouped.

##### Prioritise identity
When I was building, I was thinking what could be very useful for her to use in a website. Since she said she often uses shortcuts and she said she always wanted to go fast to the navigation as fast as possible. I was thinking, why am I not going to build a shortcut for navigation?

The other thing that I have added in the application is to 

##### Add nonsense
For the nonsens part I added an jumping button when it is focused.

# Changes I made
For my appliaction I made a few changes.

### Exclusive Design Principles

##### Study situation
As previously told Larissa is visually impaired, since I build this whole prototype for her, before I could make the changes I should take a few points into consideration: <br>

• It would be nice if the website gives feedback to me. <br>
• How handy it would be when a shortcut is introduced for the navigation. <br>
• Larissa mostly uses touch and hearing for performing actions. <br>


#### Ignore conventions
have previously said that I have changed the way of coding. For example I did not used fieldset, so the screenreader would not read the word group.

Also I added some few focusable elements when Larissa is filling in the inputs and labels. And when she filled in an input element with the "correct answer", the input is giving feedback with sounds.


##### Prioritise identity
By prioritise the identity I tried to let the screenreader read her filled in aswer like it is read by a "real human". Also I tried not to use too much text for her filled in answers.

Also I am trying to repeat her filled in answers. For example when she is filling her dogs name and then the weight, the text will be "name of dog" weight is "weight of dog". 

##### Add nonsense
By adding nonsens I added different kind of sounds for her filled in answers. For example when she search for an destination flight it gives a bounce sounds. 

Also when she is filling in her own phone number, the input is giving different kind of correct tones so she will now if she is filling the right amount of numbers.

After she filled in her own fields, she can select to use a checkbox for filling her dogs information. When she checks 'yes', there will be a bark sound.

By filling in the dog form the sounds will giving feedback in form of a happy dog bark or a sad bark.


If everything is filled in and she submits the form, there will be a sound playing where the plane is flying away.

### Testing
For my application I tested with two people: <br>

##### Tjebbe
<img width="918" alt="Screenshot 2019-05-23 21 54 19" src="https://user-images.githubusercontent.com/32538678/58282264-840c8680-7da5-11e9-8941-cc70c5244856.png">

##### Loc
<img width="914" alt="Screenshot 2019-05-23 21 54 36" src="https://user-images.githubusercontent.com/32538678/58282265-84a51d00-7da5-11e9-9082-7f83c244417d.png">

##### Tim F.
• Kilo should be added. <br>
• Typing to fast, the application breaks (screenreader). <br>
• accidentally hit the enter button.<br>

By testing the application, they gave me a few feedback points: <br>
• Month only can filled in with numbers. Maybe I should also give the option name. <br>
• By filling in the inputs, they accidentally hit the enter button. <br>
• Confused by filling in the weight. Kilo? <br>


The biggest problem I had by testing, was that all users were typing very fast, so the application breaks.


##### Changes I made
The changes I made from the feedback points: <br>
• Inputs disabled enter press. <br>
• Month now both can use numbers and names. <br>
• Added the word kilo by submit dogs weight. <br>


