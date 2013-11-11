This article is about two important four-letter words that start with “F
”: “flat” and “form.
”<aside class="content-minutiae"></aside>

Though some decry flat user interfaces as pure fashion, or the obvious response
to skeuomorphic trends, many designers have embraced the flat approach because 
the reduction in visual styling (such as gradients, drop shadows, and borders) 
creates interfaces that seem simpler and cleaner.
  

The problem is that most flat UIs are built with a focus on the provision of
content, with transactional components (i.e., forms) receiving very little 
attention. What happens when flat and forms collide? User experiences can, and 
often do, suffer.

## Forms matter

When I say forms, I mean **any interaction in which information is exchanged to
receive a product or a service**. This includes everything from internet
banking to mobile commerce, from signing up to use a new tablet app to running a
web search.

**User needs for the design of forms can differ greatly from user needs for the
design of content**, as summarized in the table below. <figure>

| Forms                                                    | Content
|

| Task completion                                          | Exploration and
task completion
|
| Users are “field focused”                                | Users are not
“field focused
”            |
| Often only one entry and exit point                      | Many possible
entry and exit points
|
| Concepts of “success” and “failure” are strictly defined | Concepts
of “success” and “failure” vary
|
| Often used only once                                     | Often visited many
times
|</figure>

Foremost, **forms are about task completion**. I’m sure I’m one of only a
handful of people in the world who actually check out forms for fun; every other
(reasonable) person just wants to fill out the form to get their car registered 
or buy those shiny new shoes. With content, however, finishing a task isn’t 
always a priority. Sometimes, we just want to browse without a specific end 
point in mind. (Wikipedia, I’m looking at you.
)

People approach task completion in ways that differ from such exploration.
Observe a person filling out a form, and you’ll see they “zoom in” on the fields,
referring to instructions, tips, and even the field labels or questions only as 
a need arises. There’s an order: a place to start and a place to finish, and at 
the finish point they (usually) know whether they have succeeded or failed.

Content, on the other hand, can often be accessed via any range of paths and
sources, and people move around and focus on that content in various ways. The 
idea of success is still relevant, but it shifts because of the diversity of use
cases.

A focus on task completion also means that a user is likely to fill out your
form only once, whereas the related content may be visited many times. 
Consequently, there is scant opportunity for a user to learn a form’s visual 
language (e.g., that there are no buttons, only links
).

## Flat equals less information

So forms and content are distinct. What does that have to do with flat UIs? 

The problem is that in the push for simplicity, flat UIs may have gone *too*
far. With content, things like drop shadows, gradients, and borders may well be 
no more than useless
“[embellishments][1].” When we read a multi-page news article, it doesn’t
matter much whether the mechanism to move to the next page is a button or a link.
With forms, however, distinguishing between a button and a link matters far more.

Take the example of a form’s “submit” and “cancel” actions. Clearly
these two actions have very different results, and we want users to quickly and 
easily use the one that meets their needs. This is why I and others—including 
respected designer Luke Wroblewski—recommend presenting the primary action (
submit) as a button and secondary actions (cancel) as links. The visual design 
doesn’t just provide aesthetics, it communicates the difference in functionality
and relative priority.

The [Klout][2] form below, on the other hand, demonstrates the loss of
information that often happens with flat UIs. Placing “cancel” before “submit” 
is a pretty nasty[dark pattern][3], but let’s put that aside for now. The
flat UI approach styles both the primary and secondary actions as links—with the
same text color and background—which slows users down, as they have to pay more 
attention before acting.<figure class="single-image">

![][4]</figure>
Imagine how much more usable this form would be if the difference in actions
was communicated through the visual design (again, putting aside the dark 
pattern
):<figure class="single-image">

![][5]</figure>
## The three biggest ways flat forms fail 

The Klout example above nicely demonstrates the three largest ways in which
flat UI forms often fail to deliver user-friendly experiences:

1.  Lack of affordance (affordance is how much the design of an object—
    physical or digital—suggests use, like a chair inviting you to sit
    )
2.  Insufficient distinction *between* form elements (e.g., fields versus
    labels versus instructions versus buttons
    )
3.  Insufficient hierarchy *within* categories of form elements (e.g., primary
    versus secondary buttons
    )

The Klout “cancel” and “submit” actions lack affordance because their
designs don’t invite the appropriate interaction. They would look clickable if 
they had the shape of a button (they are actions, after all) or were at least 
underlined (the conventional affordance for links on the web
).

Form elements are also not well-differentiated: the only thing visually
separating clickable links from non-clickable text is the text color.

When it comes to hierarchy within links, the Klout example is particularly
interesting. Appearing first, “cancel” has some prominence over “submit” (hence 
the dark pattern—there’s an established convention and inherent psychological 
association that people expect what comes first to be the most common option). 
But other than this subtle distinction, the two links have exactly the same 
style. Yet they are not equivalent (regardless of whether you view the form from
Klout’s or the user’s side
).

So how do you avoid these pitfalls while maintaining a flat UI? The trick is to
**add just enough visual treatment to convey affordance, form elements, and
hierarchy**. You can do this by focusing on the most important elements on your
form:**fields** and **buttons**, which are the core of form interactivity. 

## Tweaking the design of your fields and buttons

