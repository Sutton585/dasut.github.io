---
layout: nonHome
---

# Why Iterative Design?

For Low-budget and Low-barrier projects, this can be the most productive approach. It's main strength is that you can repeat for as many iterations as you need. One of the biggest assets of the iterative design pattern I will outine is it's simplicty and abilty to be adapted to many types of design projects.

When planning a project for iterative development, one of the most important distinction is that you set a minimum number of iterations, not a maximum. Designs for traditional applications have been measured to have improved usability by 38% per iteration (Nielsen http://www.useit.com/alertbox/design-diversity-process.html). Websites can be even higher. This is in the neighborhood of where we are developing (UI/Interaction Design), we can safely make a consirvative estimate of around 25%. Having set a minimum amount of iterations per major benchmark is more useful than only allowing yourself X iterations until ship. We are aiming to minimize how much we are guessing on our product. In this method, ihteration and testing are king; even a slight change in a new iteration with minimal testing is safer than shipping your best guess.

# Overcoming the Limitations of Iterative Design

For our purposes, there are very few drawbacks to producing quick and inexpensive iterations and testing them. The chief among these being that, on some level, you are just trying to find the most usable version of your last idea. It doesn't really allow you to see if there is something that needed to be addressed in the initial concept that is hampering your product. It is very difficult to allow yourself to throw out something you have made gone through five rounds of iterations and testing because it MIGHT be better if you use a different approach to the whole project.

This limitation is as real with high budget projects as it is with personal projects. Sending a project to square one is a hard sell to your boss, and even more so the more hierarchy it needs to pass through. For personal projects as well, if you have been tinkering with a design for a few months, scrapping the whole thing is easily misconstrued as a loss of those months.

One method of dealing with this potential limitation is to implement "limited parallel design". The concept of parallel design can be as broad as you feel appropriate. On a conservative approach, you can test up to three versions of a menu system for navigation on your website. You could also take the approach of having three designers each produce an entire iteration to themselves, and test all of those as individual products.

The reason I am using the term "limited" is not that the iterations should have limitations on what can be changed, but that you should be very conscious of how many branches you have at any given time. At some point, the wisest course of action WILL BE to find out how to integrate these parallel designs into one master design. In general, no single design tested in parallel will be your final product; you should be able to reconcile the best working elements of different parallel iterations into a master iteration. This becomes exponentially harder to create the more branches are active.


# Navigating this Writing
The way this writing will be laid out is I will give an overview of the interaction design development cycle, go into detail on what to keep in when approaching each step, and follow it up with a real-world example of a personal project of mine, and how it uses this system. The key to being able to properly use this development plan is that you have access to rapid prototyping and are able to do regular usability testing. The process of actually designing a product will be briefly mentioned as it pertains to the specific steps of the development cycle to reinforce the concepts and how they can be adjusted to suit the needs of the specific project.

The last section of this project will be reviewing were to find additional information on specific concepts. The processes detailed in this discussion were derived from researching many different elements of design, interaction design, human factors, UX design, and user-testing. Many of the concepts I outline are worth delving into. I will try to tease out as many elements gleaned from other authors as possible, and document the best places to go for additional information on each subject.

# Development Cycle
Interaction Design generally follows a similar development cycle:

1. Gathering Requirements
2. Designing a Solution Addressing Requirements
3. Develop the Product
4. Testing

Testing is not simply the final stop here; it is the first part of the next cycle. Testing (step 4) will inform your approach to Gathering Requirements (step 1).

The strength of this model is its flexibility for many types of iterative development environments. This simplified model can be followed even if you have to tweak what exactly falls into each step.

Example: Adapting this model for development of a video game: 

Video Game Design, for example, can redefine its development cycle to address the needs of a large team and time for creating the actual assets. It has strict limitations on how much iteration can be feasible. Our basic outline for Interaction Design can be adapted for such an environment in a few different ways, one of which might look like this:

1. Concept Development/Gathering Requirements for build
2. Preproduction/Development
3. Nearing-complete builds completed for testing (i.e. Alpha and Beta builds)
4. Testing

This still follows our criteria, and can be iterated as many times as budget allows. On the first iteration, you would logically start at Concept Development, and after the first cycle, that step would become "Gathering Requirements" as you are integrating the information from testing.

## Step One: Gathering Requirements

1. What do I want to do for the user's experience on this iteration?
	* Your last iteration wasn't perfect. Is there anything appropriate that can be done to simplify or enhance the users' processes?
1. How can I measure if I have accomplished this?
	* Is the change I wanted to give the user measurable? Can we prove they are receiving what I am trying to give them?
	* Even though this is just step one, it's important to be mindful that once you reach testing phase, you need to have some way of seeing if you succeeded in your approach.
1. Do the proposed solutions sharpen or soften the learning curve of the product?
	* In many instances the learning curve is largely ignored, but it is one of the most essential elements of UI and Interaction Design.
	* Introducing the ability to do many different things end up making the product LESS usable. Different products appeal to different types of users, and some might need to have a high learning curve, but be aware of what the specific product requires, and if you are taking it beyond its intended level of accessibility.
	* For example, introducing "Protools" music recording applications into the next iPhone might lead to them marketing the iPhone as "a cell phone to make and share music" but the reality is that almost nobody will be able to use that level of complicated software. The iPhone is aware of its need to maintain its learning curve, and keeps its functionality accessible. Protools, on the other hand, is intentionally incredibly complicated, as it is catered to professionals and "power-users". This in general, is hard to reconcile with a product that is supposed to "simply work" like the iPhone. It would be almost useless, the target users of Protools do not need to be able to use it on their phone, and likewise, the users of the iPhone would be overwhelmed with that level of complexity on their phone. Cool features, and the hardware is all there, but the ability to know what is going on your own phone is a high priority. Managing complexity is still a huge concern for web design for mobile websites. The hardware can handle a lot, but too many features can make it overly complicated and inaccessible.

## Step Four: Importance of Regular Testing 

While accessibility for new users is incredibly important, depending on the application, you might need to cater to a larger demographic of "power-users" and retain users that are already very familiar with the processes. Often UX for "power-users" is overlooked in development (Karn, Perry, & Krolczyk, 1997 Testing for Power Usability: A CHI 97 Workshop SIGCHI Bulletin, 29(4)) User testing regularly can be very valuable even if you haven't made major changes or even prototyped a new iteration. Each time you test, you will get some amount of new data, and something like a user's level of previous experience with your product will influence their experience. In our model, a game, ideally a user that has played your game three times will want to play it three more times. Being able to capture a new potential user, and retain experienced users are both very important aspects to your UX.

During testing of your product there are several questions to keep in mind. While adaptability is key to any of the approaches discussed here, here are some questions for users that can generally be helpful in nailing down where their experience is, and what might need to be addressed.

1. When you were introduced to the product, what type of experience were you hoping to have?
1. How does your experience compared to what you expected to do with this product?
1. Is there anything that you felt slowed you down in your ability to use this product?
1. How would you sell this experience to a potential new adopter?

These are only a few boiler-plate examples to get your surveying focused on usability and user experience. Keeping the amount of questions to a minimum can help avoid fatiguing the tester and getting less usable data. This is all very adaptable to different types of products and UX goals, but in general, just getting descriptions like these from a user's perspective can end up being one of the more useful tools in approaching step one (Gathering Requirements). That is why it is imperative that this model be applied to ITERATIVE design. This isn't very useful if you aren't able to implement any of the changes in iteration.


---