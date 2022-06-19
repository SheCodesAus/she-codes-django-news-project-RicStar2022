# She codes news project

I really liked how we worked on this project in class. It combined my previous knowledged of CSS and HTML with DJango. Unfortunatly due to technical issues, I was unable to finish this project. After I installed 'brew' my system wasn't behaving how it should and now I can't even get my sever to run locally. 

Please refer to my trouble shooting section to learn more. 

## Part 1
- Order the stories by date.
-- I removed the wiki date picker and the stories add by date, I believe the stories are listed by most current dates at the top.
- Style the form for adding new stories.
-- CSS has been added to the form, not to the level that I would like but there is CSS styling
- Add a field to the NewsStory model for an image url and use this image url rather than the default images 
provided in the starter.
-- This has been added, again, given that I cannot get updated newsroom story page to load I am unable to confirm if this actually works. 

## Part 2
- Functional login/logout buttons.
-- There are functional login/logout buttons on the applications
- Account view so authors can see their profile information.
-- this was unable to be created as I was unable to get the local sever or the Heroku server. 
- Create Account functionality, so a new user can sign up to be an author.\
-- Same as above
- View stories by a particular author.
-- same as above
- Show/Hide the relevant information and buttons based on whether the user is logged in/out (e.g.
should only be able to see the button to create a new story if I am logged in).
-- I belive this is working
- Enable/Disable the relevant features based on whether the user is logged in/out (e.g. should only be
able to create a new story if I am logged in).
-- I am unable to check this but I believe that this feature does not work. 

## Trouble shooting

### The error: 

The import dj_database_url in the settings.py file has a squiggle green line underneath which states:

    Import "dj_database_url" could not be resolved from source Plyance(reportMissingModuleSource)[Ln 15, Col 8]


### What I tried:

1. Googled the error, which mentioned that I might not have the library installed correctly. 

"Unresolved Import" is an error message produced by VSCode, not Python itself. The message simply means that VSCode cannot detect the correct path for a Python module. The cause of "Unresolved Import" could be one of the following reason: VSCode is using the wrong Python path."

-- So I ran "pip install dj-database-url" to try and rectify the problem. 

2. I ran "python3 manage.py runserver" again but it sill gave me an error message. The last line of the error "ModuleNotFoundError: No module named 'corsheaders'" 
    Side note: I have noticed that throughout the Django unit that the lead mentors notes and our (student) notes do not match. This purely relates to the code not the descriptions. 

3. I went back over the Saturday class to make sure that the code that I had was copied over correctly from my notes in Thinkfit. 
-- no errors with my copy and paste. 

4. VS code has been asking me to restart the program to be able to update.
-- This identified another error that stated VS code was corrupt and that I had to reinstall VS code because the application was corrupt. I again closed the application down and reopened the program to correct it.

## Overall
I've spent over 20 hours this week trying to understand why this won't run correctly. The above is the main avenues I have taken to rectify the error. But I have watched various YouTube videos and read a variety of posts and I'm still left extremely frustrated as to why this will not work. 
As we are now closing off study week, I'm concious of the lead mentors time and the other students awaiting my submission. 

I am not a quitter and so I will continue to work on this after my submission becauase above all else it annoys me that I cannot solve this puzzle. 