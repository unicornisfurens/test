---
ID: 7
post_title: Basic concepts
author: nick
post_date: 2016-02-03 16:36:06
post_excerpt: ""
layout: page
permalink: http://tenforce.konstantinkharlov.com/
published: true
---
[expand title="%(%h5%)%User%(%/h5%)%%(%h6%)%Users can log into pmX. And they can own items and lists. They can visit stuff and create other stuff. They are who we serve.%(%/h6%)%" rel="user" findme="auto"]
<h5>What does a user entail</h5>
A user has a username, a password, and some personal information. Each person that needs to log in will have such a user. It is used to identify that specific person. Computer services may have a username too, similar to a human user. The identification allows you to know who created a ticket, and who solved it. It may also indicate that the ticket came from an external service. Both droid and humans receive their own username, allowing us to accredit them for their work. Regardless of the occasion, any service or user that needs to perform an action, will receive a user. Each user has a username to identify them by.
<h5>Can you give some examples?</h5>
A user can represent your CEO, any application using pmX, or your smallest customer. Any person or service that uses pmX has a username. Take driver Joe, for instance. Say he notices the suspension of his truck is wearing out prematurely. He would log into pmX and create a ticket indicating the suspension needs to be fixed. Driver Joe has a user. Martin the mechanic will pick up the ticket and plan when the truck needs to come in for inspection. Martin has a user as well. Driver Joe has access rights on all tickets he creates, so he can add feedback if necessary. At the end of the process, we can follow the trail, and see who was involved. Handy, no?
[/expand]

[expand title="%(%h5%)%Item%(%/h5%)%%(%h6%)%An item represents an artifact in the application. It can be a truck in your company, the package a client has ordered, or a cool glass of whine on a hot summer evening. If pmX needs to know about it, it's an item.%(%/h6%)%" rel="item" findme="auto"]
<h5>What is described in an item?</h5>
An item contains the complete description of the artifacts we want to track. Items have a set of fields which will be entered and shown to the users. The artifacts an item can represent are as wide as what you may want to represent in the workflow of the company. Each item contains an identifier for that specific item, and a set of fields which represent the contents of the item. By extending the item, you can tailor it so it contains exactly the information you want to record in the company. Items are configurable artifacts describing the business logic of your company.
<h5>Can you give some examples?</h5>
Pratical examples of an item are an IT support ticket, a company car or a big software project. Say Martin the mechanic detects that the truck he is working on needs new bushings (he'll know what that means, because he's a mechanic), he can indicate that the truck needs to come in for new bushings. Martin will order the new bushings, and he may create an item for these bushings so he can track the order. The scripting guys can even automatically schedule the truck to come in once the bushings have arrived. Anything we want to track in pmX can be an artifact.
[/expand]

[expand title="%(%h5%)%List%(%/h5%)%%(%h6%)%Lists are awesome. Lists contain items and specify what the items should look like. Lists define what information we need about their items. And the items in a list, may be lists. Items all the way down.%(%/h6%)%" rel="list" findme="auto"]
<h5>What is described in a list?</h5>
Lists may contain many items, and the description of the list describes the items contained in it. Computers are good at mass processing, so most data we process is written in a list. When we define a list, we specify what the fields are of the items in the list. That way, we describe the type of items once and can reuse them. But wait, there's more! You can move items from one list to another. The moved item will change its representation to match the representation of the supplied list. So we get all the benefits of having a standardized representation, and the flexibility individual representations would give us. Lists describe the items which are contained in them in a very flexible way.
<h5>Can you give some examples?</h5>
Any item we represent in pmX is contained in a list. The payroll, each of the trucks, all your customers, they're all contained one list or another. What a list consists of depends on how you want to structure of your business logic. If our production manager wants an overview of all the production machines at the plant, he'll open that list. It's the list of all production machines. If one of these machines would go on sale, then we could move it to the list of items to sell. Any information about the machine would still be contained in the item. Any item we have in pmX is stored in a list, and we can move the items around freely.
[/expand]

[expand title="%(%h5%)%Smart lists%(%/h5%)%%(%h6%)%Smart lists combine multiple lists and filter them. This lets us retrieve the necessary content and render exactly what the user needs to see.%(%/h6%)%" rel="smartlists" findme="auto"]
<h5>What is described in a smartlist?</h5>
A smartlist combines and filters multiple lists, generating a broad overview. It isn't always clear what should be in a separate list. If you group everything, you'll need to add filters to show only the necessary content. Should we store all items we sell in one list, or should we split the items per department? Although the choice is still prevalent in pmX, the resulting issues are alleviated. Use different lists based on what content should be in the items, and join (or split) the list using a smartlist. Smartlists allow us to combine multiple lists, or filter the items in a list.
<h5>Can you give some examples?</h5>
If you need to combine multiple lists of items, you can combine them using a smartlist. Assume we have two production lines, each producing a widely varying product. One produces red boxes, and the other producing blue boxes. The red boxes have a completely different description than the blue boxes, so we may want to put them in separate lists. Listing all available boxes could then be done in a smartlist. Smartlists make it easy to combine and filter any list.
[/expand]

[expand title="%(%h5%)%Workspaces%(%/h5%)%%(%h6%)%A company consists of many units. The delivery service unit will have other tasks than the production unit. Sure, some users may belong to both operations and tasks may need to move between across, but for the users it's mostly a separate application.%(%/h6%)%" rel="workspaces" findme="auto"]
<h5>What is described in a workspace?</h5>
A workspace provides a logical separation for the units of the organization. The workspace has its own homescreen with the contents most important for that part of the company. Mostly, it's a logical separation as it's an easy way to classify broad parts of the organization. Although items can move between workspaces, they generally don't. Thus keeping the logical content of each business unit separate. Of course, a user may have access to multiple workspaces. The workspace provides a logical separation between multiple business units.
<h5>Can you give some examples?</h5>
The production unit and the marketing unit are clearly separated. Sure, it's awesome if they communicate, but they won't share much of the internal working. The same goes with the upper management team, they simply don't need to know every detail about each other. It's good te separate these big logical lumps from each other. So these three units could have a separate workspace. But what about Melanie the marketing manager? Melany simply has access to both the upper management workspace as to the marketing workspace. Easy right? The upsides of separation, without the downsides. That's how we roll.
[/expand]

[expand title="%(%h5%)%Access rights%(%/h5%)%%(%h6%)%All users are created equal, but some are more equal than others. We all like driver Joe, but somehow we doubt he should raise the budget for the new trucks by himself. Access rights allow us to limit the access to various parts of the application.%(%/h6%)%" rel="accessrights" findme="auto"]
<h5>What is described in a access rights?</h5>
Access rights ensure users have a clean overview of what matters to them. There are two ways of looking at access rights. The most prominent reason for them is to ensure that no one oversteps their responsabilities. Each person has tasks to achieve and get the means to achieve them. The access rights ensure that you rule over the tools you get. It also limits the view of pmX based on what you can access. So well thought-out access rights ensure that pmX stays clear for every user. Access rights can be placed on the ownership of an item, or on the groups you belong to on a per-list basis. Access rights help users find what matters to them, and limits them from making mistakes.
<h5>Can you give some examples?</h5>
Well, there's driver Joe. He wanted to spend the marketing budget to dress up his truck. Now, that may have been a smart marketing move, but mostly everone agreed that the billboards were a better idea. Access rigths ensure that these things don't go wrong. It ensures the party committee doesn't overspend, so the next parties still work out just fine.
[/expand]