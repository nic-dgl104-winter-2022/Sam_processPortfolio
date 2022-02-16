# Sam_processPortfolio
## Week_1-Textbook production technologies
### Research
For this assignment I found multiple resourses that can be very helpful for the production of our textbook. But all of them have advantages as well as disadvantages.
Most of them required signing up and monthly payments while others were free for use.After spending some time I found [Scalar](https://scalar.me/anvc/scalar/) and [GitBook](https://www.gitbook.com/about).

**Scalar**

Scalar is a free, open source authoring and publishing platform that makes it simple for authors to create long-form, born-digital scholarship for online publication.
Scalar allows users to compile media from a range of sources and juxtaposition it with their own text in a variety of ways, all while requiring little technical knowledge.


*Advantages*

- It comes with a built-in reading interface as well as an API for using Scalar content to power custom-designed apps.
- Content in Scalar is comprised of three main units: Media, Pages, and Paths.
- Images, audio, and videos are all supported in Scalar and adding these various types of media to your page is done through links. 
 You simply select the text you want to associate with the media and attach it.
 
 *Disadvantages*
 
 A network connection is necessary to access Scalar books because they are hosted "in the cloud."
 However, because the majority of the media assets in a Scalar book are also held on servers managed by other organisations or firms, 
 if one of them experiences a technical issue, all media from that source within your book will be unavailable until the problem is resolved.
 
 **GitBooks**
 
 GitBook is a dynamic tool for sharing and collaborating on various types of content.
 It gives different users a one unified workspace where they can create, manage, and share content without having to utilise several tools.
 
 *Advantages*
 
 -They have certain built-in shortcuts that are quite useful. They also support a trial version, which is something that not many tools do.
 -You can create folders, categories, upload files, publicly share a page, and so on.
 -Setting up a custom domain is easy
 
 *Disadvantages*
 
 - For bigger teams it seems they charge a bit much than they do for small teams.
 - Lack of documentation.
 
 ### Reflect
 The only textbook I have used since the beginning of this program is zyBooks. It was convenient and intractive. Not only it provided with loads of information but they also had activites for students to test themselves. But It has some disadvatages too. It was expensive and were only accessible during the semester, so after the semester was over I wasn't able to access them. Beside that I haven't used any textbook most of teachers would provide us the link of some article or open source documentation for information on particular subjects. 
 
## Week_2-Style Guide
For week 2 research I have choosen [React](https://dev.to/abrahamlawson/react-style-guide-24pp) by DEV

As I am doing a project with React, so I am coming across a lot of documentation and style guides so for this assignemnt I would choose this one as it is beginner friendly and helped me a lot inproving my coding habits and naming conventions.Also it is very simple and easy to understand.
The first thing they talk about  is the basic rules which is:-

-Always include one react component per file.
-Always use JSX syntax

Then moving forward they share some basic naming conventions and declarations. The thing I found most interesting is that not only it informed about the things you should do
but also the things you should avoide doing or which can cause errors as well as explain the reason for avoiding them.
```diff
- Always define explicit defaultProps for all non-required props.
+Why? propTypes are a form of documentation, and providing defaultProps means the reader of your code doesn’t have to assume as much. 
+In addition, it can mean that your code can omit certain type checks.

  // bad
  function SFC({ foo, bar, children }) {
    return <div>{foo}{bar}{children}</div>;
  }
  SFC.propTypes = {
    foo: PropTypes.number.isRequired,
    bar: PropTypes.string,
    children: PropTypes.node,
  };

  // good
  function SFC({ foo, bar, children }) {
    return <div>{foo}{bar}{children}</div>;
  }
  SFC.propTypes = {
    foo: PropTypes.number.isRequired,
    bar: PropTypes.string,
    children: PropTypes.node,
  };
  SFC.defaultProps = {
    bar: '',
    children: null,
  };
```
There is a lot of information about components but not much about methods and hooks.

### Reflect
There were lot of things that I already knew about naming conventions but there were certain things that I wasn't aware of that I now make sure of doing after reading this documnetation like:-

Omit the value of the prop when it is explicitly true.

My old Code
```diff
<Foo
  hidden={true}
/>
```
My code after reading the style guide.
```diff
<Foo hidden />
```
## Week_3-API Search
For this weeks reserch I have choosen [Random User Generator](https://randomuser.me/)

This is a free and easy to use service to generate random user data for application testing. When I was conducting my reseach I came across this [blog](https://blog.hellojs.org/fetching-api-data-with-react-js-460fe8bbf8f2) which was based on how to fetch api with React.js. That was when I came across this API ad also started using Postman for pulling up the data. It is a great way to target specific data.You can apply it using npm, ajax as well as postman.The documentation of the API in the above link is very explanatory itself but apart from that there are plenty of other documentation that are very educational. What I liked about the documnetation that it gave proper information on usage, results as well as error handling. It shows how you can to generate multiple users, users of specific gender and nationalities. The only thing that I didn't liked is it only tells you how to call the api using ajax. So if you are not familiar with ajax or you want to call the Api with other method you can't use this documentation. So for me as I wanted to call this api using postman, I had to look at other documentations as well.

### Reflect
Reflecting on this research and my old projects I don't thik I have done a good job at all. I have neglected documenting my code as I thought they were small projects. But I have done a poor job on comments as well. After the week 2 and week 3 research I acknowledged the fact that commenting and documenting my code is important not only for other to understand it better but also for myself when I get back at it after an interval of time. In future, I will try to document all my project not matter if they are small or big. And adding proper and necessary comments in my code.

## Week_4-Find Your community
For my community code project I have choosen [StackOverflow](https://stackoverflow.com/).Stack Overflow's public platform, which was founded in 2008, is utilised by practically everyone who programmes to learn, exchange knowledge, collaborate, and advance their careers. Every since I have started coding this platform has helped me a lot not only with the coding questions but also with the tools like android studio and xcode. StackOverflow changed that and revolutionized programming by putting the answers to millions of programming questions online.Anyone on StackOverflow can post a new question and, most likely, get an answer within an hour. The community has very strict guideline for posting, so if someone tries to take disadvantage of the platform or post irrelevant content stackOverflow suspends them. It enables you to get answers to your most difficult coding issues, share expertise with your coworkers in a private setting, and discover your next dream job. They have a very efficient contact methods as well, through emails and phones services. You can also integrate your stckOverflow with Github, microsoft Team and  [Slack](https://stackoverflow.com/teams/integrations/slack). On top of that you can build your own team as well.It charges a small amount of money if you want to build a team but all the answers and articles are free they even a podcast.The site employs a successful carrot and stick strategy. Users that answer questions frequently and wisely are rewarded.

![stackOverflow](https://github.com/nic-dgl104-winter-2022/Sam_processPortfolio/blob/main/stackoverflow.png)

### Reflect
I have used stackOverflow for 2 years now and I like using it because it has all the content in one place no matter which programmming language you are learning or which tools you are using you can always find a solution for your problem.The Goal of the community is to create a healthy space where everyone is encouraged to learn and give back, Adopt a Growth Mindset. Be curious and eager to learn. Aim for ethical, sustainable, long-term growth, both personally and in the community. Other thing is you can easily give back to community just by answersing questions for new programmers. 

## Week_5-Debugging
For this week I choose Android studio as my IDE for debugging. I found various articles and videos on tricks and tip for debugging in android studio. Android studio have lots of tools that you can use to make debugging easier. So after a while I started applying these tips in my previous projects.First of all we need to make sure that our device is set-up for debugging. Android studio provides the ability to **attach debugger to android process** so you don't have to restart your app, it also gives you the ability to debug specific features.Because some operations run slower in the debug mode going through the app without the debug mode on is much faster. When you are one click away from the thing you want to debug, attach a debugger to your app and start debugging right there. There are hundred of ways to debug your app or code but the one that I liked the most was by using **breakpoints**. When you are at the point where you can’t fix a bug just by looking at your code, it’s time to use breakpoints. Breakpoints allow you to pause the execution of your app at a particular line of code. You can move your breakpoint if you think you have set it wrong, android Studio will highlight whatever line of code the app stops at when a breakpoint is hit. There are various kind of breakpoints that you can set up to track down a bug like conditional and dependent breakpoints. There were so many concepts that were advance I wasn't able to cover them all. But I didi applied some conditional brekpoints in my code just to test it out. So after setting up the breakpoints you can right click on it to add condition which be any code expression that equates to a Boolean.If the expression evaluates to true the breakpoint activates.

![Breakpoints]()

### Reflect
I don't have much experience in debugging. I have worked on small project and most of the error would be syntax and somtimes when the code wouldn't work after multiple tries I would just use stackOverflow to find the bug. The editor that I used till date is VScode and it doesn't have much debugging tools although there are some plugins that you can install that will help to detect the bug and review it. After this research I have atleast found the basic and proper technique to debug my code. I would definately use breakpoints in my code as it is simple process that i can even use in VScode. 
- I would attach debugger to android process.
- In debug mode, click on a line number in the gutter to run to that line.
