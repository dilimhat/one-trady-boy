# one-trady-boy

*Plan is to create a website where people are encouraged to share trading bot code and help new people learn the trade

*I've wanted to learn this for a while now, but it seems that I really do have to do everything myself if anything is gonna work out the way I want'

*I think that if i make good progress and prove myself capable, then other capable people will come along the way and join me

*Micro Charter: 

--Micro-charter--
*Codename: 
    kids next door
*Mission statement:
    Create website with assistive application that supplements the user with market knowledge about the foreign exchange ecosystem, and backtests prefabricated algorithms at home or on the go to rank performance and quality of securities.
*Vision statement: 
    Bring algorithmic and modular trading to your average joe! RobinHood, but you make money.
*Elevator pitch:
     AuguryX will be the holy grail of modular trading. We are here to help users meet and learn the demands of the market and allow them to implement competitive strategies 
*Target customers/users:
    I am a competent day trader named Steve
    I want an assistant to help me make unbiased trades
    I want this because I am losing money, I need a competitive edge in this increasingly quantitative field

    I am a student interested in algorithmic trading
    I want a good jumping off point to start learning about what exactly is going on behing these big words
    I want this because it provides tutorials, there is a community to rely on for advice, and I can make and test bots
    with little to no coding knowlege

    Im a girl who knows alot about econ and trading
    I want to share my hobby with others
    I want to use this site because everyone in my life thinks im boring, but these people really like my passion
    so I wanna talk to them and teach them

*Metrics:
    -UI improvement:
        + overall aesthetic of the site.
        + logic in page flow
        + simplicity of use, especially in context of out new trady-them case
            + getting started should be an almost linear path
        + real-time data and info flow
        + personal messaging
        + bot modularity
        + public posting and commenting
    -Database:
        + storage and access of basic user info
        + storage and access of user commentary
    -Trading bot:
        + ability to share code
        + ability to store code securely
        + maybe a GitHub link so multiple users can work on the same code
    -Tutorial:
        + simple articles for people to get started
        + link to streamlined, non frivolous starting material, stuff even Dilim could understand
*Milestones:
    + basic HTML and CSS front end webpages of non user screens
        + splash page
        + about us page
        + features page
        + forum page
        + contact us page

    + user sign up and sign in pages
    + database that stores and accesses user data 
    + persistent user login session
    + email verification upon sign up
    + password recovery via email
    + live market data
    
    + user profile:
        + dashboard setup based on level of experience determined during survey
        + dashboard stored in database for each user
        + basic user profile picture
        + user able to switch between different dashboards 
        + users can monitor specific data when they log into the site
        + users can make public posts in the site in the forum page
        + basic info and posts are saved in the database
        + direct messaging for users
        + users can post graphs of their current trading progress for the public, or they can keep them private
        + user email notification
        + friend requesting 
        + group creation
        + user url like a website or their own
        + profile page with public user activity
        + searchable user database
    
    + Community:
        + forum posts
        + classes that verified or respected users can host to teach
        + money can change hands if one user wants to pay for the services of another
        + trady-boy competitions
        + user blockchain digital modular contracts which allow users who collaborate on a project to formally agree on secure terms on trady0-boy ownership

    + Trady-boy:
        + be able to upload the code for the bot
        + back testable in various markets of choice
        + for Novice users modularity of simple trading strategies and signals can be generated as code
        + site wide statistical showcase of whether certain trady-boy signals are going up or down the polls in success rate in implementation
        + group collaboration on new trady-boys. 

    + Mobile companion app:
        + login to user account
        + view posts from other users
        + comment on posts
        + send and receive direct messages from other users
        + view live market data
        + start, stop, and switch out tested trady-boys
        + monitor health of trady boys
        + security authentication with QR code login for new or public devices

*Resources:
    + inspiration:
        + https://www.tradingview.com
        + betterment.com 
    + Web dev:
        + HTML, CSS, Javascript and JQuery
        + PHP
        + Bootstrap
    + Database:
        + MySQL
        + maybe mongo
        + maybe Firebase
    + Live data:
        + news stream api
        + twitter integration
        + trading view api
        + JSON
    + Testing:
        + OANDA API
        + Scientific/ML libraries
        + OTHER
    + Hosting:
        + AWSBucket
        + some other sort of domain hosting
        + Market research from Emory resources
        + other students to help
*Risks:
    Loss of money, possibly exceeding original investment
*Trade-offs:
    Based on what markets we focus on



-----------------whats important right now?---------------------

    * it was super motivating to have made the website earlier. I think ill start there. 
    
-----------------User Stories-----------------------------------

1. make the non user webpages:
    * use html and css to  design these 
    * they will be php pages tho (changed to html pages)
    * pages:
        + header
        + footer
        + index
        + about us page
        + features page (moved to a later story)
        + forum page
        + contact us page
-----------------------C O M P L E T E D--------------



-----------------------N E X T--------------
2. website completion

    * user accounts and logged in session
        + create logged in session and backend first
            - try following the Lynda tutorial for angular and Node JS
        + make a user profile page that is specific to each user
    * email confirmation upon sign up
    * forum

-----------------------N E X T--------------
3. make core functionality of modular trading bot
    * tasks:
        + come up with trading robot templates
            - Python
                * follow that Poloniex video series first
            - MQL4
        + be able to print out source code to a file by parsing it as a string using another program.
            - program should identify markers in in the template (possibly comments) and insert the contents of another file into the area
        + things to insert into templates using printer file:
            - API to connect to
            - API keys
            - Indicators
        + make GUI applet that makes these two other programs interact with each other through drag and drop

  