# GIT AND GITHUB ASSIGNMENT
- Let’s write a book! You’re building a book app. It has the feature for the author to add a book. We’ll be working on that feature of the app today. (Don’t worry we’ll be using text files for now)
- Fork this repo - [https://github.com/gtech-mulearn/git-n-github](https://github.com/gtech-mulearn/git-n-github)
- Once the fork is made, clone the repo using the SSH option. (Google if you don’t know how to)
- After you’ve cloned it locally, do the list command, you should be able to see the repo now.
- Change directory into the cloned repo folder.
- Make a new branch called `develop`
- You would now see a folder named book and two files inside in it. Let it be there for reference. Don’t bother about it much.
- Do a `git status` 
- You should now be able to see that the working tree is clean.
- Make another directory in the root of the app, with your **full name.** Eg: `bijoy_sijo_book_app`
- Change directory into it. 
- Now, create another directory inside your book app directory called `add_books_feature` 
- Let’s build some features in it now!
- Now let’s make two text files in your books_feature directory.
    1. Add a `create_book.txt` file.
    2. Add the text `"This is the feature for the author to add a new book."` in to the create_book.txt file.
    3. Let’s commit your change now. 
    4. Next, create another file named `list_all_books.txt`
    5. Add the text `“This is the feature which shows the user all the books they’ve created as a list.”` to the list_all_books.txt
    6. Let’s add your change now. 
- Uh oh! You just realised that you don’t need to add the change made to list_all_books.txt now.
- Unstage the list_all_books.txt. (If you don’t know the command, try a `git status` and read the output 😉. or Google for it)
- You realise that, since, list_all_books.txt is another feature, you decide to complete developing it on another branch. **Checkout to main branch first** and then create a new branch called `feature` and commit the list_all_books.txt file and it’s changes in that branch.
- In the same feature branch, now let’s make another change, to your list_all_books.txt file add the text `"List all books will list all books in ascending order."` You just added a new feature. 
- Check the log to see the changes you’ve made so far.
- Let’s commit it. Your feature branch should ideally have a minimum of two commits now. 
- Now, to push back your changes and conrtibute your code to the GTech µLearn Github repository, you need to raise a Pull Request (പേടിക്കണ്ട നമുക്ക് സെറ്റ് ആക്കാം).
- But before that, remember that you now have two different branches, namely, `develop` and `feature` The commits you made so far are in two branches. Let’s merge them together to get a complete project with all features and then push back to the GTech µLearn Github to raise a Pull Request.
- Checkout to the `develop` branch and then merge the `feature` branch into develop branch. 
- Once the merge is complete. Push the develop branch to the remote.
- Navigate to your forked repo in your Github.
- Find the option to open a PR. Open your PR from your develop branch to the main branch of the GTech µLearn repo. Give your PR a meaningful title and description. Open the PR.
