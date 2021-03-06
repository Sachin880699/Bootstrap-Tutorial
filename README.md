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




________________________________________________________________________________
# Text Colors
________________________________________________________________________________
  
  
  # text color
  
  
  
  Example :
  
  
  
              <p class="text-muted">This text is muted.</p>
              <p class="text-primary">This text is important.</p>
              <p class="text-success">This text indicates success.</p>
              <p class="text-info">This text represents some information.</p>
              <p class="text-warning">This text represents a warning.</p>
              <p class="text-danger">This text represents danger.</p>
              <p class="text-secondary">Secondary text.</p>
              <p class="text-dark">This text is dark grey.</p>
              <p class="text-body">Default body color (often black).</p>
              <p class="text-light">This text is light grey (on white background).</p>
              <p class="text-white">This text is white (on white background).</p>


# background-color



Example :


                        <p class="bg-primary text-white">This text is important.</p>
                          <p class="bg-success text-white">This text indicates success.</p>
                          <p class="bg-info text-white">This text represents some information.</p>
                          <p class="bg-warning text-white">This text represents a warning.</p>
                          <p class="bg-danger text-white">This text represents danger.</p>
                          <p class="bg-secondary text-white">Secondary background color.</p>
                          <p class="bg-dark text-white">Dark grey background color.</p>
                          <p class="bg-light text-dark">Light grey background color.</p>
____________________________________________________________________________________________
# Tables 
____________________________________________________________________________________________


Example : 


                                                <table class="table">
                                                    <thead>
                                                      <tr>
                                                        <th>Firstname</th>
                                                        <th>Lastname</th>
                                                        <th>Email</th>
                                                      </tr>
                                                    </thead>
                                                    <tbody>
                                                      <tr>
                                                        <td>John</td>
                                                        <td>Doe</td>
                                                        <td>john@example.com</td>
                                                      </tr>
                                                      <tr>
                                                        <td>Mary</td>
                                                        <td>Moe</td>
                                                        <td>mary@example.com</td>
                                                      </tr>
                                                      <tr>
                                                        <td>July</td>
                                                        <td>Dooley</td>
                                                        <td>july@example.com</td>
                                                      </tr>
                                                    </tbody>
                                                  </table>


# Striped Rows

The .table-striped class adds zebra-stripes to a table



Example : 


                                    <table class="table table-striped">
                                        <thead>
                                          <tr>
                                            <th>Firstname</th>
                                            <th>Lastname</th>
                                            <th>Email</th>
                                          </tr>
                                        </thead>
                                        <tbody>
                                          <tr>
                                            <td>John</td>
                                            <td>Doe</td>
                                            <td>john@example.com</td>
                                          </tr>
                                          <tr>
                                            <td>Mary</td>
                                            <td>Moe</td>
                                            <td>mary@example.com</td>
                                          </tr>
                                          <tr>
                                            <td>July</td>
                                            <td>Dooley</td>
                                            <td>july@example.com</td>
                                          </tr>
                                        </tbody>
                                      </table>




# Table Borderd

class = .table-bordered

# Hover Rows

Class = table-hover

# Dark Table

class = table-dark

# Borderless Table

class = table-borderless

# Responsive Tables

table-responsive



________________________________________________________________________________________________
# Images
________________________________________________________________________________________________

# Rounded Corners
class = rounded

# Circle

class = rounded-circle

# Thumbnail

class = img-thumbnail

# Aligning Images

class = float-start
class = float-end

# Centered Image

class = mx-auto

# Responsive Images

class = img-fluid


_______________________________________________________________________________________
# Jumbotron
_______________________________________________________________________________________

A jumbotron was introduced in Bootstrap 3 as a big padded box for calling extra attention to some special content or information.



Example :



            <div class="mt-4 p-5 bg-primary text-white rounded">
              <h1>Jumbotron Example</h1>
              <p>Lorem ipsum...</p>
            </div>



_______________________________________________________________________________________
# Alerts
_______________________________________________________________________________________

# 1) Success

Example :

            <div class="alert alert-success">
                <strong>Success !</strong> Object successfully created .
            </div>


# Info

This alert box could indicate a neutral informative change or action.

Example :

            <div class="alert alert-info">
                <strong>Info !</strong> Info warning
            </div>

# Warning

This alert box could indicate a warning that might need attention.

Example :

            <div class="alert alert-warning">
                <strong>Warning !</strong> Warning
            </div>


# danger

This alert box could indicate a dangerous or potentially negative action

Example :

            <div class="alert alert-danger">
                <strong>Danger !</strong> Danger
            </div>

# Primary

Indicates an important action

Example :

            <div class="alert alert-primary">
                <strong>Primary !</strong> Primary
            </div>


_________________________________________________________________________________________________________
# button
_________________________________________________________________________________________________________

# Button Styles


            <button type="button" class="btn">Basic</button>
            <button type="button" class="btn btn-primary">Primary</button>
            <button type="button" class="btn btn-secondary">Secondary</button>
            <button type="button" class="btn btn-success">Success</button>
            <button type="button" class="btn btn-info">Info</button>
            <button type="button" class="btn btn-warning">Warning</button>
            <button type="button" class="btn btn-danger">Danger</button>
            <button type="button" class="btn btn-dark">Dark</button>
            <button type="button" class="btn btn-light">Light</button>
            <button type="button" class="btn btn-link">Link</button>

