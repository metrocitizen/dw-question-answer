=== DW Question & Answer ===
Contributors: DesignWall
Tags: question, answer, support, quora, stackoverflow
Requires at least: 3.0.1
Tested up to: 3.8
Stable tag: 1.1
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Your WordPress site will have a full-featured Question & Answer section like Stack Overflow, Quora or Yahoo Answers

== Description ==

Developed by [DesignWall](http://www.designwall.com/?utm_source=readme&utm_medium=description_tab&utm_content=plugin_link&utm_campaign=dwqa_plugin), DW Question & Answer is a FREE [WordPress Plugin](http://www.designwall.com/wordpress/plugins/) in which builds up a Question & Answer system on your WordPress site.

* [Github Project](https://github.com/designwall/DW-Question-Answer)

Your WordPress site will have a full-featured Question & Answer section like Stack Overflow, Quora or Yahoo Answers. Your users can Submit question, Search and Filter questions by status, get answered from others. Users can comment and reply to a question or an answer, can vote and definitely can pick one best answer for their questions.

Here is the list of features of this plugin:

* Submit Question
* Order Question by Category, Tags
* Add Answer to Question
* Choose Best Answer for Question
* Comment for Question / Answer
* Vote Question / Answer
* Customizable Notification Email regarding new Question / Answer and Comment 
* Quick Questions filter 
* Manages Question by status
* Instant Search by keywords

[youtube http://www.youtube.com/watch?v=usS9ug0pI7A]

== Installation ==

1. Upload `dw-question-answer` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Log In to your WordPress Dashboard and go to menu `Dashboard > DW Q&A > Settings` then choose pages where to put submit question form and list questions page.

== Screenshots ==

1. Front-end appearance
2. Ask question page
3. Single question page
4. Search page with Instant search function
5. Back-end settings

== Changelog ==

= 1.1 =
* Fixed: Don't automatically pick the best answer which has the most votes ( at least 3 votes)
* Fixed: Only admin and author's question can read the best answer
* Fixed: Can still add answer comment for closed questions
* Fixed: Display number of answers incorrectly
* Fixed: Link format in comment box displays incorrectly after editing
* Fixed: After following the question, will change the tooltip to "Unfollow this question"
* Fixed: Draft answers publish automatically when change status of the draft answers
* Fixed: Missing avatar of anonymous after posting comment
* Fixed: Subscriber can change private/public questions of other people
* Fixed: Anonymous can follow the question
* Fixed: Private question owners can not read their own private answers
* Fixed: Answers disappear after answer author changes status from public to private
* Fixed: Permalinks don't displays properly as in back-end settings
* Fixed: Ordered by bulleted list and numbered list don't display properly after posting answers
* Fixed: Still show "Edit/delete" icon on question comment after disabling "edit" comment
* Fixed: Tags filtering displays the results incorrectly
* Fixed: Anonymous can not post comments after enabling  anonymous to post the comments
* Fixed: Permalinks don't work properly after refreshing
* Tweak: Missing "flag" function at front-end after disabling "edit"/"delete" answer in back-end
* Tweak: Not highlight "questions" page on the menu when viewing a single question
* New: Filter Questions which have new comments
* New: New user interface
* New: Add option to enable/disable notification email in back-end
* New: Add registering form
* New: Follow/Unfollow questions
* New: Switch question/answer between Private and Public

= 1.0.4 =
* Fixed: Can not publish Private question.
* Fixed: Link format in question comment box does not display properly.
* Fixed: Replace text "by by" under the question with " by -question author"
* New: Use new vector-based icon for DW Q&A Menu 

= 1.0.3 =

* Fixed: Missing attribute "class" when insert codes to <code> tag on Answer Editor
* Fixed: Input's placeholder disappeared on IE 8,9 in submit question page
* Fixed: Time is incorrect when add question/answer/comment
* Fixed: duplicate answer after changing status of the question
* Fixed: Line spacing between code lines becomes larger after editting
* Fixed: Can not post comment on IE 8
* Fixed: Time stamp is overlapped by avatar

* Tweak: Auto create 2 pages: "Questions" & "Ask" when active plugin
* Convert links when add new comment
* Have a message to inform number of charaters for title box

* New: Permission Settings - allow you to set permissions for default user roles: read, post, edit and delete either questions, answers or comments

= 1.0.2 =

* Tweak: When user add a new comment/answer, status of question is changed to "open".
* Fixed: Do not press "enter" key to post new comment.
* Fixed: The answer cloned automatically after changing question status.
* Fixed: When flag an answer, the answer should be automatically hidden.
* Fixed: Function to Show/Hide an answer after flagging the answer works incorrectly.
* Fixed: Question link and "View Comment" button don't work on new comment to question notification email.
* Fixed: Can pick best answer for a draft answer.
* Fixed: Filter functions don't work on IE8.
* Fixed: Related questions were not being displayed by related Tags & Categories.
* Fixed: Timestamp of the comment in the single post is incorrect after activating DW QA plugin.
* Fixed: Questions don't appear on IE9.
* New: Ready to translate into your native language. 


= 1.0 =

* The first version of DW Question & Answer