# STANDUP NOTES
## Daily Scrum

### Friday (October 8th, 2021)
1. What have you completed yesterday?
   
- Add CSS to Lab 2 Meeting Minutes
- Create some new issues and resolve them.

2. What will I do today?

- Ask tutor about these things:
  + Not sure how to go about the Pull Request section in the lab. Have already created the issue template and a new branch but unsure how to add new issues in this new branch, link and merge pull request. Please help me with 1 demo.
  + What is the difference between static position vs relative position?
  + How do I check if min-width makes any difference in my webpage?
- Adding new issues and merge pull requests for all of them
- Complete "CSS selectors" of the lab
- Double check the final repo and submit

3. Where do you get stuck?

- N/A
  
4. Comfort Level — How close are we to hitting our sprint goals?

- 100%. Finally finish everything after a lot of hours learning CSS + applying what I learned in this lab.

### Thursday (October 7th, 2021)
1. What have you completed yesterday?
  
- Continue creating issues for different tasks in lab 3.
- Learn how to use CSS

2. What will I do today?

- Add CSS to Lab 2 Meeting Minutes
- Create some new issues and resolve them.
 
3. Where do you get stuck?

- I am not stuck per se. I am just confused about different positions in CSS (static vs relative). 
- Also, how do I check if min-width makes any difference in my webpage?

4. Comfort Level — How close are we to hitting our sprint goals?

- 65%. I am done with "General CSS topics" of lab 3. Just have to complete "CSS selectors" and submit.

### Wednesday (October 6th, 2021)
1. What have you completed yesterday?

- Get started on lab 3
- Create a standup notes
- Create an issue template and labels in GitHub

2. What will I do today?

- Continue creating issues for different tasks in lab 3.
- Learn how to use CSS
- Add CSS to Lab 2 Meeting Minutes

3. Where do you get stuck?

- I wasn't sure how to create a pull request for each issue. 
- I have also accidentally pushing the issue template to the main branch and I don't know how to revert that.

4. Comfort Level — How close are we to hitting our sprint goals?
  
- 10%. I have only been able to set up and done the bare minimum. No where near complete. 
  
## Work Log

### Friday (October 8th, 2021)

+ [x] Class selector (.class)
+ [x] ID Selector (#id)
+ [x] Universal Selector (*)
+ [x] Element Selector (element) 
+ [x] Attribute Selector (e.g. [attribute=foo])
+ [x] Pseudo-class Selector (e.g. p:hover)
+ [x] Selector List (element, element)     
+ [x] Combinators (you must use one of each)
  + [x] Descendant Combinator (element element)
    ```css
    ol li {
      font-size: large;
    }
    ```

  + [x] Child Combinator (element > element)
    ```css
    .grid-container > div {
      font-family: 'Lora', serif;
      background-color: rgb(255, 204, 222);    /* sets opacity of black color */
      text-align: center;
      padding: 15px;
      color: navy;
      border: solid navy;
      border-width: 0.5mm;
      border-radius: 15px;
    }
    ```

  + [x] General sibling combinator (element ~ element)
    ```css
    p ~ div{
      font-size: 18px;
    } 
    ```

  + [x] Adjacent sibling combinator (element + element)
    ```css
    h1 + h2 {
      font-size: 3em;
      margin: 0px 200px 0px 470px;
    }
    ```

  + [x] Combining Two Selectors (element.class)
    ```css
    div.text{
      font-family: 'Lora', serif;
      color: black;
      font-weight: bold;
      margin-left: 10px;
      margin-right: 10px;
      text-align: center;
    }
    ```

### Thursday (October 7th, 2021)
+ [x] Comment
  + [x] Color
    + [x] rgb
    + [x] #FFF
    + [x] hsl(h, s, l)
    + [x] Color name
  + [x] Background
  + [x] Unit
    + [x] Use 3 unique relative units total (rem, em ch)
    + [x] Use 3 unique absolute units total (px, cm, mm)
  + [x] Box model
    + [x] Margin
      + [x] Long
      + [x] Short
      + [x] Auto
    + [x] Padding
      + [x] Long
      + [x] Short
    + [x] Borders
      + [x] border-style
      + [x] border-color
      + [x] border-width
      + [x] border-radius
  + [x] Text
    + [x] Color
    + [x] text-decoration
    + [x] text-align
  + [x] Display (none, block, inline-block, inline)
    + [x] At least 2 of them (block, inline)
  + [x] Sizing
    + [x] height
    + [x] width
    + [x] max-width
    + [x] min-width
  + [x] Layout
    + [x] Flexbox (align-items, justify-content, flex-direction)
    + [x] Grid
  + [x] Pseudo-class
  + [x] Responsiveness (screen, max-width)
  + [x] Position (static, relative)
  + [x] Font (Lora)

