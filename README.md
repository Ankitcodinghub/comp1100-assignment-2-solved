# comp1100-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COMP1100 Assignment 2 Solved](https://www.ankitcodinghub.com/product/comp1100-in-this-assignment-you-will-write-code-to-explore-a-way-in-which-programming-can-be-used-to-model-long-term-environmental-impacts-you-will-make-a-crude-model-of-the-impact-an-agricultural/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109290&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP1100 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this assignment, you will write code to explore a way in which programming can be used to model long term environmental impacts. You will make a crude model of the impact an agricultural process might have on its environment.As our global population increases, the demand for food and agricultural products increases commensurately. This results in increased pressure on said agricultural production systems.

In this assignment, you will be producing a basic model of the degradation of a paddock in a farm.

{:.msg-info} This assignment is worth 12% of your final grade.

Required Knowledge

Students who have worked up to the Week 6 lab should have the programming knowledge required for this assignment; in particular you will need to work with recursion and parametric polymorphism. The Week 7 lab will help you improve your unit test and style marks. You do not need any knowledge or understanding of degradation modelling beyond what we give you in this document to complete this assignment.

Getting Started

1. Fork the assignment repository and create a project for it in VSCodium, following the same steps as in Lab 2. The assignment repository is at https://gitlab.cecs.anu.edu.au/comp1100/2022s2/2022s2StudentFiles/assignment2.

2. Add our version of the repository as a remote called upstream. This allows us to provide additional fixes in the unlikely case that they are required. You do this by doing the following:

3. Go to the command palette in VSCode (or VSCodium) by pressing Ctrl + Shift + p

4. Type git remote

5. Click Git: Add Remote

6. Enter upstream into the box for the remote name 7. Put the following URL as the remote url: https://gitlab.cecs.anu.edu.au/comp1100/2022s2/2022s2StudentFiles/assignment2.git.

Overview of Tasks

This assignment is marked out of 100

| Task | COMP1100 | |——————————————|————–| | Task 1: Types and Helper Functions | 25 | | Task 2: Implementing Farm World | 35 | | Unit Tests | 10 | | Style | 10 | | Technical Report | 20 |

Overview of the Repository

Most of your code will be written in src/Farm.hs, and a little in src/TestPatterns.hs. You will also need to implement tests in src/FarmTest.hs, which contains some example tests for you to study.

Other Files

src/TestPatterns.hs contains some test patterns for FarmWorld. There is one piece missing for you to fill in, and an opportunity for you to create your own if you wish.

src/Testing.hs is the testing library we used in Assignment 1. You should read this file as well as src/FarmTest.hs, and make sure you understand how to write tests.

src/GridRenderer.hs contains code to render a grid of cells (in this case, a farm) to the screen, and to convert a point on the screen back into a grid coordinate. You are not required to understand it, but it is commented for interested students to read.

src/App.hs contains the bulk of a small CodeWorld test program that uses your FarmWorld code. We discuss its features in “Overview of the Test Program”. app/Main.hs launches the test application. test/Main.hs is a small program that runs the tests in src/FarmTest.hs.

comp1100-assignment2.cabal tells the cabal build tool how to build your assignment. You are not required to understand this file, and we will discuss how to use cabal below.

Setup.hs tells cabal that this is a normal package with no unusual build steps. Some complex packages (that we won’t see in this course) need to put more complex code here. You are not required to understand it.

Overview of Cabal

As before, we are using the cabal tool to build the assignment code. The commands provided are very similar to last time:

cabal v2-build: Compile your assignment. cabal v2-run farmworld: Build your assignment (if necessary), and run the test program. cabal v2-repl comp1100-assignment2: Run the GHCi interpreter over your project.

cabal v2-test: Build and run the tests. This assignment is set up to run a unit test suite like in Assignment 1, but this time you will be writing the tests. The unit tests will abort on the first failure, or the first call to a function that is undefined.

{:.msg-info} You should execute these cabal commands in the top-level directory of your project: ~/comp1100/assignment2 (i.e., the directory you are in when you launch a terminal from VSCodium).

Overview of FarmWorld

FarmWorld is a simulator made up of a grid of paddocks designed to model the development and change in quality of a farm over time. The simulation will proceed in a series of discrete time intervals representing the passing of years. Each year, a rule will be applied over each of the Paddocks in the Farm, which, depending on the neighbouring paddocks, will update the yield (value for that year) and degradation rate of that paddock in the next year.

