# RFC for the 7XX Range of HTTP Status codes - Developer Errors

At Railscamp X it became clear there is a gap in the current HTTP specification.

There are many ways for a developer to screw up their implementation, but no code to share the nature of the error with the end user.

We humbly suggest the following status codes are included in the HTTP spec in the 7XX range.

  * 701 - Meh
  * 702 - Emacs
  * 71X - Novelty Implementations
    - 710 - PHP 
    - 711 - Convenience Store
    - 719 - I am not a teapot
  * 72X - Edge Cases
    - 720 - Unpossible
    - 721 - Known Unknowns
    - 722 - Unknown Unknowns
    - 723 - Tricky
    - 724 - This line should be unreachable
    - 725 - It works on my machine
    - 726 - It's a feature, not a bug
  * 73X - Fucking
    - 731 - Fucking Rubygems
    - 732 - Fucking Unicode
    - 733 - Fucking Deadlocks
    - 734 - Fucking Deferreds
    - 735 - Fucking IE
    - 736 - Fucking Race Conditions
    - 737 - FuckThreadsing
    - 738 - Fucking Bundler
    - 739 - Fucking Windows
  * 74X - Meme Driven
    - 741 - Compiling
    - 742 - A kitten dies
    - 743 - I thought I knew regular expressions
    - 744 - Y U NO write integration tests?
    - 745 - I don't always test my code, but when I do I do it in production
    - 746 - Missed Ballmer Peak
    - 747 - Motherfucking Snakes on the Motherfucking Plane
    - 748 - Confounded by Ponies
    - 749 - Reserved for Chuck Norris 
  * 75X - Syntax Errors
    - 750 - Didn't bother to compile it
    - 703 - Syntax Error
  * 76X - Substance-Affected Developer
    - 761 - Hungover
    - 762 - Stoned
    - 763 - Over-Caffeinated
    - 764 - Under-Caffeinated
    - 765 - Railscamp
    - 766 - Sober
    - 767 - Drunk
  * 77X - Predictable Problems
    - 771 - Cached for too long
    - 772 - Not cached long enough
    - 773 - Not cached at all
    - 774 - Why was this cached?
    - 776 - Error on the Exception
    - 777 - Coincidence
    - 778 - Off By One Error
    - 779 - Off By Too Many To Count Error
  * 78X - Somebody Else's Problem
    - 781 - Operations
    - 782 - QA
    - 783 - It was a customer request, honestly
    - 784 - Management, obviously
    - 785 - TPS Cover Sheet not attached
  * 79X - Internet crashed
    - 799 - End of the world