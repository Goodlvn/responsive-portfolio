# responsive-portfolio

This [project](https://goodlvn.github.io/responsive-portfolio/) was all about Bootstrap! My oh my what a beautiful resource! It makes generating styling for a website more effecient and uniform. To go deeper though, we created a portfolio page using bootstrap in this project. We were tasked with creating a home page -index.html- a portfolio page and a contact page. We had to create the html elements from scratch but were able to use the Bootstrap framework for styling and layout



## Technolgies Used

1. HTML - used to create the elements of a website
2. CSS - used to style the contents of a website 
3. Bootstrap - css framework used for more efficient layout and styling

## Challanges/Thoughts

Although Bootstrap is a powerful tool I felt limited when it came to customized margin layouts for specific elements. The boot strap padding and margin incriments have 5 levels so using padding and margin to move an element exaclty where you wanted was tough. I also thought that it would be great if Bootstrap had more functionality with colors/baclground colors in respect to media queries. I know most of my challenges are coming from a lack of experience with the frame work itself. That being said I really appreciated how easy it is to create responsive elements in Bootstrap. I really appreciated the gird system and the built in break points! They were a life saver and left the website feeling smooth.

In my attempt to complete the assignment I tried to remove as many of the divs that I could and replacing them with more semantic tags like 

## Most satisfying code to complete
```
<div class="row w-100 m-0">
      <div class="col-xs-1 col-md-1 col-xl-2 none"></div>

        <div class="col-md-10 col-xl-8 pl-5 pr-5 mbl">
            <div class="container bg-white mt-sm-4 mt-lg-5 ">
                <h1 class="p-3 m-0 pt-3 text-info">About Me</h1>
                <div class="container border-top border-secondary thiccBorder pt-4 p-3 pb-sm-3 pb-md-5">
                    <img class="float-left p-3 mbl" src="assets/images/aboutme.jpg" width="200" alt="placeholder image of myself">
                    <p>Hi! My name is Jonathan David Lopez Martinez but please call me JD! I am an aspiring front end web developer and digital marketer. I have been in the aquatics industry for the last 5 years where I have honed my communication and leadership skills. I am excited to dive into the next chapter of my life and career. Although I am in the process of gaining more work experience you can rest assured that I am here to listen to what your needs as a client are. My attention to detail along with good communication skills will ensure an outcome that we will both be proud of.</p>
                    <p class="pb-5 pb-sm-4">A little bit about me: I am the oldest of five! I grew up all over the bay area and feel most at home in the pennisula and south bay! I love playing underwater hockey (our team got second place at nationals 2019 and am currrently training to join the mens international team) I also love playing magic the gathering (specifically in the commander format)</p>
                </div>
            </div>
        </div>

        <div class="col-sm-1 col-md-1 col-xl-2 none"></div>
    </div>
```

## Personal best use of grid system

```
<div class="row w-100 m-0">
        <div class="col-xs-1 col-md-1 col-xl-2 none"></div>
  
          <div class="col-md-10 col-xl-8 pl-5 pr-5 mbl mb-5">
              <div class="container bg-white mt-sm-4 mt-lg-5 ">
                  <h1 class="p-3 m-0 pt-3 text-info">Portfolio</h1>
                  <div class="container border-top border-secondary thiccBorder pt-4 p-3 pb-sm-3 pb-md-5">

                    <div class="row mb-4">
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                        <div class="col-xs-12 col-md-6 col-lg-4">
                            <img class="p-3 img-fluid mx-auto d-block" src="https://via.placeholder.com/350" alt="placeholder image">
                        </div>
                    </div>
                  </div>
              </div>
          </div>
          <div class="col-sm-1 col-md-1 col-xl-2 none"></div>
      </div>
```



## Order of workflow:

1. Create the index page to be fully responsive 
2. Use index.html as a base to create portfolio.html then contact.html 
3. Fill in with personal information :3

## Resources 

[Showed me how to float my navbar items to the right](https://stackoverflow.com/questions/41513463/bootstrap-4-align-navbar-items-to-the-right)

[Gave me a new perspective for my borders](https://stackoverflow.com/questions/48506610/bootstrap-4-border-utilities)

[Found ClearFix!! and how to implement it](https://mdbootstrap.com/docs/jquery/navigation/footer/)

[Gave me the base/idea for my footer](https://goodlvn.github.io/responsive-portfolio/)

[Showed me a way to get a sticky footer - I ended up coding it differently](https://stackoverflow.com/questions/40853952/bootstrap-footer-at-the-bottom-of-the-page/40854221 )




