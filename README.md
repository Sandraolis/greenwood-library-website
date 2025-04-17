# greenwood-library-website
## Mongan's Work: Adding Book Reviews.
1. ### Create and switch to New branch.
``` bash
git checkout main
git pull origin main
git branch add-book-reviews
```
![branch](img/branch.png)

2. ## Stage and Commit Changes:

``` bash
git add book_reviews.html
git commit -m "Add book reviews section"
git push origin add-book-reviews
```
![commit](img/commit.png)

`The push origin add-book-reviews`

![push](/img/push.png)

3. ## Creating Pull Request for Morgan's Work
### Steps:

1. Navigate to the cloned Github repository
2. Click "Compare & pull request" for add-book-reviews

![compare](img/compare-n-pull.png)

![PR](/img/PR.png)
below the pull request page, you wouls see create pull request. click on it
![merge](/img/merge.png)

4. Merging to Main
``` bash
git checkout main
git merge add-book-reviews
git push origin main
```
![merge--2](/img/merge--2.png)
![pull](/img/git%20checkout%20and%20pull.png)

# Jamies work: Updating Events Page
1. ## Create and Switch to New Branch:

``` bash
git checkout main
git pull origin main
git checkout -b update-events
```
![update](/img/update-events.png)

2. ## Staging and Commiting Change:
``` bash
git add .
git commit -m "this is the homepage"
git push origin update-events
 ```
 ![add&commit](/img/add&commit.png)

 3. ## Creating Pull Request for Morgan's Work:
 Confirm compare and pull request

 ![cnp22](/img/CND22.png)

 click on the pull request

 ![CPP](/img/CPP.png)

 Confirm that there is no conflict

 ![noconflict](/img/no-conflicy-merge.png)

 switch to main branch and pull

 ![mainpull](/img/mainpull.png)
