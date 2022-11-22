# ECE444-F2022-Lab6

Part 1: Link to heroku-deployed app (from the contents of this git repo): https://infinite-shelf-92743.herokuapp.com/

Part 2: Link to tests added to group project: https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-19-omega/blob/635b93a5e93c57b081357532ac59bf8e2575c5f2/Education_Pathways/feature_json.py#L39

The tests are "test_userwishlist_add_course", "test_userwishlist_delete_course", and "test_userwishlist_to_json".

Note: tests were already merged into main, the comment with the name is not.

Part 3:

One pro of test-driven-development is that it helps you find bugs in your implementation much quicker, compared to not using this process. When writing code in a highly coupled and non-modularized manner to implement something, bugs with the implementation become much harder to find due to all the moving parts in the code. Testing afterwards is more difficult as well. With test-driven development, because you are first writing tests and then implementing the required behavior to cause them to pass, you can immediately catch an implementation bug before it ends up affecting the rest of the system. This saves a lot of time debugging, and allows you to incrementally verify the correctness of the system, as opposed to trying to verify that the entire system works correctly all at once at the end of the development process.

Another pro of test-driven development is that it makes code easier to maintain because you have a full and up-to-date test-suite present during the development process. Since the functionality of the code is clear from the test cases, it is clear for new contributors to the codebase and veterans alike what the code should be doing. Furthermore, it makes adding new tests easier since the framework is already present, as opposed to trying to add tests after all of the code has already been written. The path to what functionality must be written and tested is made clearer using this development process.

One con of test-driven development is that it can slow down the development process in the initial stages because time is taken to write tests. Writing and maintaining a test suite can take a substantial amount of time, and this may affect how quickly products can be prototyped and pushed out, which can have important business implications if the process takes too long and deadlines cannot be met.

Another con of test-driven development is that it's more difficult to modify a project midway to use the process. Older and larger codebases may have their own practices or pipelines that impede the adapting of the code to this new process, which can mean a significant time is spent on changing the development process. This might be unreasonable or not worth it, depending on the project.
