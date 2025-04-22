# Figma Design Strategies
Design components need to be scalable for various use cases, both present and future. Most importantly, they need to be usable by UI library consumers. A good indicator of component usage is the frequency of broken instances. When a designer breaks an instance, the component likely didn't meet their needs. A pattern of broken instances indicates a need for component improvement. Broken instances disconnect components from the master, losing critical properties such as interactive states, responsive variants, theming, language, as well as not receive component updates.

We want to prevent [component detaching](https://help.figma.com/hc/en-us/articles/360038665754-Detach-an-instance-from-the-component). This can be achieved by better organizing nested elements, which helps designers understand component structure, and enhances organization while optimizing and saving Figma file memory. This is achieved through better structuring, organizing, and optimizing complex design components by applying the following applicable strategies.

### Design Strategies for Complex Components in Figma
1. [Concept of base components](https://medium.com/timeless/concept-of-base-components-1215ac71e88c) `Not recommended`
2. [Comparing base components, variants, and slot components](https://www.figma.com/community/file/1059969965206286524)
3. [Base components best practices](https://www.figma.com/community/file/1014940662898686749) `Not recommended`
4. [Building scalable variants using base components](https://youtu.be/Im2Eg-m688Y) `Not recommended`
5. [Building flexible components with slots](https://www.figma.com/community/file/969234311094210750)
6. [Best practices for component props](https://twitter.com/Ridderingand/status/1544712832683425792)
7. [Creating and organizing variants](https://www.figma.com/best-practices/creating-and-organizing-variants/)
8. [Using variants effectively](https://www.figma.com/best-practices/creating-and-organizing-variants/using-variants-effectively/)
9. Slot components best practices:
   1.  [Thread 1](https://twitter.com/Ridderingand/status/1435094399143137281) 
   2.  [Thread 2](https://twitter.com/Ridderingand/status/1447600854215782400)
   3.  [Thread 3](https://twitter.com/Ridderingand/status/1482434935428300800)
   4.  [Thread 4](https://twitter.com/Ridderingand/status/1527393687960842253)
   5.  [Thread 5](https://twitter.com/Ridderingand/status/1592561652758548480)
10. [Example of using slot components](https://youtu.be/jdFFH9MvGhw)
11. [Template components in Figma](https://youtu.be/iW_goSGqrNk)
12. Component properties best practices
    1.  [Thread 1](https://twitter.com/molly_hellmuth/status/1557780376390537216)
    2.  [Thread 2](https://twitter.com/Ridderingand/status/1552677501683376128)
13. [Repeating children](https://twitter.com/SShuaiqi/status/1597093945925779456)
14. [Pseudo slots](https://youtu.be/CGWbit0BDQM)
15. [Nested elements and instance swap](https://medium.com/user-experience-design-1/make-your-figma-components-work-harder-6d7e0baf96e8)
16. [Structure and clarity](https://www.buttonconf.com/blog/how-to-bring-structure-and-clarity-to-design-system-components)