# Button Outline

            <button type="button" class="btn btn-outline-warning">Warning</button>
            <button type="button" class="btn btn-outline-danger">Danger</button>
            <button type="button" class="btn btn-outline-dark">Dark</button>
            <button type="button" class="btn btn-outline-light text-dark">Light</button>
            
            
# Button Sizes

Example : 

            <button type="button" class="btn btn-primary btn-lg">Large</button>
            <button type="button" class="btn btn-primary btn-md">Default</button>    
            <button type="button" class="btn btn-primary btn-sm">Small</button>
            

# Block Level Buttons

Example :

            <div class="d-grid">
              <button type="button" class="btn btn-primary btn-block">Full-Width Button</button>
            </div>


# Active/Disabled Buttons

Example : 

            <button type="button" class="btn btn-primary active">Active Primary</button>
            <button type="button" class="btn btn-primary" disabled>Disabled Primary</button>
            <a href="#" class="btn btn-primary disabled">Disabled Link</a>

# Spinner Buttons

Example : 


            <button class="btn btn-primary">
              <span class="spinner-border spinner-border-sm"></span>
            </button>

            <button class="btn btn-primary">
              <span class="spinner-border spinner-border-sm"></span>
              Loading..
            </button>

            <button class="btn btn-primary" disabled>
              <span class="spinner-border spinner-border-sm"></span>
              Loading..
            </button>

            <button class="btn btn-primary" disabled>
              <span class="spinner-grow spinner-grow-sm"></span>
              Loading..
            </button>

________________________________________________________________________________
# Button Groups
________________________________________________________________________________

# Button Groups

Example : 

            <div class="btn-group">
              <button type="button" class="btn btn-primary">Apple</button>
              <button type="button" class="btn btn-primary">Samsung</button>
              <button type="button" class="btn btn-primary">Sony</button>
            </div>
            
            

____________________________________________________________________________________


# bootstrap break 

                        <div class="w-100"></div>
                        
                        
_______________________________________________________________________________
_______________________________________________________________________________
# Padding class for different sies
_______________________________________________________________________________




# padding class for different Break points

                     

1 ) Extra Large   : .p-xl*
2 ) Large         : .p-lg-*
3 ) Medium        : pl-md-*
4 ) Small         : .p-sm-*
5 ) Extra Small   : 




Bootstrap Example : 


                        <div class="container">
                          <div class="row p-md-5">
                            <div class="col-md-4 pt-lg-5 pb-md-5 pink">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make </div>
                            <div class="col-md-4 pl-0 pr-5 green">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</div>
                          </div>
                        </div>

2 ) Style.css



                        .container{
                            border:5px solid black;
                        }
                        .row {
                            border 3px solid red;
                        }
                        .pink{
                            background: pink;
                        }
                        .orange{
                            background :orange;
                        }
                        .blue{
                            background:#007bff;
                        }
                        .green{
                            background:yellowgreen;
                        }


_______________________________________________________________________________________________________
# Horizontal Alignment

class  = .justify-content-end
class  = .justify-content-start
class  = .justify-content-center


also we can can do ti seprate for that

Ani yacha vapar alignment change karnyasathi hoto . hya class la apan row var lavto

class = .justify-content-between




________________________________________________________________________________________________________
# Vertical Alignment

<img src="https://i.stack.imgur.com/mOvi2.png" width="300" height="200"/>

class name = .align-items-start

alignment from buttom

class = .align-items-end

class = .align-items-center

class = .align-items-stretch

class = align-items-baseline



HTML :

                        <div class="container">
                          <div class="row align-items-center">
                            <div class="col-md-3 pink">
                              <h2> Col A</h2>
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
                            </div>
                            <div class="col-md-3 green">
                              <h2> Col B</h2>
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                            </div>
                             <div class="col-md-3 blue">
                              <h2> Col B</h2>
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                            </div>
                          </div>
                          
                          
CSS


                        .container{
                            border:5px solid black;
                        }
                        .row {
                            border:3px solid red;
                        }
                        .pink{
                            background: pink;
                        }
                        .orange{
                            background :orange;
                        }
                        .blue{
                            background:#007bff;
                        }
                        .green{
                            background: #8fd46a;
                        }



# Lign-temms for different break points


1 ) Extra Large       =  .align-items-xl-start
2 ) Large             =  .align-items-lg-start
3 ) Medium            =  .align-items-md-start
4 ) Small             =  .align-items-sm-start
5 ) Extra Small       =  no class for extra small



Example :




            <div class="container">
              <div class="row align-items-lg-center">
                <div class="col-md-3 pink">
                  <h2> Col A</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
                </div>
                <div class="col-md-3 green">
                  <h2> Col B</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                </div>
                 <div class="col-md-3 blue">
                  <h2> Col B</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                </div>
              </div>



_________________________________________________________________________________________
# Vertical Alignment Align-Content


