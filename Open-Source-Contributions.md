## Open source contribution policy
Our policy favors open source contributions and our team engineers should be rewarded with that visibility. Additionally, we also want to encourage a positive ecosystem with all our partners. As such:

* If you find a bug in an open source package, you absolutely should open a ticket.
* If you know what is going on you should absolutely fix it.
* You should connect your corporate email to your github/gitlab account so you can filter relevant emails to be notified in the right place.
* If the right place for a change is in a library, look there to solve it first. Avoiding duplicating packages or writing wrappers to solve for missing functionality.

### Business related functionality
We never share business logic between services, that's the service boundary. And so don't put business logic in a package, even one that we own. It doesn't matter if the package is public or not, a library is not the right place for it. If functionality is frequently or necessarily needed to be reused between many services, and it's business related, let's move that to one of our services.