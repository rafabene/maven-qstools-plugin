jdf-stacks-client Contributing Guide
====================================

Basic Steps
-----------

To contribute with Stacks client, clone your own fork instead of cloning the main Stacks client repository, commit your work on topic branches and make pull requests. In detail:

1. [Fork](https://github.com/jboss-jdf/jdf-stacks-client/fork_select) the project.

2. Clone your fork (`git@github.com:<your-username>/jdf-stacks-client.git`).

3. Add an `upstream` remote (`git remote add upstream git@github.com:jboss-jdf/jdf-stacks-client.git`).

4. Get the latest changes from upstream (e.g. `git pull upstream master`).

5. Create a new topic branch to contain your feature, change, or fix (`git checkout -b <topic-branch-name>`).

6. Make sure that your changes is formatted using the JBoss AS profiles found at http://github.com/jboss/ide-config/tree/master/

7. Run the tests

        mvn test

8. Commit your changes to your topic branch.

9. Push your topic branch up to your fork (`git push origin  <topic-branch-name>`).

10. [Open a Pull Request](http://help.github.com/send-pull-requests/) with a clear title and description.

If you don't have the Git client (`git`), get it from: <http://git-scm.com/>

