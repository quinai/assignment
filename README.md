# Quin AI Assignment
Quin AI Assignment for Software Developers (Last Update: Jun 14, 2022)

An imaginary business team came up with a request. They want a simplified task management app. They say that they use every possible task management tool but they could not handle the complexity. 


Business Requirements
----

:white_medium_square: Each entry must have a unique identifier, entry code, assignee, tag(s), due date, creation date and update date fields

:white_medium_square: Each entry must be in a List. (For example TODO, In Progress etc.)

:white_medium_square: Each entry can have parent and sub entries. 

:white_medium_square: Duplicate entries must eliminated. (Due to migration there would be duplicates in db, you can go through entry code to eliminate duplicates)

:white_medium_square: Entries must be sorted by recent views. (Bonus)

:white_medium_square: Tag is a free text field. Users sometimes misspell the tag. You need to correct misspelled words as you get the entry request. (Bonus)

Technical Requirements
----

:white_check_mark: Programming Language: Golang preferred

:white_check_mark: Application: A Web Api

:white_check_mark: DB: No Infrastructure wanted. You can just mock Database operations in own its own layer. Keep in mind that we are not examining your infrastructure usage skills.  

:white_check_mark: Unit Tests are required

:white_check_mark: Be aware of concurrent operations 



