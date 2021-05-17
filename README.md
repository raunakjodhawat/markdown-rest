
# Markdown REST
![badge](https://markdown-rest.com/npm?title=You're&displayText=Awesome)

endpoint: `https://markdown-rest.com/npm`
## Motivation
There's always so many things that is not available with Markdown. One of the thing I thought, that was desperately needed was for, npm packages to have some way of displaying latest published version. But that was impossible to do. You would either have to hardcode the latest version, or create an endpoint that serves latest version. But now, you can use the endpoint described here to get your own "latest version" in the markdown, as easy as by writing one line of code and then completely forgetting about it.

With this project Markdown REST, I would be creating multiple markdown components, that connects a package metadata to markdown's. Feedback/feature request are more then welcome!


## Features
## 1. NPM Version Badge
Display latest published version of npm package on your markdown, with simple one-liner and multiple ways to configure it

### Usage
`![badge](https://markdown-rest.com/npm?package=package_name)`


Example (with package name as node-fetch): 


![badge](https://markdown-rest.com/npm?package=node-fetch)

  
### Parameters
**package**: Name of the package, for which you want to get the latest published version


`![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World)`


Example (with package name as node-fetch):


![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World)

**displayText**: If you want to display some funky text message, in place of actual version


`![badge](https://markdown-rest.com/npm?title=You're&displayText=Awesome)`  


Example: 


![badge](https://markdown-rest.com/npm?title=You're&displayText=Wonderful)


Note: Either package or displayText parameter has to be provided, preference is given to displayText

**title**: Anything you want to replace the text 'npm'


`![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World)`


Example:


![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World)

**timestamp**: When you want to include timestamp to the tag


`![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World&timestamp=1)`


Example: 


![badge](https://markdown-rest.com/npm?package=node-fetch&title=Hello%20World&timestamp=1)


More features coming soon, please look out this space for everything related to creating cool/effective markdowns

Connect with me on [LinkedIn](https://www.linkedin.com/in/jodhawat/)


Reach out via [email](mailto:raunakjodhawat@gmail.com)
