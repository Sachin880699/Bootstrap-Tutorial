# Bootstrap-Tutorial



# Container


1 ) The .container class provides a responsive fixed width container
2 ) The .container-fluid class provides a full width container, spanning the entire width of the viewport



# Fixed Container

Use the .container class to create a responsive, fixed-width container.

Example :

            <div class="container">
              <h1>My First Bootstrap Page</h1>
              <p>This is some text.</p>
            </div>
            
# Fluid Container

Use the .container-fluid class to create a full width container, that will always span the entire width of the screen 

Example : 

          <div class="container-fluid">
            <h1>My First Bootstrap Page</h1>
            <p>This is some text.</p>
          </div>
          
          
# Container Padding

By default, containers have left and right padding, with no top or bottom padding. Therefore, we often use spacing utilities,
such as extra padding and margins to make them look even better. For example, .pt-5 means "add a large top padding":


Example :

            <div class="container pt-5">
            
            </div>
            

# Container Border and Color


Other utilities, such as borders and colors, are also often used together with containers:



Example :

            <div class="container p-5 my-5 border"></div>

            <div class="container p-5 my-5 bg-dark text-white"></div>

            <div class="container p-5 my-5 bg-primary text-white"></div>
            



# Responsive Containers




Example :

        <div class="container-sm">.container-sm</div>
        <div class="container-md">.container-md</div>
        <div class="container-lg">.container-lg</div>
        <div class="container-xl">.container-xl</div>
        <div class="container-xxl">.container-xxl</div>
        
        

______________________________________________________________________________________________
# Grid Basic
______________________________________________________________________________________________
Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.


# Grid Classes


1 ) .col- (extra small devices - screen width less than 576px)
2 ) .col-sm- (small devices - screen width equal to or greater than 576px)
3 ) .col-md- (medium devices - screen width equal to or greater than 768px)
4 ) .col-lg- (large devices - screen width equal to or greater than 992px)
5 ) .col-xl- (xlarge devices - screen width equal to or greater than 1200px)
6 ) .col-xxl- (xxlarge devices - screen width equal to or greater than 1400px)




# Basic col

Example : 


        <div class="row">
          <div class="col">.col</div>
          <div class="col">.col</div>
          <div class="col">.col</div>
        </div>




# Responsive Columns

On mobile phones or screens that are less than 576px wide, the columns will automatically stack on top of each other:


Example : 

                <div class="row">
                  <div class="col-sm-3">.col-sm-3</div>
                  <div class="col-sm-3">.col-sm-3</div>
                  <div class="col-sm-3">.col-sm-3</div>
                  <div class="col-sm-3">.col-sm-3</div>
                </div>





# Two Unequal Responsive Columns

how to get two various-width columns starting at tablets and scaling to large extra desktops


Example : 



          <div class="container">
              <div class="row">
                  <div class="col-sm-4">First Col</div>
                  <div class="col-sm-8">Second Col</div>
              </div>
          </div>




____________________________________________________________________________________
# Text/Typography
____________________________________________________________________________________

Heading Tag 

example :


            <p class="h1">h1 Bootstrap heading</p>
            <p class="h2">h2 Bootstrap heading</p>
            <p class="h3">h3 Bootstrap heading</p>
            <p class="h4">h4 Bootstrap heading</p>
            <p class="h5">h5 Bootstrap heading</p>
            <p class="h6">h6 Bootstrap heading</p>
            
            
# Display Headings



Example : 


              <div class="container mt-3">
                <h1 class="display-1">Display 1</h1>
                <h1 class="display-2">Display 2</h1>
                <h1 class="display-3">Display 3</h1>
                <h1 class="display-4">Display 4</h1>
                <h1 class="display-5">Display 5</h1>
                <h1 class="display-6">Display 6</h1>
              </div>


# small

Example : 



            <h2>h2 Heading <small>Second Text</small></h2>

  
  



