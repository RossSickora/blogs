# Agile Principles Blog 3

Happy March, and welcome back for another installment where we will discuss the third principle of agile:  **"Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale."**  If you want to take a look at all of the principles of agile, check them out here [Agile Manifesto](http://www.agilemanifesto.org)

This principle seems easier said than accomplished, however what is stopping your teams from delivering the software you build each day, week, or month?  Understanding the constraints of what is preventing frequent regular releases of what you build is the first step.  In my experience there are a few things that prevent me from actually delivering (releasing) working software:

1. I'm scared
2. I'm lazy

## I'm scared

If there is one thing we have at Principal, it is an abundance of history.  We have been building software for decades, and that means it is very challenging to know when we change a system, that we didn't adversly impact another system.  Because of these side effects I get scared to release software.  These side effects also have scared my business partners too.  When I'm scared and my business partners are scared, we need one thing to overcome that fear of releasing!

**Prove It Works!**

Generally we prove things work by executing meticulous test plans, coordinating with other humans to identify what could go wrong. This is generally a very time consuming process which is still prone to error.  I can think of one outage I created a little over a year ago.  We made a relatively small change which led to a four hour outage one Wednesday morning, because there was a little extra security that we didn't know about when we were testing. We went through all of the process and still failed spectacularly delivering a very small incremental change.

One way we can start removing this fear is by automating our risk away.  When we uncover a risk we need to find a way to prove we have mitigated that risk automatically.  We don't have to overcome every risk all at once, but when we find one; we should find a way to never have to worry about that one again.  Over time, we'll have an environment where we can be fearless.  Have some ways you have overcome your fear of releasing?  Share below in the comments!

## I'm Lazy

I'm not saying we're all lazy, but I'm lazy.  I veiw it as a strength in most circumstances.  Lazy developers automate their problems away (see I'm Scared above).  Lazy is not however a strength when it comes to releasing software at Principal.  In my experience we have enough manual steps to delivering working software that we do the logical lazy thing, we bundle our releases.  A few bits of code for this application and that one, some security changes for another, and finally a tiny little change to this one other thing all get bundled together in one PCM request.  Which of those changes was really waiting on another?  Did we just delay some security changes because it was easier to release it all together?  Talk about an easy way to improve your **speed to market** make those steps easier.  We have made several improvements to this process over the years, but for the lazy one like me the process is still combersome.

**Keep Automating!**

Standardization allows us to automate what we do, automation also makes standardization easier.  If we automate how we test our software, we can standardize the way we output the results of those tests, when we standardize the way we output those results, we can automate a way to prove we built what we said we would build, which allows us to take one less step in delivering working software.  Helping the lazy and non-lazy alike deliver more working software faster!

What steps have you taken to make delivering working software frequently a reality for your area?  Have you shared that with other areas?  Communication is the heart of agile. So please, share your ideas and actions with others 