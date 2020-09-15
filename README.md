# Dating Shouldn't Suck

## Overview

_**Dating Shouldn't Suck** is an app that helps singles add spice to their dating lives and avoid the monotonous dinner or drink at a bar. Dating Shouldn't Suck (DSS) is a full stack application where users have full CRUD capabilities to share their favorite date ideas along with personal reviews. Its the Yelp of Dating! Let's face it, dating in today's world is hard and overwhelming but it, here at DSS, we believe it doesn't have to suck!._


<br>

## MVP

_The **Dating Doesn't Suck** MVP will have a backend server built with Ruby on Rails exposing RESTful JSON endpoints. The server will include a database which consists of (3) tables, defined models, and full CRUD between non-user tables. In addition, the app will have a full CRUD functioning, interactive React front end. The front end will render data from back end APU and utilize client side routing through (8) components. Lastly, the front end will showcase impressive CSS styling, use of Flexbox, and responsive design on both desktop and mobile devices. The MVP will be delivered within the week timeframe alotted and deployed on Netlify (front end) and Heroku (back end).._

<br>

### Goals

- _Have a RESTful JSON API built on Ruby on Rails._
- _Build a database with at least 3 tables with defined models._
- _Full CRUD capability on both back end and front end._
- _Have an interactive React front end with (8) components._
- _Consume data from your Ruby on Rails API, and render that data in your components._
- _Utilize React Router, for client-side routing._
- _Front end polished with CSS that utilizes Flexbox._
- _Implemented on (2) media queries for responsive design on both mobile and desktop._

<br>

### Libraries and Dependencies

TBD

<br>

### Client (Front End)

#### Wireframes

![https://wireframe.cc/vIthRu](https://wireframe.cc/vIthRu)

- Desktop Landing

![https://wireframe.cc/UMcJui](https://wireframe.cc/UMcJui)

- Resource Show

![https://wireframe.cc/S94X41](https://wireframe.cc/S94X41)

- Resource Create

![https://wireframe.cc/zHNQ0H](https://wireframe.cc/zHNQ0H)

- Resource Update/Delete

![https://wireframe.cc/vIthRu](https://wireframe.cc/vIthRu)

- Tablet Resource Index

![https://wireframe.cc/jBSaVx](https://wireframe.cc/jBSaVx)

- Mobile Resource Index

#### Component Tree

> Use this section to display the structure of how your React components are being rendered. This should show the parent to child relation between you components. In other words, show which components are rendering the other components. 

#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
|__ services/

```

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   n   | _The header will contain the navigation and logo._               |
|  Navigation  | functional |   n   |   n   | _The navigation will provide a link to each of the pages._       |
|   Gallery    |   class    |   y   |   n   | _The gallery will render the posts using cards in flexbox._      |
| Gallery Card | functional |   n   |   y   | _The cards will render the post info via props._                 |
|    Footer    | functional |   n   |   n   | _The footer will show info about me and a link to my portfolio._ |

#### Time Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Add Contact Form    |    L     |     3 hrs      |     2 hrs     |    3 hrs    |
| Create CRUD Actions |    H     |     3 hrs      |     1 hrs     |     TBD     |
| TOTAL               |          |     6 hrs      |     3 hrs     |     TBD     |

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evaluate possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

### Server (Back End)

#### ERD Model

> Use this section to display an image of a computer generated ERD model. You can use draw.io, Lucidchart or another ERD tool.

![alt text](http://url/to/img.png)

<br>

***

## Post-MVP

- _Carousel of images on main page._
- _User Authentiation required for editing._
- _Map image accompanied of date idea._
- _Pop-up clickable buttons/images._
- _Tracking star rankings of total users for each date idea._
- _User first browse symbols for diff dating idea categories._

***

## Code Showcase

TBD

## Code Issues & Resolutions

TBD
