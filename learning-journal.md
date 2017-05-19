# Learning Journal for 401 Python

## 5/15/17
Happily back to the grind after 1 month off, 1 month as a TA, and another 2 weeks off. I really enjoyed the opportunity to be a TA, but by the end of it I was envious of the students - I wanted back into the classroom!

Today we got a quick intro to environments, and - if I understand correctly - an environment walls off what packages and variables your code has access to. With that in mind, it sounds like our assignments are supposed to be contained in environments, which should give us finer control. We also talked about more Python-specific features, like using dir to see a list of an object's attributes.

Every time another student asked a question in lecture, I'm finding that it was a question wouldn't have thought to ask and was glad to learn the answer.

## 5/16/17
Last night, I started the "How To Think Like a Computer Scientist" reading and found the concept of formal languages (as opposed to natural languages) really interesting. From the book: "Formal languages are languages that are designed by people for specific applications. For example, the notation that mathematicians use is a formal language that is particularly good at denoting relationships among numbers and symbols... Programming languages are formal languages that have been designed to express computations." Formal languages are supposed to be unambiguous and concise, and are likely to be dense.

Today's lecture was chock full of information. We got deeper into parameters than I'd been before - I hadn't heard of positional or keyword parameters, and I'm excited to see how we apply them. 'Namespace' is a term I'd heard but my understanding of it was vague. Today helped; as I understand it, it's where Python thinks something - a value, a function - is defined.

The second part of lecture was our introduction into TDD. It makes sense to build out tests before / concurrently with building functionality, but I'm guessing the art of writing good tests is a complex one! We'll find out in lab today.

## 5/17/17
Yesterday, we worked on functions that sum a series. My partner and I focused on iterator solutions first and turned our attention to recursion after our three iterative solutions passed tests. Castro shared his recursive solution for the fibonacci sequence, which was pretty different from my initial attempts. As I was watching the Clean Architecture video for today, Brandon Rhodes touched on what he considers a strength of functional programming: the simplicity and cleanliness allows him to visualize what the data looks like at every step. I need more exposure to recursion because I don't yet have that vision! But just five months ago, I was struggling to 'see' how a loop ran and we arrived at our iterative solution quickly - proof that it's very possible to learn that ability to visualize what a function/program is doing.

Lecture got a lot deeper into environments and packages, but it made sense and the structure was similar to how we used Node.js in 301. Reading and writing into files is newer for me, so I anticipate needing to do some research in that area. The work we do in the command line makes me realize how little I've really used my computer until now! We talked a lot about collection data types and all the super cool, clean Python methods specific to each.

Lab time today made me feel like I was back at Code Fellows for real. The 'how is half this work ever going to get done' feeling is back in full force! Anna and I spent a lot of time on our environment and package set up, which I think will pay off. I was able to clone the repo and install the dependencies without any problems, and we can easily run whatever we put in main from the terminal.

## 5/18/17
Today's lecture focused more on lists and dictionaries, including anonymous/lambda functions. We also got more in-depth about shallow and deep copying, which can be used to sort lists and dictionaries.

This was our second day in lab setting up our environments and packages, and building a package around our own module. Today we added tox, however, so that added a new level of complexity. We got to see the magic of tox in action when we ran a test on a function that converts our mailroom donor keys into a list - since we hard-coded the expected result, the test didn't pass because the outputted list in the Python2 environment was unpredictible.

Tomorrow we're going to do our Day of Code assignment, solving CodeWars katas and writing tests for them. I'm excited to practice writing tests because I need it!