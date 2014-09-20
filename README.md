## Instructions

- Form teams of 2-4 people
- Complete each challenge using [Ember's version of JSBin](http://emberjs.jsbin.com)
- [cdnjs](http://cdnjs.com/) is extremely useful for including external js libraries in a jsbin

## Challenges

1. #### [2 points] create a computed property that can be set

  modify [this](http://emberjs.jsbin.com/gepezu/1/edit) jsbin and implement the `fullDate` computed property
  
  Solutions:
    - http://emberjs.jsbin.com/qofuboquheme/1/edit
    - http://emberjs.jsbin.com/xumeb/1/edit

2. #### [3 points] Build an [Ember component](http://emberjs.com/guides/components/) that displays a github users' avatar and name given a github username

  example: 
  ```
  {{github-user username='wycats'}}
  ```
  would display Yehuda's github avatar and name.
  
  Solutions:
    - http://emberjs.jsbin.com/xoqag/3/edit

3. #### [4 points] create a live preview markdown editor

    create an ember application that creates a live preview of markdown entered into a textarea
    
   Solutions:
     - http://emberjs.jsbin.com/sexap/1/edit
     - http://emberjs.jsbin.com/cirev/1/edit

4. #### [5 points] Display a large list in a high performance manner
   - Ember can choke on rendering large lists
   - load this [dataset](https://data.cms.gov/developers/docs/hospitals-in-the-partnership-for-patients-hospital-engagement-networks-hens)
   - display the whole list in a way that renders quickly and has good scroll performance
   
   Solutions:
     - http://emberjs.jsbin.com/selepiziheyi/1/edit
     - http://emberjs.jsbin.com/qodulosoliwi/1/edit

5. #### [5 points] Create a simple API-based data viewer for Gratipay
   - display the paydays information in a table that can be sorted by clicking on the columns
   - Gratipay API endpoints: https://github.com/gratipay/gratipay.com#api
   - Bonus points [2 points]
     - persist the sorting when sending a link to the page to someone else
    
  Solution:
    - http://emberjs.jsbin.com/guquxu/1/edit
    
  Bonus Solution (using query params):
    - http://emberjs.jsbin.com/mipaha/1/edit
    
6. #### [7 points] Add keyboard shortcuts to navigate between routes
   - Add keyboard shortcuts to [this](http://emberjs.jsbin.com/tukuj/1/edit) example app
     - 'i' should transition to the index route
     - 'a' should transition to the about route
     - 'f' should transition to the favorites route
     
     Solutions:
        - http://emberjs.jsbin.com/litizezogagi/1/edit
        - http://emberjs.jsbin.com/relac/1/edit
  

