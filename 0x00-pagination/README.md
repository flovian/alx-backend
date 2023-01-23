# 0x00. Pagination

## Description
What you should learn from this project:

---

### [0. Simple helper function](./0-simple_helper_function.py)
* Write a function named index_range that takes two integer arguments page and page_size.
  * The function should return a tuple of size two containing a start index and an end index corresponding to the range of indexes to return in a list for those particular pagination parameters. 

### [1. Simple pagination](./1-simple_pagination.py)
* Copy index_range from the previous task and the following class into your code  
 * Implement a method named get_page that takes two integer arguments page with default value 1 and page_size with default value 10.


### [2. Hypermedia pagination](./2-hypermedia_pagination.py)
* Replicate code from the previous task.
* Implement a get_hyper method that takes the same arguments (and defaults) as get_page and returns a dictionary 

### [3. Deletion-resilient hypermedia pagination](./3-hypermedia_del_pagination.py)
* The goal here is that if between two queries, certain rows are removed from the dataset, the user does not miss items from dataset when changing page.