In this assignment, you will create and use this simulation, to visualise how the state of the farm changes over time, to calculate the net predicted value (NPV) of the farm over a given number of years.

Overview of the Test Program

The test program in app/Main.hs uses CodeWorld, just like Assignment 1, and responds to the following keys:

| Key | Effect | |————–|————————————————-| | 1 | Reset the simulation to the first test pattern | | 2 | Reset the simulation to the second test pattern | | 3 | Reset the simulation to the third test pattern | | 4 | Reset the simulation to your (optional) test pattern | | . | Step the simulation forward one year | | D | Toggle display of the values of each cell and the NPV up to the given year | | + | Increase the year up to which the NPV will be calculated | | – | Decrease the year up to which the NPV will be calculated |

You can also click on cells with the mouse to change them, if you want to play around with different patterns.

“Exception in blank-canvas application:” Prelude.undefined

If this happens, refresh the browser to continue.

Getting started with FarmWorld Data types

A Farm is made up of different cells, called Paddocks. A Paddock has a Crop and two Doubles which represent the yield (value) and degradation rate, respectively, at a given time.

The initial values of the yield and the degradation rate are determined by the Crop.

These initial values are given in the table below:

| Crop | Expected Production capacity (yield) (AUD) | Expected Degradation Rate | |————|—————————————|—————————-| | Livestock | 500 | 3% | | Wheat | 1000 | 10% | | Conservation | 0 | -10% | | Intercropping | 750 | 5% |

In the first year of a Paddock of Livestock, we can expect it to generate $500 in revenue, but that by the next year it will degrade to generate 3% less revenue (note that the amount it will degrade in future years will depend also on its neighbours.)

A Paddock of Conservation, on the other hand, will never generate any income, but will reduce the rate of degradation of its neighbours.

Both the yield and degradation rate of a Paddock will change each year, depending on its own degradation rate and the degradation rates of its neighbours — the Paddocks to its immediately North, South, East and West.

More specifically, the degradation rate at year $$t$$, $$d_t$$ is defined to be $$displaystyle d_t = rac{d_{t-1} + sigma( ext{neighbours}(d_{t-1}))}{2}$$ where $$sigma$$ takes the average degradation rate.

and we can calculate the yield at time $$t$$ to be $$y_t = y_{t-1}(1-d_{t-1})$$.

{:.msg-info} In real life, land degradation involves many more complex factors and this simulation is far from realistic. For example, consider what the simulation will predict after 100 years of a single Livestock paddocks surrounded by Conservation paddocks! Attempting to accurately predict and model the effects of different maintenance and usage systems in agriculture is challenging, but increasingly important. For more information if you find this interesting, you can see resources from: NSW Department of Planning and Environment, Sustainable Agriculture and Sustainable Food Systems. Test Patterns

The Test Patterns given in this assignment will allow you to observe some of the variety of behaviour that the FarmWorld simulator can display.

The next test pattern, monoculture, is a 4 by 4 monoculture of wheat. Our simulator will show its yield decay rapidly.

The third test pattern, stableMix is a mix of crops which should eventually reach an equilibrium where the decay in value of each of the crops will eventually reach zero, and so the yield will remain the same from there on in.

You can use this to test your code after you have finished all tasks (although, you can do this without renderPaddock).

If your result is very similar but not exactly the same to what is given here, that does not necessarily mean it is wrong.

Task 1: Types and Helper Functions (25 Marks)

Before we can begin implementing the rules for our farm model, we need to set up a few things:

1. A data type to represent each sort of crop;

2. Helper functions over paddocks; and

3. Helper functions for our Farm data type.

The assignment framework will use these functions to render entire grids of paddocks to CodeWorld Pictures.

Your Tasks

In src/Farm.hs, fill out the data type Crop that represents what is being produced in the paddocks in FarmWorld. Defining our own type to talk about crops lets us be precise when we code; knowing that there is a fixed number of possibilities reduces bugs.

In src/TestPatterns.hs, there are test patterns for FarmWorld, expressed as Strings. The parseGrid function parses these strings into values of type Farm, which are made available to the rest of the program. (Parsing is the process of analysing unstructured data — usually strings or binary data — and converting it into a more structured form.)

parseFarm relies on a helper function to parse individual characters into Paddocks. For FarmWorld, the helper is toCrop :: Char -&gt; Crop, which you need to implement according to the following rule:

A ‘c’ character represents a Livestock crop.

A ‘w’ character represents a Wheat crop.

A ‘i’ character represents an Intercropping crop.

Any other character represents a Conservation crop.

