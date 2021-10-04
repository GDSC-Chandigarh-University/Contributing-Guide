Naming Conventions for element attributes and styles will be following:
* All the ID and CLASS NAMES should not include any capital letter.
* For styling the element use CLASS NAMES which are already defined in base.scss and try not to make your own CLASSES.
* Your overall code should be wrapped inside a DIV element with an ID attribute. Its ID attribute should speak for itself and the code you have done. For example: If you are         working on dashboard then your top DIV element ID should be dashboard
  ```
  <div id="dashboard">
     your code...
  </div>
  ```

* Don't directly style the HTML tags use CSS SELECTORS 

 ```
  <div id="dashboard">
    <h2>Dashboard</h2>
    <h3>Welcome Back!</h3>
  </div>
 ```

 ```
  #dashboard > h2 {
    font-size: 24px
  }
  #dashboard h2 + h3 {
    font-size: 14px
  }
 ```
