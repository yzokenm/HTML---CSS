Today's Agenda:
    Lists:
        1: ul 
        2: ol

Lists => Ordered/Unordered list
style => list-style-type: none/disc/circle/custom
float => Float CSS xususiyati, bu - elementni konteynerning chap yoki o'ng tomoniga joylashtiradi va matn va inline elementlarni uning atrofida o'rashga imkon beradi. Element sahifaning oddiy oqimidan o'chiriladi, lekin hali ham oqimning bir qismi bo'lib qoladi

https://www.w3schools.com/html/html_lists.asp => full explanation here


li child is set to float and there is a problem unless we set UL to overflow hidden:
    The Problem with Floating Elements
    When child elements (in this case, <li> elements) are floated, they are removed from the normal document flow. This means that the parent container (<ul>) no longer recognizes their height. Without a proper height, the <ul> would "collapse," and its background or borders wouldn't extend to cover the floated children.

    The Role of overflow: hidden;
    Setting overflow: hidden; on the parent <ul> creates a block formatting context (BFC). This context ensures the parent element properly "contains" its floated children. Specifically, it causes the <ul> to:

    Adjust its height automatically to include all floated child elements.
    Prevent visual issues, such as the background color or border of the <ul> collapsing.
    How It Works in This Example
    The <li> elements are floated, causing them to align horizontally.
    Without overflow: hidden;, the <ul> would have no height, and the black background would disappear.
    With overflow: hidden;, the <ul> expands to fully contain its floated <li> children, ensuring the black background remains visible and properly encloses the content.

Task: U/I of the layout

-------------------------------------
         My Navigation Menu
-------------------------------------
|  Home  |  About  |  Contact  |
-------------------------------------

-------------------------------------
       Favorite Websites
-------------------------------------
1. Google
2. YouTube
3. Instagram
-------------------------------------
         My Task List
-------------------------------------
- Complete HTML assignment.
- Practice CSS.
- Learn JavaScript.
-------------------------------------