We provide a test program that uses CodeWorld to draw the cells to the screen, and allows you to edit the grid by clicking on it. It relies on some helper functions in src/Farm.hs, which you need to implement:

In order to turn the Crop found by toCrop into a Paddock that can form part of the Farm in the test pattern, in src/Farm.hs, you must also fill in the helper function allocatePaddock :: Crop -&gt; Paddock. This function should set the initial expected annual yield and degradation rate as shown in the table above.

The test program allows the user to change paddocks by clicking on them. As well as allocatePaddock, this relies on cycleCrop :: Crop -&gt; Crop, which returns what the paddock should be after it is clicked. This function needs to return the “next” type of allocated production system, similar to nextColour from Assignment 1. Cycle through the Crops in the order they appear in the table.

The test program knows how to draw a Farm of paddocks, provided that it can be told how to draw a single paddock from the farm. It uses renderPaddock :: Paddock -&gt; Picture to do this, which needs to behave according to the following rules:

Each paddock should be a solid 1 by 1 rectangle, centred at the origin (i.e., not translated).

Paddocks containing different crops should have different colours and be easily distinguishable; no paddock should be black or white by default.

The colour of a non-Conservation paddock should fade as the yield approaches zero, and brighten as it approaches infinity.

The test program requires two more helpers in src/Farm.hs that deal with the grid as a whole. You might also find them useful in Task 2:

get :: Location -&gt; Farm -&gt; Maybe Paddock

The test program uses get when it responds to mouse clicks, to pick out the cell that the user is changing.

get (Lot col row) farm shall return Just the Paddock in farm at column col and row row, if it exists. If no such lot exists (i.e., col or row are outside the bounds of the Farm), it shall return Nothing.

col will be a character between ‘a’ and ‘z’ representing columns from left to right. row will count from 0. That is, Lot ‘a’ 0 is the topleft corner of the grid. In a 5 by 5 farm, Lot ‘e’ 4 would be the opposite corner.

The paddocks in a Farm are stored as a single list, in what we call row-major order. This means that the list contains every cell in row 0, then every cell in row 1, then every cell in row 2, and so on… An example of the order is given in the below:

allLocations :: Int -&gt; Int -&gt; [Location]

allLocations width height shall return a list of every possible Location in a grid of that width and height, in row-major order. It is important that you emit Locations in this order, as the assignment skeleton assumes that the list of Paddocks in a Farm is stored in the same order. The renderer in the test program uses allLocations to decide where to place the Picture of each paddock in the farm.

Both width and height must be positive integers to return a sensible result. Raise an error if either are zero or negative.

Example: allLocations 3 2 shall return [Lot ‘a’ 0, Lot ‘b’ 0, Lot ‘c’ 0, Lot ‘a’ 1, Lot ‘b’ 1, Lot ‘c’ 1].

Hints

The function (!!) :: [a] -&gt; Int -&gt; a can return the nth element of a list:

Example: [‘a’, ‘b’, ‘c’] !! 2 returns ‘c’.

Example: [] !! 0 throws an error, as the index is beyond the length of the list.

You don’t want to use this function often (because of the risk of errors), but it is a handy tool here.

Task 2: Running FarmWorld 35 Marks

We can now render the farm grids in CodeWorld. The next step is to make them update according to our degradation model, and to find the farm’s value over time.

Your Task

Define the following two functions in src/Farm.hs:

updateFarm :: Farm -&gt; Farm generates the next year of Farm World according to the rules described above

predictIncome :: Int -&gt; Farm -&gt; Double returns the predicted total income from the entire Farm the given number of years. Over zero years, the income would be zero. If a negative number of years is given, predictValue cannot give any reasonable output and so should return an error.

Money in the future is less useful than money now, and we take this into account by reducing the value of future income at a fixed rate ( $$7%$$ ) each year. So, for the purpose of this function, the value of the farm $$f$$ in 5 years time will be $$0.93^5 imes v($$updateFarm$$_{5 ext{ times}}(f))$$. where $$v$$ takes the sum of the yields of each of the Paddocks in the Farm.

This is very similar to the definition of the NPV given here.

Hints

Remember, the formulae are

$$displaystyle d_t = rac{d_{t-1} + sigma( ext{neighbours}(d_{t-1}))}{2}$$, where $$sigma$$ denotes the mean degradation rate of neighbours, and

$$y_t = y_{t-1}(1-d_{t-1})$$

Break the problem down into sub-problems (separate functions), and test each in isolation. If you find a function does not do what you expect, you will have smaller units of code to debug. This is easier to get your head around.

