
So I learned something interesting just now and I wanna make a note of it. I’ve been really bumping my head into organization as I try as I begin to tackle a more complex project this loop sampler is the most complex module I have ever attempted to build and the single file or single file plus one or two libraries or head files is not cutting it. This is going to require a much more Methodical and robust method of layering and organization in order to keep everything manageable so that I’m not scrolling through 3000 lines of code Trying to find where the mistake happened or something

Anyway, talking to Bob about like what you know how professionals do this and on the subject of drivers. He reminded me that like a driver is basically just a piece of software that handles. A driver is just a piece of a piece of code that gives you a reusable interface to a piece of hardware and reusable is the keyword

So now I’m thinking OK I need to go back through E encoder and rotary switch and even deck list and I need to figure out is are these libraries only surfacing generic reusable things I think they are but I just need to crystallize that idea in my mind that like Driver is just a more specific term for a library that exposes an interface to a hardware peripheral.

And IAnd I Is actually probably the better term for a lot of of the things that I have been doing