Let’s get lazy with React
=================================================

* Speaker   : [Ricardo Soares Silva](https://pixes.camp/ricardani)
* Length    : 90 minutes (workshop)
* Language  : English

Description
-----------

Do you like how your application gets bundled into a single file? 

Do you like that the user has to download the full code only to find out they never left the home page? 
And then you add features, new pages, experiments and the bundle gets bigger and bigger and bigger. 

Fortunately, React allows you to split your main code bundle into several chunks that can be lazy loaded by the users only when needed. 

And how is this done? 
By using one of the future features of ECMAScript: dynamic imports.

Do you hate it when you need to write code like this in every component

    if (isLoading) {
        return <LoadingSpinner />;
    }
    return (
        <>
            <ActualComponent />
        </>
    );

just to handle the loading state? React is trying to solve this in their experimental branch by using Suspense

    return (
        <Suspense fallback={<LoadingSpinner />}>
            <ActualComponent />
        <Suspense />
    );

Join us and learn how to be lazy and write less code with React. 

Speaker Bio
-----------

**Ricardo Soares**

![Ricardo Soares](https://raw.githubusercontent.com/PixelsCamp/talks/master/img/ricardo_soares.jpg)

Ricardo is a software developer at Blip. He is not intimidated in switching between frontend and backend technologies, without forgetting to test everything to assure the quality of his code. He believes that with an amazing team the sky is the limit.

Links
-----

* Company: [Blip](https://blip.pt/)
* GitHub: [Ricardani](https://github.com/ricardani)
* Photo: [Photo](https://raw.githubusercontent.com/PixelsCamp/talks/master/img/ricardo_soares.jpg)

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