Here are some questions you might need to ask when formulating a solution; some of them could be turned into helper functions:

Given a Location for a paddock on a farm, what is its neighbourhood (the four paddocks around that coordinate: one step North, South, East, and West)? Note that corner lots have only two neighbours, edge lots have three.

Style Note: You can split complex expressions over multiple lines, for readability:

“`haskell — This calculation is pointless but long. — Instead of writing it out like this: fiveFactorials = [1, 1 * 2, 1 * 2 * 3, 1 * 2 * 3 * 4, 1 * 2 * 3 * 3 * 5]

— Why not write it out like this? fiveFactorials = [ 1 , 1 * 2 , 1 * 2 * 3 , 1 * 2 * 3 * 4 , 1 * 2 * 3 * 3 * 5 ]

— P.S.: Did you notice the bug? — It’s easier to see in the second example, isn’t it? “`

Given a neighbourhood, how can we find the neighbourhoods average degradation rate?

Given a paddock and its neighbourhood, what will the degradation rate of the paddock look like in the new year?

Do the helper functions from Task 1 solve any of your sub-problems?

The list of cells within a Farm is in row-major order. The list of coordinates returned by allLocations is in row-major order. Can you do anything useful by using both simultaneously?

Unit Tests (10 Marks)

How do you know that the program you’ve written is correct? GHC’s type checker rejects a lot of invalid programs, but you’ve written enough Haskell by now to see that a program that compiles is not necessarily correct. Testing picks up where the type system leaves off, and gives you confidence that changing one part of a program doesn’t break others. You have written simple doctests in your labs, but larger programs need more tests, so the tests you will write for this assignment will be labelled and organised in a separate file from the code.

Open src/FarmTest.hs. This file contains a couple of example test cases, written using a simple test framework defined in src/Testing.hs. These files are heavily commented for your convenience.

You can run the tests by executing cabal v2-test. If it succeeds it won’t print out every test that ran, but if it fails you will see the output of the test run. If you want to see the tests every time, use cabal v2-test –test-show-details=streaming instead.

Your Task

Replace the example tests with tests of your own. The tests that you write should show that the Haskell code you’ve written in Tasks 1-3 is working correctly.

Hints

General Hints

Try writing tests before you write code. Then work on your code until the tests pass. Then define some more tests and repeat. This technique is called test-driven development.

The expected values in your test cases should be easy to check by hand. If the tested code comes up with a different answer, then it’s clear that the problem is with the tested code and not the test case.

Sometimes it is difficult to check an entire structure that’s returned from one of your functions. Maybe you can compute some feature about your result that’s easier to test?

If you find yourself checking something in GHCi (i.e., cabal v2-repl comp1100-assignment2), ask yourself “should I make this into a unit test?”. The answer is often “yes”.

If you are finding it difficult to come up with sensible tests, it is possible that your functions are doing too many things at once. Try breaking them apart into smaller functions and writing tests for each.

Technical Hints

The assertEqual and assertNotEqual functions will not work on the CodeWorld Picture type (it has no Eq instance). Therefore, it is not possible to write tests for renderQR.

For anything involving Doubles, you should use the assertApproxEqual function; as shown in the example failure test, Doubles don’t always behave as expected.

If you want to write tests about new types you have defined, add deriving (Eq, Show) to the end of the type definition, like this:

data MyType = A | B | C deriving (Eq, Show)

It is not possible to test for a call to error using the tools provided in this course.

Style (10 Marks)

“[…] programs must be written for people to read, and only incidentally for machines to execute.”

From the foreword to the first edition of Structure and Interpretation of Computer Programs.

Programming is a brain-stretching activity, and you want to make it as easy on yourself as possible. Part of that is making sure your code is easy to read, because that frees up more of your brain to focus on the harder parts.

Guidance on good Haskell style can be found in this course’s Style Guide, and in lecture notes.

Your Task

Ensure that your code is written in good Haskell style.

Technical Report (20 Marks)

You are to write a concise technical report about your assignment.

The maximum word count is 1250 . This is a limit, not a quota; concise presentation is a virtue.

{:.msg-warn} Once again: These are not required word counts. They are the maximum number of words that your marker will read. If you can do it in fewer words without compromising the presentation, please do so. You will not lose marks for having fewer than 1250 words.

The report must have a title page with the following items:

Your name

Content and Structure

Introduction

If you wish to do so you can write an introduction. In it, give:

A brief overview of your program: how it works; and what it is designed to do.

