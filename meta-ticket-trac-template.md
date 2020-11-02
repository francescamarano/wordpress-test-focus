As we are aware, a lot of the web relies on WordPress. This means that we as WordPress contributors have a duty to deliver quality updates. This not only means that coding standards should be checked or code reviews are done, but also that we should spend more time on testing new features, bug fixes and everything else.

We are currently working on the testing area in WordPress. This means that we are actively looking into improving the quality of everything released in WordPress. To make sure all tickets can get properly tested, developers need to help the testing team to test their submissions.

This means that developers:
- Need to add test cases/steps in all tickets so testers know exactly what to test;
- If a ticket has priority, notify #core-test in Slack

There is a #core-test channel in Slack where we’re happy to help out any developer or tester with testing or the scenarios that need to be covered.

## Possible fix
As we cannot expect every developer to exactly know what to write to explain to the test team what needs to be tested and how, this means the Trac template needs to be updated with testing information.

The issue is in this: inserting comments as on GitHub can be done, but are not very user friendly, as a Trac comment will look like this:
{{{#! Comment
Note to: ....
}}}

This kind of comments in Trac might scare off (new) developers and this is something we absolutely do not wish.

I’d like to propose the following:
When creating a Trac ticket, you can submit various details, such as Keywords, Priority and Description. Extra steps with details on how to test will be added here. Perhaps it’s wise to automatically add an URL after it with a short ‘how to’ on how to write testing descriptions. If one is unsure on how to write testing descriptions, the developer will then also learn where to reach out for help.
We should make the fix as clear as possible, but not without forgetting the goal. While we want to make sure that developers will continue to develop and provide the best testing scenarios as possible, the ultimate goal is to test more and deliver more quality products.
