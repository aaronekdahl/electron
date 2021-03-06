# electron

Topic Chosen: Ways Of Using Javascript Outside The Browser (Node, Electron, etc)

Specific Subject: GitHub Electron

JavaScript as I have so far experienced has been incredibly simple, yet incredibly frustrating at the same time. It is officially my first, and I will admit right now, definitely not my last programming language. 

I had come in to this program (Web Development and Design) thinking I wanted to help people make websites that look great. That was it. I had absolutely no idea how much deeper things would actually get! 

As the class got more in to the JavaScript side of web development, and the design portion took a back seat to our main “studies”, I realized that there was much, much more to what I could do within a web browser than make things look good. This was the turning point for what I feel should be my direction in future programs and possibly a new career. 

Now, on to what tinkering with JavaScript has lead me to discover over the past few months…I’ve learned that JavaScript (along with HTML & CSS) is being used to create full fledged cross platform applications, not just web pages. This really got my attention. The ability to take what I’m learning right now and turn that in to real applications, not just web apps or web pages is just cool. Also since day one of learning web development and design I have been in love with Github…no idea why, there’s just something so satisfying about using it.

With Electron the GitHub team has taken what was being done with node.js and simplified it. Electron has all the node.js and Chromium APIs “built-in” to it. 

Unfortunately, or not, depending on your views of the node package manager, it is still a big part of Electron. Electron is a module that is located in NPM and NPM has all these dependencies you’ll have to rely on to make everything work. Not sure if I’d need to get in to NPM here but it’s one of those things that as of right now I find very confusing. Luckily there’s a “how to install” this, that, and everything else through NPM.

Electron takes whatever application you have or will create and makes it more accessible to just about everyone by using what is basically a web page as a graphical user interface to display your application. The only “catch,” which really isn’t a catch these days is that whatever device would be running your app would need to be able to handle a bit more action than just browsing static web pages.

So, now comes the part where I talk about things, I really don’t know much about, but figure it is what makes this a technical paper that demonstrates I at least read up and researched the main subject a bit…

Since Electron is making what is essentially a “fancy” web app, it relies on a couple of main processes when running your application. They are as follows; the “main” process and the rendering process. I’m not sure what other compilers deal with this, it could be all of them or just some of them. Anyway, the main process is the “manager” that contains the render processes of your application. Then the stripped down version of Chromium that Electron uses takes these render processes and displays them as your application windows to the user. The advantage of having this go on is that your application will have access to native graphical user interface APIs through node.js APIs, which will in turn allow the developer access some of the users lower level operating system actions. Apparently from what I’ve read and remember, this is not allowed for an actual every day web page.

This ends my current rendition of this essay. Everything after what is stated above is a bit too technical for me as of right now and I have no reason to pretend to know what I’m talking about.

