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

###Reflect
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