You’ll go a long way to making your flat form usable if you **make your fields
look hollow** and **make your buttons look raised**. Such design provides
affordance and differentiates form elements.

The screenshot below, of the [Lowdi][6] speaker purchase process, shows what
happens if you fail to do this. The design of both the quantity field and the 
buy button are so flat, they don’t invite the appropriate interactions. Without 
careful inspection, users won’t realize that they can change the quantity, and 
will struggle to find what to click to proceed to the next step.
  <figure class="single-image-90">

![][7]</figure>
Here’s how to distinguish and give affordance to fields and buttons:<figure>



| What to do                   | How to do it
|

| Make fields look **hollow**  | *   Give fields a border or inset shadow, even
if only 1px wide
*   Eliminate background color
|
| Make buttons look **raised** | *   Include drop shadow, rounded corners,
gradient, or border, however slight or subtle
*   Use a background color different from that used for both the page and form
fields
|</figure>

### Fixing fields

Let’s look at a before and after, focusing first on fields. The mobile sign-
up form for Hipstamatic’s[Oggl][8] starts with the first screen below. Finding
the place to tap in your email address is like an Easter egg hunt (but not as 
fun). Compare this to the alternative designs I mocked up, shown second and 
third. The second design simply adds a border around the field, setting it as a 
distinct element. The third design includes the border and removes the page 
background from the field. Using the form is now seamless. Both alternatives 
have a flat UI, but significantly better affordance—especially the third version.

![][9]![][10]![][11]</figure>
When Facebook released graph search, 
[it discovered the hard way how important it is to have fields that appear hollow][12]

![][13]</figure>
### Balancing buttons

Here’s another before and after, now with buttons. 

In the real estate mobile search example below, we have the original version on
the left and an alternative—and I suspect, more usable—version on the right.<
figure class="multi
">

![][14]![][15]</figure>
In the original design, the button was so flat it could easily be confused with
a heading, footer, or other content block. Reducing the button’s width from full
screen and adding rounded corners gives it greater affordance (while still 
having plenty of area for touch
).

### Primary versus secondary actions

Finally, don’t forget to style primary actions differently from secondary
actions. There are two ways to do this:

*   Use buttons for the primary action and links for secondary actions
*   Use more prominent styling on the primary action button, relative to
    secondary action buttons
   

As an example of best practices, [Fiverr][16] uses links for secondary actions
on its sign-up form.<figure>

![][17]</figure>
And for further improvement, Riki Tanone demonstrates how to distinguish
primary and secondary buttons in her[blog UI template on Dribbble][18].<figure
>

![][19]</figure>
## More information equals better accessibility

You may have noticed that a more usable, intuitive flat UI form involves some
degree of redundancy. It’s often not just one visual design component (e.g., 
color) that communicates difference. Instead, it might be color*and* shape, or
color*and* size.

This redundancy makes the interface accessible to a wider range of users, as
the design doesn’t rely on the user being able to perceive or understand the one
visual distinction that informs the type of interactivity.

Color is a great example. [Approximately 12 percent of the population][20] has
vision with some color deficiency. If color is the only thing distinguishing non
-clickable text from clickable links, as the Klout example showed, you’re 
immediately making things difficult for approximately 12 percent of your users.

Compare this with the recommendation that [I][21], [Luke Wroblewski][22], and
many others make, that required questions should be marked with a red asterisk (
as shown on the left). Here, both color*and* shape communicate to the user, so
that the form is still usable by those with color-deficient vision (who might 
see it as shown on right
).<figure class="multi">

![][23]![][24]</figure>
## Best of all worlds

As designers, we want to create great user experiences through simplicity and
clarity.

What is simplicity and clarity? It’s the user knowing exactly *what* to do, and
*how* to do it, with a minimum of effort. Achieving this kind of user
experience means finding the right*balance*—not just going flat for flatness
’s sake.

When it comes to forms—frustrating experiences even at the best of times—it
means knowing that less isn’t always simpler.

 [1]: http://mattgemmell.com/2013/06/12/ios-7/
 [2]: http://klout.com/
 [3]: http://darkpatterns.org/
 [4]: img/Klout-original.jpg
 [5]: img/Klout-fixed.jpg
 [6]: https://lowdi.com/
 [7]: img/lowdi-original.png
 [8]: http://hipstamatic.com/oggl/
 [9]: img/Oggl-left.png
 [10]: img/Oggl-mid.png
 [11]: img/Oggl-right.png

 [12]: http://www.fastcodesign.com/1673209/how-facebook-fixed-the-biggest-design-flaw-in-graph-search#1
 [13]: img/facebook.png
 [14]: img/real-estate-search-original.png
 [15]: img/real-estate-search-fixed.png
 [16]: http://fiverr.com/
 [17]: img/fiverr-login.png

 [18]: http://dribbble.com/shots/968433-Freebie-PSD-Flat-UI-Kit-2-Blog/attachments/111312
 [19]: img/riki-tanone.png
 [20]: http://joeclark.org/book/sashay/serialization/Chapter09.html
 [21]: http://formulate.com.au/articles/mandatory-versus-optional-fields/
 [22]: http://www.lukew.com/resources/web_form_design.asp
 [23]: img/asterisks.png
 [24]: img/asterisk-bw.png