# My First Multipage Project
* Objective - To implement a multipage web project.
    * Each web-page should showcase a different skill or feature of HTML / CSS
* Purpose - To recap on learned material

## Part 1 - Clone the project
* Begin by _forking_ this project into a personal repository.
   * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the _newly forked repository_.
* Clone the repository from **your account** into the `~/dev` directory.
* Open the newly cloned project in a code editor (Visual Studio Code, for example).

## Part 2 - Demonstrate Feature Familiarity
* Each `.html` file in this project has a title which describes the intended feature to be implemented.
    * `my-definition-list.html` file should have a [definition list](https://www.w3schools.com/tags/tag_dl.asp) using the following format

    ```HTML
    <dl> <!-- definition list -->
        <dt></dt> <!-- definition term-->
        <dd></dd> <!-- definition -->
    </dl>
    ```



    * `my-ordered-list.html` file should have an [ordered list](https://www.w3schools.com/tags/tag_ol.asp) using the following format

    ```HTML
    <ol> <!-- ordered list -->
        <li> <!-- list item-->
        </li>
    </ol>
    ```



    * `my-unordered-list.html` file should have an [unordered list](https://www.w3schools.com/tags/tag_ul.asp) using the following format

    ```HTML
    <ul> <!-- unordered list -->
        <li></li> <!-- list item -->
    </ul>
    ```

    * `my-column-of-rows.html` file should have a [table of columns of several rows](https://www.w3schools.com/tags/tag_tr.asp) using the following format

    ```HTML
    <table> <!-- table -->
        <tr> <!-- table row-->
            <td> <!-- table data -->
            </td>
        </tr>
    </table>
    ```

    * `my-row-of-columns.html` file should have a [table of rows of several columns]() using the following format

    ```HTML
    <table> <!-- table-->
        <tr> <!-- table row -->
        </tr>
    </table>
    ```

## Part 3 - Creating navigation
* Ensure that there is a _navigation path_ that makes it possible to view each of the pages.
    * A _navigation path_ is a set of links from one web page to another that allows internet users to _navigate_ through the web.

## Part 3 - Rename files
* Rename each of the files to better match the content of the actual page.
    * For example, if `my-row-of-columns.html` contains several columns of bunny-images, rename `my-row-of-columns.html` to `bunny-images.html`.

## Part 4 - Refactor Navigation Paths
* Because each of the file names have been changed, create a

## Part 5 - Stylize your WebPage
* Modify the `style.css` file to ensure that each web page has a _cool style_.


## Part 6 - Refactor your Table
* Refactor your tables to use `div` tags rather than `table`, `tr`, and `td` tags.

#### Sample Refactor

##### Using `table`, `tr`, and `td` tags

```html
<table>
    <tr>
        <td>
        </td>
    </tr>
</table>
```


##### Using `div` tags

```html
<div class="row">
  <div class="column"></div>
</div>
```



