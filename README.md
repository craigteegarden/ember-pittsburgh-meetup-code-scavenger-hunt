## Instructions

- Form teams of 2-4 people
- Complete each challenge using [Ember's version of JSBin](http://emberjs.jsbin.com)
- [cdnjs](http://cdnjs.com/) is extremely useful for including external js libraries in a jsbin

## Challenges

1. #### [2 points] create a computed property that can be set

  - modify [this](http://emberjs.jsbin.com/gepezu/1/edit) jsbin and implement the `fullDate` computed property

1. #### [3 points] Build an [Ember component](http://emberjs.com/guides/components/) that displays a github users' avatar and name given a github username

  example: 
  ```
  {{github-user username='wycats'}}
  ```
  
  would display Yehuda's github avatar and name.

1. #### [4 points] create a live preview markdown editor

  - create an ember application that creates a live preview of markdown entered into a textarea

1. #### [5 points] Display a large list in a high performance manner

  - Ember can choke on rendering large lists
  - load this [dataset](https://data.cms.gov/developers/docs/hospitals-in-the-partnership-for-patients-hospital-engagement-networks-hens)
  - display the whole list in a way that renders quickly and has good scroll performance

1. #### [5 points] Create a simple API-based data viewer for Gratipay

  - display the paydays information in a table that can be sorted by clicking on the columns
  - Gratipay API endpoints: https://github.com/gratipay/gratipay.com#api
  
  Bonus points [2 points]
  
    - persist the sorting when sending a link to the page to someone else
    
1. #### [7 points] Add keyboard shortcuts to navigate between routes

  - Add keyboard shortcuts to [this](http://emberjs.jsbin.com/tukuj/1/edit) example app
    - 'i' should transition to the index route
    - 'a' should transition to the about route
    - 'f' should transition to the favorites route
  

