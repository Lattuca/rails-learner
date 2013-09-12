rails-learner
=============

After 6 sessions of SacRuby.new, attendees have had a chance to learn the basics of Ruby,
the Ruby ecosystem of common tools, techniques such as Test Driven Development, and a
brief introduction to Rails.

This project is something of a check-point test. Rather than it being done with the entire
class, instead you will be tasked with satisfying the requirements on your own or with
your coding partner(s).

Requirements
============

You are going to build a simple Task management app in Ruby on Rails. You need to satisfy
the following use cases:

1. User can enter new tasks with a description of the tasks and an optional due date
2. User can view existing tasks in a date sorted list, with tasks with no due date on top
3. User can mark task as completed.
4. User can see completed tasks sorted at the bottom of the task list in order of completion.
5. User can not set task due dates in the past.

Technical requirements
======================

You should verify these requirements through testing:

1. Your model should have a task description
2. Your model should require that an optional due date be in the future
3. Your model should remember the date when it was completed
4. Your model can be "undone" and have its completion date cleared

Optional requirements
=====================

If you have time, add the following use cases:

1. Graphically identify completed tasks in the list with strikethru or other design element
2. Provide a means of dynamically marking tasks done from the list
3. If you do #2, make sure the list is updated
