## DappSociety Daily Digest Archive

### What is this?
This is a place where we collect our daily digests in which we collect all the important (and not so important) stuff we do everyday. This helps us to stay focused and not getting lost and promotes transparency.

### Contributions

#### Who can write a daily digest?
Everyone who wants to contribute can do so.

#### Daily digest branch structure
```
---+-----------------------------master------------------------------------+--->
   |                                                                       ^
   |    +----------------wip/YYYY-MM-DD/user1------------------+----->     |
   |    ^                    |                                 ^     |     |
   v    |                    v                                 |     v     |
   +----+--+-------------wip/YYYY-MM-DD/master--------------+--+-----+-----+
           |                   |  ^  |                      ^
           v                   v  |  v                      |
           +-wip/YYYY-MM-DD/user2->  +-wip/YYYY-MM-DD/user3->
```
- The first user to contribute to a daily creates the wip master branch (`wip/YYYY-MM-DD/master`) and commits the [digest template](#digest-template).
- After that, the user should branch of this wip master into `wip/YYYY-MM-DD/username` and commit any changes to the digest itself there.
- Before merging the changes on the personal branch back into the `wip master`, a `pull` should be performed to include all changes merged into the `wip master`.
- Once the digest is finished, a pull request should be created to include the `wip master` into the `master` branch.

#### How to contribute?
Each digest has its own master branch, where all contributions are put together. This digest master branch follows this format: `/wip/YYYY-MM-DD/master`

- To contribute you should fork this master branch following this format: `/wip/YYYY-MM-DD/username`
- Commit changes to the post file (created following the template below).
- **Before merging the changes into the digest's master branch it is important to `pull` to get all changes committed by other users while you were working on your branch.**
- Merge your changes into the **digest master** (**NOT** the repository's `master`)

#### <a name="digest-template"></a>Digest template

** Add the end of the template is a link list that allows to use links easily without having to type the entire URL each time. Copy that list to any markdown file to make it available there.**  
Usage example:
```markdown
Link to #general Slack channel: [link text][#general]
```

```markdown
---
layout: post
title:  "Daily Digest - MONTH DAY, YEAR"
date:   YYYY-MM-DD 12:00:00
categories: daily
---
#If Nothing Else, Read This

[[ section of most important announcements and calls to action ]]

## Current Stats

[[ Analytics can be found in slack on the drop down tab next to the title name Dapp Society ]]

| Daily Active Users | Daily Active Posters|
|--------------------|---------------------|
| *Input analytics*  | *input analytics*   |

| % Public Messages | % Thread Messages | % Private Messages |
|-------------------|-------------------|--------------------|
| *input analytics* | *input analytics* | *input analytics*  |


## Notable Events

[[ Notable events overview ]]

## Community Projects

[[ Below are examples of categories of previous updates ]]

#### Logo Concept

#### Utilizing Social Media Profiles

#### Website Theme

#### Slack Channel Archive

### Ballot Box
[[ update team on current and important polls they should be voting in ]]

### New  Slack/Trello Channels
[[brief update and description of any new channels or updates to default channels ]]

### Trello Board Updates
[[ pretty self explanitory, add info about new voting or trollo boards which experienced a lot of action. Bellow are previous examples ]]

#### [Town Hall][trello town hall]

#### [Dapp Ideas][trello dapp ideas]
**This board has the potential to serve as our main catalyst / motivator for actually getting to work on real blockchain projects.**
[[ Really drive people to this page. Its important that we get moving on development. Should become increasingly detailed ]]

## Notable Discussions

[[ Any great debates or disccusions packed with info?! post them here and give a link and brief overview ]]

## Content Kiosk

[[ Skim through material added to the content kiosk and highlight the main points in order to drive people to these channels and encourage them to learn! ]]

## Volunteers Needed

[[ Update what we need active volunteers for. Below is an example from 2018-02-07  which mostly still holds true ]]

It's awesome how everyone is stepping up to the plate to help make this group amazing. But we're not running at optimal efficiency just yet :-)

Please see the `Volunteers Needed` section in [Monday's Daily Digest](https://dappsociety.github.io/digest_archive/daily/2018/02/05/daily-digest.html). What is needed today hasn't changed much since those tasks encompass most of what we are currently working on.

**IMPORTANT: One place where we will need help _right now_ is with writing these daily digests.**

We are going to create a generic template that can be used each day, delegating individuals to write each section. This will streamline the process immediately and be a beneficial structure once we scale, requiring contributions from individuals with more specialized knowledge on projects.

This will be especially important over the next 6 days while @BlockchainBud is out of town. Otherwise, the entire burden is @ericbrown99 :-/

It would be awesome if at least **two more people** would step up to help pull information out of Slack. Even if you don't want to write the formal drafts, you can just leave notes on the Trello cards to be composed at the end of the day.

## In Closing
[[ Summarize and call to action for tomorrow ]]

### Today's Collaborator Credits

[[ A list of everyone who has contributed today ]]

[//]: # (Copy the following section into a Markdown file to enable linking by using the first part as URL)

[#access-requests]: https://dappsociety.slack.com/messages/C9498BH8C
[#attachments]: https://dappsociety.slack.com/messages/C96PYAY6N
[#ballot-box]: https://dappsociety.slack.com/messages/C94SG4VK7
[#community-management]: https://dappsociety.slack.com/messages/C93ARTCGG
[#content-kiosk]: https://dappsociety.slack.com/messages/C93U0SZQB
[#dapp-ideas]: https://dappsociety.slack.com/messages/C93V1MS1J
[#design]: https://dappsociety.slack.com/messages/C95CY7JEN
[#general]: https://dappsociety.slack.com/messages/C93CZR93K
[#group-contracts]: https://dappsociety.slack.com/messages/C9403E24A
[#group-repos]: https://dappsociety.slack.com/messages/C94PPRAD8
[#introductions]: https://dappsociety.slack.com/messages/C93U4JT99
[#needhelp]: https://dappsociety.slack.com/messages/C941CS55H
[#off-topic]: https://dappsociety.slack.com/messages/C953DAS2H
[#social-media]: https://dappsociety.slack.com/messages/C95HEF336

[trello town hall]: https://trello.com/b/Gpm7rwac/town-hall
[trello community management]: https://trello.com/b/3r6vlDXn/community-management
[trello daily digest]: https://trello.com/b/JIUk7VsQ/daily-digest
[trello dapp ideas]: https://trello.com/b/UNFkVdpL/dapp-ideas

[trello poll list]: https://trello.com/c/CyOTAFX8

```
