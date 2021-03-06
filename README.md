# introjs_forblackboard
Use IntroJS to give users on-screen help with insanely multi-optioned Blackboard pages (built originally for Mt. Hood Community College)

**SETUP**

This is a "hack package" for JavaScript Hacks (JS Hacks) building block: http://projects.oscelot.org/gf/project/jshack/. Tested on Blackboard SaaS 9.1 environment.

**WHAT IS INTROJS**

Documentation for IntroJS found here: https://introjs.com/. You'll notice I tweaked the JS for IntroJS to be more accessible, and the source file is now called "intro_accessible.js," which isn't the same as the one from HarvardX (https://github.com/Colin-Fredericks/hx-js/blob/master/HXHelper%20Files/intro_accessible.js), but that one looks pretty cool too.

**WHAT DO I EDIT**

This is an example of how to use IntroJS with Blackboard for the "Test Options" screen. You can use it for a lot of different screens: basically anywhere you can inject JavaScript via the JS Hacks building block's injection points and restrictions.

The most basic thing to edit is the array of instructions in snippet.html, all of which correspond with different on-screen elements that are nabbed in the dom:loaded event observation. If that doesn't freak you out, you probably know that you can figure out how to get the elements you need with your browser dev tools. (Bearing in mind that Blackboard's element-loading is pretty dynamic, and you have to be pretty rigorous about checking to make sure something is there and is where you think it is before you assign it an IntroJS "step.")

If that does freak you out, you should get help from someone who knows what all of that means.

**CREDIT**

Besides IntroJS and JS Hacks, credit for some of the styling should go to Jeff Rouyer, and credit for the actual help text on the different "Test Options" should go to Nathalie Wright and Allison Georgioff.