This section is particularly relevant to more complicated programs. Content

Talk about why you structured the program the way you did. Below are some questions you could answer:

Program design

Describe what each relevant function does conceptually. (i.e. how does it get you closer to solving the problems outlined in this assignment spec?)

How do these functions piece together to make the finished program? Why did you design and implement it this way?

What major design choices did you make regarding the functions that youâ€™ve written and the overall structure of your program?

Assumptions

Describe assumptions you have made about how a user might use the program and how this has influenced your design decisions.

How did you test individual functions?

Describe the tests that prove individual functions on their own behave as expected (i.e. testing a function with different inputs and doing a calculation by hand to check that the outputs are correct).

How did you test the entire program? What tests did you perform to show that the program behaves as expected in all (even unusual) cases?

Inspiration / external content

What resources did you use when writing your program (e.g., published algorithms)?

If you have used resources such as a web-page describing an algorithm, be sure to cite it properly at the end of your report in a â€˜Referencesâ€™ section. References do not count to the maximum word limit.

Reflection

Discuss the reasoning behind your decisions, rather than what the decisions were. You can reflect on not only the decisions you made, but the process through which you developed the final program:

Did you encounter any conceptual or technical issues?

If you solved them, describe the relevant details of what happened and how you overcame them.

Sometimes limitations on time or technical skills can limit how much of the assignment can be completed. If you ran into a problem that you could not solve, then your report is the perfect place to describe them. Try to include details such as:

theories as to what caused the problem; suggestions of things that might have fixed it; and discussion about what you did try, and the results of these attempts.

This is a great way to gain marks to make up for a not completely successful programming experience!

What would you have done differently if you were to do it again

What changes to the design and structure you would make if you wrote the program again from scratch?

Are parts of the program confusing for the reader? You can explain them in the report (in this situation you should also make use of comments in your code).

If you collaborated with others, what was the nature of the collaboration? (Note that you are only allowed to collaborate by discussing concepts, not sharing solutions.)

Collaborating is any discussion or work done together on planning or writing your assignment.

Other info

{:.msg-info} This is a list of suggestions, not requirements. You should only discuss items from this list if you have something interesting to write.

Things to avoid in a technical report

Line by line explanations of large portions of code. (If you want to include a specific line of code, be sure to format as described in the “Format” section below.)

Pictures of code or your IDE.

Content that is not your own, unless cited.

Grammatical errors or misspellings. Proof-read it before submission.

Informal language – a technical report is a professional document, and as such should avoid things such as:

Unnecessary abbreviations (atm, wrt, ps, and so on), emojis, and emoticons; and

Stories / recounts of events not relevant to the development of the program.

Irrelevant diagrams, graphs, and charts. Unnecessary elements will distract from the important content. Keep it succinct and focused.

If you need additional help with report writing, ANU Academic Skills have resources to help.

Format

You are not required to follow any specific style guide (such as APA or Harvard). However, here are some tips which will make your report more pleasant to read, and make more sense to someone with a computer science background.

Colours should be kept minimal. If you need to use colour, make sure it is absolutely necessary.

If you are using graphics, make sure they are vector graphics (that stay sharp even as the reader zooms in on them).

Any code, including type/function/module names or file names, that appears in your document should have a mono-spaced font (such as Consolas, Courier New, Lucida Console, or Monaco)

Other text should be set in serif fonts (popular choices are Times, Palatino, Sabon, Minion, or Caslon). When available, automatic ligatures should be activated.

Do not use underscore to highlight your text.

Text should be at least 1.5 spaced.

Communicating

Sharing concepts and sketches is perfectly fine, but sharing should stop before you risk handing in suspiciously similar solutions.

Course staff will not look at assignment code unless it is posted privately in piazza, or shared in a drop-in consultation.

Course staff will typically give assistance by asking questions, directing you to relevant exercises from the labs, or definitions and examples from the lectures.

Submission Checklist

You have fully read and understand the entire assignment specification.

Your work has been pushed to GitLab. You can confirm that the latest version of your code has been pushed to GitLab by using your browser to visit https://gitlab.cecs.anu.edu.au/uXXXXXXX/assignment2, where XXXXXXX is your student number.

Your program compiles and runs, including the cabal v2-test test suite.

You have proof-read and spell-checked your report.

Related courses

ENVS2023 – Sustainable Agricultural Systems

ENVS2024 – Agricultural Systems

ENVS3024 – Agricultural Innovation

ENGN3410 – Engineering Sustainable Systems

ENVS1008 – Sustainable development
