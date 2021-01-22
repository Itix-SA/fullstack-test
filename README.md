# Itix SA / Luxcaddy

## Laravel Backend Test
Thanks for applying for our Fullstack position here at Itix. We have prepared this rather simple test to have an idea of your current ability and see how you choose to structure code.

### Objective
The objective of this test is to build an API that does simple CRUD operations and displays it on a Vue frontend.

### Tasks (Backend)
1. Create endpoint /news with the 4 basic operations: Create, Read, Update and Delete.
2. News should have the following attributes: id (int), title (string), author_id (int), article (string), is_published (bool). All these fields are required.
3. The endpoint that returns the articles should accept pagination, basic filters and sorting.

### Tasks (Frontend)
1. Create 2 pages:
1.1 A page that lists all the news
1.2 A page where you can see, create OR edit a specific news.
1.2.1 For the article creation part, use an existing WYSIWYG editor.
2. Field validation is required.
3. Successful/error messages should be shown as a Toasts or Snackbars.

### Suggestions
1. Feel free to use 3rd party packages if you feel it's justified, don't reinvente the wheel if it's not necessary.
2. Make sure you include all necessary files/settings to setup test environment. (migration files, configs, documentation, etc)
3. Do what you understand a "RESTful" API should be.
4. We care about performance, we consider how "expensive" your code is (less API calls is better).
5. Unit tests are welcomed.

## Others
Once you are done, push it to your own repository and share the link in the mail provided with this challenge.
