                Group'A'
1. Define Information Architecture(IA)
Information Architecture (IA) is the process of organizing, structuring, and labeling website content so that users can easily find and understand information

2. What is a Wireframe?
A wireframe is a basic visual layout of a webpage that shows structure and placement of elements (menus, content, buttons) without colors or design details.

3. Explain the concept of Cognitive Friction in web design.
Cognitive friction refers to the mental effort users must make when a website is confusing, poorly organized, or hard to navigate, which reduces usability.

4. Why should URL slugs use hyphens instead of underscores?
Hyphens are preferred because search engines treat them as word separators, improving readability and SEO, whereas underscores are not recognized as separators.



                 Group'B'
 5. Compare Hierarchical (Tree) structure and Linear (Sequential) structure.
Hierarchical Structure:
-Content organized in parent–child levels
-Easy navigation for large websites
Example: University website

Linear Structure:
-Pages arranged in a sequence
-User follows a fixed path
Example: Online tutorial or exam form
Use:
Hierarchical → complex websites
Linear → step-by-step processes

6. Explain the “Three-Click Rule” and its significance in UX design.
The Three-Click Rule states that users should find any information within three clicks.
Its significance:
-Reduces frustration
-Improves user satisfaction
-Encourages users to stay longer on the website

7. How do Card Sorting and Flowcharts help in planning a website?
-Card Sorting helps understand how users group information, improving navigation structure.
-Flowcharts visualize page flow and user journeys.
Together, they help design a clear, logical website structure before development.


                                   Group'c'

 8.You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.
 For a university website that contains hundreds of pages such as Admissions, Departments, Alumni, and News, the most suitable structural model is the Hierarchical (Tree) Structure.A hierarchical structure organizes website content in levels, starting from a main page (Home) and branching into main categories, sub-categories, and individual pages. Each page has a clear parent–child relationship, similar to a tree. This model is widely used for large and complex websites because it allows information to be grouped logically.
 -Easy Navigation for Users:Users such as students, parents, faculty, and alumni can easily find information because content is clearly categorized. For example, a student looking for admission details can directly go to Admissions → Undergraduate.
-Suitable for Large Content:Since a university website contains hundreds of pages, a hierarchical structure prevents clutter by dividing information into manageable sections and sub-sections.
-Scalability and Flexibility:New departments, courses, or announcements can be added easily without changing the overall structure of the website.
-Improved User Experience (UX):Clear navigation menus and logical grouping reduce cognitive load, helping users understand where they are and how to move to other sections.
-Better SEO and Content Management:Search engines can easily crawl hierarchical websites. It also helps administrators manage and update content efficiently.
In conclusion, the Hierarchical (Tree) Structure is the best choice for a university website because it supports large-scale content, clear navigation, easy expansion, and improved usability. This makes the website user-friendly and effective for both visitors and administrators.

9)A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the "KISS" (Keep It Simple) principle.
The "KISS" principle (Keep It Simple, Stupid) suggests that most systems work best if they are kept simple rather than made complicated. In the scenario you described, the design prioritizes "minimalist aesthetics" over "functional clarity," leading to a direct failure in user experience (UX).
Here is an analysis of that failure through the lens of simplicity.
-Unnecessary Cognitive Load:The primary goal of the KISS principle is to reduce the mental effort required to use a product. When a navigation menu is hidden behind a small icon (often called a "hamburger menu") on a desktop:
The Problem: The user has to first locate the icon, then interpret what it means, and finally click it just to see their options.
The Failure: On a large desktop screen, there is ample space to display navigation links. Hiding them adds an unnecessary step, forcing the user to solve a puzzle rather than find information.
-Violation of "Don't Make Me Think":Simplicity is closely tied to affordance—the quality of an object that allows people to know how to use it.
The Logic: A visible navigation bar says, "Click here to go to 'About Us'." A hidden menu says, "Click here to find out where you can go."
The Result: By hiding the primary tool for exploration, the designer has created a barrier. If a user has to search for the navigation, the design is no longer simple; it is obstructive.
-Misapplication of Minimalism:Designers often confuse minimalism (visual style) with simplicity (ease of use).
Visual Simplicity: A clean screen with one tiny icon.
Functional Simplicity: A clear path to the destination.
In this case, the website achieved visual simplicity at the expense of functional simplicity. For a user, "simple" means getting the job done with the fewest clicks and the least amount of confusion.The design failed because it valued the "look" of simplicity over the "act" of being simple. On a mobile device, a hidden menu is a necessary compromise due to space; on a desktop, it is an avoidable complication.

10)An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explain why this is bad for both users and Search Engines (SEO), and propose a better structure using Page Slugs.
The URL structure you mentioned—www.shop.com/prod?id=55&cat=9—is known as a dynamic URL. While functional for a database, it is "unfriendly" for both humans and search algorithms.
Here is a breakdown of why this structure is problematic and how to fix it.
-Why it’s bad for Users
Lack of Context: A user cannot tell what the page is about before clicking. Does "id=55" refer to a pair of shoes or a lawnmower?
Trust and Security: Random strings of numbers and symbols can look "spammy" or technical, which may decrease the click-through rate (CTR) in social media shares or emails.
Memorability: It is impossible for a user to type that URL from memory or describe it over the phone.
-Why it’s bad for SEO
Keyword Relevance: Search engines use the URL as a ranking signal. By using numbers instead of words, you miss an opportunity to include relevant keywords (like "blue-denim-jacket").
Duplicate Content Risks: Parameters like id and cat can sometimes lead to search engines indexing the same product under multiple URLs, which dilutes your "ranking power" (link equity).
Crawling Efficiency: Search engine bots sometimes struggle with complex strings of parameters, potentially leading them to skip indexing certain pages if the structure is too deep or repetitive.
-The Solution: Descriptive Page Slugs
A Page Slug is the part of a URL that identifies a specific page in a human-readable format. Instead of IDs, you use the product name and category name.
Best Practices for Your New Slugs
Use Hyphens: Use - to separate words. Search engines read hyphens as spaces, whereas underscores _ are often seen as a single character.
Keep it Short: Aim for 3–5 words. Remove "stop words" like a, the, and, of.
Stay Lowercase: Always use lowercase letters to avoid 404 errors on servers that are case-sensitive.
Be Descriptive but Static: Don't include prices or temporary sales in the slug (e.g., use /running-shoes instead of /running-shoes-20-percent-off) so the URL stays valid forever.
