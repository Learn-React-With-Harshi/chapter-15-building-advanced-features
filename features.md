# `Learn React With Harshi` Series 
   Documenting my learning journey of [Namaste React Live Course](https://learn.namastedev.com/) conducted by Akshay Saini
   

## Machine Coding Round : 

- Developing/Coding -  an app during the interview 

- Many companies ask to develop in `HTML, CSS & Javascript`

- Some companies ask to develop in their tech stack -> `React`

- Examples of problems asked in interviews:
todo list 
caurosel
infinit scroll
counter app
bouncing
image gallery

* Important in machine coding -> Time management *

How to manage ? 
-> Practice before interview 
-> Plan before starting the interview  
-> Execution 

### What are we going to build ? 

*** YOUTUBE *** 

1. Requirement Clarification : 
- features 
- tech stack and briefly say why - UI layer & Data Layer 
JS Framework -> React 
CSS -> Tailwind CSS
Routing -> react-router-dom
Web bundler -> webpack 
Testing -> Jest 


2. Low-level Design - There are 1000 ways to implement a project -> LLD makes sure that both you and interviewer are in the same page 

Component UI Hierarchy 
App
  Header 
  Body 
    SideBar
    MainContainer 
      CategoriesButtonContainer
        CategoryButton
      VideosListContainer
        VideoCard
    VideoPageContainer
      VideoContainer 
        VideoStream
        VideoDescription 
        VideoComments
      CategoriesButtonContainer
        CategoryButton
      VideosListContainer
        VideoCard


3. Basic features that we are going to develop in this chapter 

1. Display hamburger menu, logo, search input bar, button and user login button in Header 

2. Display List of menus in Sidebar (hardcoded for now)

3. On click of hamburger menu, toggle the Sidebar

4. Display CategoryButtonsContainer (group of category buttons) and VideosListContainer (list of most popular videos (video card) in India) in Main Container.

5. On Click of any video card, naviagte to `/watch` page along with videoId

6. In VideoPageContainer, Play the video, and display its description like video details and comments. 

7. On right side, display the CategoryButtonsContainer and VideoListContainer (videos relevant to the currently played video)






