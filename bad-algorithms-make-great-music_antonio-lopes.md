Bad Algorithms Make Great Music
========================

* Speaker   : António Lopes
* Available : October 6th and 7th (all-day), would like to avoid October 8th
* Length    : 30 mins should suffice, but some time should be accounted for comments/questions afterwards
* Language  : English or Portuguese, I'll leave it to the audience to decide

Description
-----------

Artificial Intelligence has been romanticized by science-fiction movies, but it's not a glamorous life. Most of an AI researcher's time is spent modelling, running and tweaking simulations. So you end up spending too much time looking at a terminal watching millions of lines of logs passing by.

To make it a bit less boring I decided to spice up the simulations by using different visual and acoustic approaches. One of those approaches consisted of playing some musical notes whenever a task was completed in the simulation. At first, the output produced by the initial algorithms was quite bad and didn't resemble anything like what someone would consider to be music. It was only when I tested some algorithms with poor performance that some melodic tunes started to appear. It turned out that bad algorithms (the ones in which the tasks are completed over an extended period of time) ended up producing better music.

This made me think if these automatically-generated pieces of music could pass as being the work of a unknown (human) artist. So I decided to put them to the test. You won't believe what happened next.


---------------
[*All things below are optional*]

Speaker Bio
-----------

```java
try{
  Bio bio = new Bio();

  bio.setName("António Lopes");
  bio.setCurrentJob("Head of Development at ISCTE-IUL");
  // ATTENTION: this next line may throw an overflow exception sometimes: after all, there's only 24 hours in the day 
  bio.setAnotherCurrentJob("Artificial Intelligence Researcher at Instituto de Telecomunicações");

  bio.getQualifications().add(new Qualification("Computer Science", 2002));
  bio.getQualifications().add(new Qualification("Telecommunications Engineering MSc", 2006));
  bio.getQualifications().add(new Qualification("Artificial Intelligence PhD", 2011));

  bio.getHobbies().add(new Hobby("DIY"));
  bio.getHobbies().add(new Hobby("Programming"));
  bio.getHobbies().add(new Hobby("Attending geeky events"));

  bio.getLinks().add(new Link("Twitter", "https://twitter.com/tonyvirtual"));
  bio.getLinks().add(new Link("Homepage", "http://antoniolopes.info/"));
  bio.getLinks().add(new Link("CV", "http://antoniolopes.info/cv/"));

  System.out.println(bio);

  System.out.println("== Yes, I chose Java. Deal with it. Make programming love, not language flame wars. ==");

}catch(Exception e){
  URL url = new URL("http://stackoverflow.com/search?q=[java]+" + e.getMessage());
  URLConnection con = url.openConnection();
  InputStream in = con.getInputStream();
  String encoding = con.getContentEncoding();
  encoding = encoding == null ? "UTF-8" : encoding;
  String body = IOUtils.toString(in, encoding);
  System.out.println(body);
}
```

Links
-----

* Blog: http://antoniolopes.info/blog/
* Company: http://www.iscte-iul.pt/
* Github: https://github.com/antoniolopes