<img src="https://user.oc-static.com/upload/2018/06/14/15289918266602_2.png" width="300" height="200"/>


use clas on row _______________________



1 ) class = align-content-start

Desc : Yane sagle box he top la yetil ani buttom la space rahil



2 ) class = align-content-end

Desc : Yane sagle box he buttom la yetil ani top la space rahil


3 ) class = align-content-center

Desc = Yane content box ahet te center la yetil hi tevach use hoil jeva apan row la hight use keiya

4 ) class = .align-content-between

Desc = Yane jo pan space ahe to middile la yeil


5 ) class = .align-content-around

Desc = Yane kay hoil pratek box madhe thodi thodi space yeil






HTML :


                        <div class="container">
                          <div class="row align-content-start" style="height:400px;">
                            <div class="col-md-3 pink">
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
                            </div>
                            <div class="col-md-7 green">
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                            </div>
                             <div class="col-md-5 blue">
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                            </div>
                            <div class="col-md-3 orange">
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                            </div>
                             <div class="col-md-4 blue">
                              Lorem Ipsum is simply dummy text of the printing and typesetting industry.  dummy text of the printing and typesetting industry
                            </div>
                          </div>
                        </div>


CSS :


            .container{
                border:5px solid black;
            }
            .row {
                border:3px solid red;
            }
            .pink{
                background: pink;
            }
            .orange{
                background :orange;
            }
            .blue{
                background:#007bff;
            }
            .green{
                background: #8fd46a;
            }



# Align-content classes for different Break Point


1 ) Extra Large  = .align-content-xl-start
2 ) Large        = .align-content-lg-start
3 ) Medium       = .align-content-md-start
4 ) small        = .align-content-sm-start





_______________________________________________________________________________________________
# Vertical Alignment Align-Self



<img src="https://sharkcoder.com/files/article/bootstrap_align-self.png" width="300" height="200"/>


Ya madhe phakta akach box la alignment deta yete

1 ) class    = .align-self-end
2 ) class    = .align-self-center
3 ) class    = .align-self-stretch
4 ) class    = .align-self-baseline

Desc : yane text line alignment karin

5 ) class    =  .align-self-auto

Desc = row ahe ani row var hight lavliya tar tar to box la bottom la karti


Ya madhe class la div var latop


Example :

                <div class="col-md-3 align-self-end green">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                </div>
                


HTML :


            <div class="container">
              <div class="row" style="height:300px;">
                <div class="col-md-3 align-self-start pink">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
                </div>
                <div class="col-md-3 align-self-center green">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                </div>
                <div class="col-md-5 align-self-end orange">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                </div>
              </div>
            </div>



CSS :

            .container{
                border:5px solid black;
            }
            .row {
                border:3px solid red;
            }
            .pink{
                background: pink;
            }
            .orange{
                background :orange;
            }
            .blue{
                background:#007bff;
            }
            .green{
                background: #8fd46a;
            }
            
            

____________________________________________________________________________________________

# Flex Direction classes

ya madhe box che direction apan change karu shaktoy

ani he class row var lavto


<img src="https://somospnt.com/images/flex-direction.png" width="300" height="200"/>

1 ) class = flex-row-reverse

Desc : ha horizantally work karin

2 ) class = .flex-column

Desc : ha vertically order ne yein

3 ) class = .flex-column-reverse

Desc : jar reverse ordern ne karaychi asel tar

4 ) class = .flex-nowrap

Desc  : jar aka box madhe pahije asel . mhaje next block khalchay linke la nako asel teva use karto

5 ) class = flex-wrap-reverse




Example :



            <div class="container">
              <div class="row flex-row-reverse">
                <div class="col pink">
                  <h2>Col A</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
                </div>
                <div class="col green">
                  <h2>Col B</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s
                </div>
                <div class="col flex-fill blue">
                  <h2>Col C</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                </div>
                <div class="col orange">
                  <h2>Col D</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                </div>

                <div class="col flex-fill cyan">
                  <h2>Col E</h2>
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. ever since the 1500s . dummy text of the printing and typesetting industry
                </div>
              </div>
            </div>





# Flext direction classes for different break points

1 ) Extra Large    : .flex-xl-row
2 ) Large          : .flex-lg-row
3 ) Medium         : .flex-md-row
4 ) Small          : .flex-sm-row
5 ) Extra Small    : 


_________________________________________________________________________________

# Display Utilities

1 ) display:none;          ------> .d-none
2 ) display:inline;        ------> .d-inline
3 ) display:inline-block   ------> .d-inline-block
4 ) display:block          ------> .d-block
5 ) display:table          ------> .d-table
6 ) display:table-cell     ------> .d-table-cell
7 ) display:table-row      ------> .d-table-row
8 ) display:flex;          ------> .d-flex
9 ) display:inline         ------> .d-inline-flex




# Display classes for diffrent break poin 
Yane diffrent size var block hide and show hoil

1 ) Extra Large        : .d-xl-none
2 ) Large              : .d-lg-none
3 ) Medium             : .d-md-none
4 ) Small              : .d-sm-none
5 ) Extra Small        : .d-none



