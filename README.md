# David Howe Portfolio
David Howe's Writing Portfolio and Blog

### Goal
To make a user-friendly React-App site to present David Howe as a writer both in a portfolio and blog site. This will be created using React.js as well as Ruby on Rails for the backend. The site must also include auth for David to be the only person to create new blog posts and be able to handle comments 

### Mock Flow Sketch

https://wireframepro.mockflow.com/view/Mdefaf76b8e74ae91fd17d0f027f0954a1600965861992#/page/6b3270029b054a9d8bb41d4236664c95


#### Component Breakdown


|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | class |   n   |   n   | _The header will contain the navigation and logo._               |
|  Navigation  | class |   n   |   n   | _The navigation will provide a link to each of the sections._       |
|  About    |   class    |   n   |   n   | _This section will render David's bio._      |
| Blog | functional |   y   |   y   | _This will showcase David's writings where he will be able to display them. David will also be able to delete blogs with his own auth account._                 |
| New Blog       | functional  |  n   |   n   | _This component will only be used by David to make a new post._ |
| Edit Blog | class  |   y   |  n   | _This component will only be used by David to edit or delete a post.._ |
| Contact     |  functional |  y |  n |  _This section will provide a way for the user to have further inquiry into David's writing or for possible hire._ |
|    Footer    | functional |   n   |   n   | _The footer will showcase David's socials and other links to his work._ |

#### Time Estimates

| Task                | Priority | Estimated Time | Rate | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :--: | :-----------: | :---------: |
| HTML Structure     |    M   |     2 hrs      |  |    |        |
| CSS Styling |    H     |     3 hrs      |         |     |    |
| Advanced CSS & Animation |    M     |   3 hrs       |    |      |        |    
| Dynamic (Javascript)     |    M     |    3 hrs      |     |      |        |
| Blog Mechanics (Backend)  |   H     |    5 hrs      |      |      |         |
| Authorization            |    H     |    4 hrs      |      |      |           |
| Contact Form             |    M     |    2 hrs      |     |       |             |
| TOTAL               |          |     22 hrs      |     |  |          |

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evaluate possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>


#### Change Log
